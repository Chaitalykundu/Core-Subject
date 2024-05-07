# Overview

- how to use the PostgreSQL WHERE clause
- Evaluation
- Syntax
- Operators

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

> FROM > WHERE > GROUP BY > HAVING >  SELECT > DISTINCT > ORDER BY > LIMIT

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

# GROUP BY without an aggregate function

The `GROUP BY` clause removes duplicate values in the column and returns distinct values

## Synrax

```sql
SELECT 
   column_1, 
   column_2,
   ...
FROM 
   table_name
GROUP BY 
   column_1,
   column_2,
   ...;
```

&nbsp;

## Example

```sql
SELECT gender FROM details GROUP BY gender;
```

 In this example, the GROUP BY clause works like the `DISTINCT` operator.

<img src='../../assets/Group-by/without-aggregate.jpg'>  

&nbsp;

&nbsp;

# GROUP BY with SUM() function

The `GROUP BY` clause is useful when used in conjunction with an aggregate function.

# Syntax

```sql
SELECT 
  column_name, 
  SUM (amount) 
FROM 
  table_name 
GROUP BY 
  column_name 
```

&nbsp;

&nbsp;

# Overview

- how to use the PostgreSQL WHERE clause
- Evaluation
- Syntax
- Operators

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

> FROM > WHERE > GROUP BY > HAVING >  SELECT > DISTINCT > ORDER BY > LIMIT

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

