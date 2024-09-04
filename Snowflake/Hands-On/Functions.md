# get_ddl('type_of_the_object', 'name_of_the_object')

`get_ddl()` function takes 2 parameter.

    1. Type of the object
    2. Name of the object

&nbsp;

### Syntax

```sql
SELECT get_ddl('type_of_the_object', 'name_of_the_object')
```

&nbsp;

### Example

```sql
SELECT get_ddl('table', 'EMP_BASIC');
```

```
+-----------------------------------------+
| GET_DDL('TABLE', 'EMP_BASIC')           |
|-----------------------------------------|
| create or replace TABLE EMP_BASIC (     |
|       FIRST_NAME VARCHAR(16777216),     |
|       LAST_NAME VARCHAR(16777216),      |
|       EMAIL VARCHAR(16777216),          |
|       STREETADDRESS VARCHAR(16777216),  |
|       CITY VARCHAR(16777216),           |
|       START_DATE DATE                   |
| );                                      |
+-----------------------------------------+
```

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;
