# Overview

- Using WHERE clause with the OR operator

&nbsp;

&nbsp;

&nbsp;

# Introduction

We use `OR` operator when we need to check at least one condition is true among two or more conditions.
`
# Syntax

```sql
SELECT
  select_list
FROM
  table_name
WHERE
  condition OR condition
ORDER BY
  sort_expression;
```

&nbsp;

&nbsp;

# Example

```sql
SELECT * FROM details WHERE gender='Polygender' OR date_of_birth='19/01/2000' ORDER BY firstname;
```

<img src="../../assets/Where/or.jpg">

&nbsp;

&nbsp;
