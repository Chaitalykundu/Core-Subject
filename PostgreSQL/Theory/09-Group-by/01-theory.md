# Overview

- how to use the PostgreSQL GROUP BY clause
- Evaluation
- Syntax

&nbsp;

&nbsp;

&nbsp;

# GROUP BY clause

The `GROUP BY` clause divides the rows returned from the `SELECT` statement into groups.

Use the PostgreSQL `GROUP BY` clause to divide rows into groups and apply an **aggregate function** to each group.

For each group, you can apply an `aggregate function` such as `SUM()` to calculate the sum of items or `COUNT()` to get the number of items in the groups.

&nbsp;

&nbsp;

# Evaluation

PostgreSQL evaluates the GROUP BY clause after the FROM and WHERE clauses and before the HAVING, SELECT, DISTINCT, ORDER BY and LIMIT clauses.

> FROM > WHERE > GROUP BY  >  SELECT > DISTINCT > ORDER BY > LIMIT

&nbsp;

&nbsp;

# Syntax

```sql
SELECT 
   column_1, 
   column_2,
   ...,
   aggregate_function(column_3)
FROM 
   table_name
GROUP BY 
   column_1,
   column_2,
   ...;
```

&nbsp;

&nbsp;

