# Table

A table is a basic element of a relational database. It stores data in a tabular format, which means the system organizes data into rows and columns.

&nbsp;

&nbsp;

# Create a table

Create a table named **emp_basic** in **sf_tuts.test_schema** using the **_CREATE TABLE_** command:

```sql
CREATE OR REPLACE TABLE emp_basic (
   first_name STRING ,
   last_name STRING ,
   email STRING ,
   streetaddress STRING ,
   city STRING ,
   start_date DATE
   );
```

&nbsp;

```
+---------------------------------------+
| status                                |
|---------------------------------------|
| Table EMP_BASIC successfully created. |
+---------------------------------------+
```

&nbsp;

**If we don't specify the size of the table, it will take automatically.**

&nbsp;

&nbsp;

# Show Table Column details

```sql
desc table EMP_BASIC;
```

```
+---------------+-------------------+--------+-------+---------+-------------+------------+-------+------------+---------+-------------+----------------+
| name          | type              | kind   | null? | default | primary key | unique key | check | expression | comment | policy name | privacy domain |
|---------------+-------------------+--------+-------+---------+-------------+------------+-------+------------+---------+-------------+----------------|
| FIRST_NAME    | VARCHAR(16777216) | COLUMN | Y     | NULL    | N           | N          | NULL  | NULL       | NULL    | NULL        | NULL           |
| LAST_NAME     | VARCHAR(16777216) | COLUMN | Y     | NULL    | N           | N          | NULL  | NULL       | NULL    | NULL        | NULL           |
| EMAIL         | VARCHAR(16777216) | COLUMN | Y     | NULL    | N           | N          | NULL  | NULL       | NULL    | NULL        | NULL           |
| STREETADDRESS | VARCHAR(16777216) | COLUMN | Y     | NULL    | N           | N          | NULL  | NULL       | NULL    | NULL        | NULL           |
| CITY          | VARCHAR(16777216) | COLUMN | Y     | NULL    | N           | N          | NULL  | NULL       | NULL    | NULL        | NULL           |
| START_DATE    | DATE              | COLUMN | Y     | NULL    | N           | N          | NULL  | NULL       | NULL    | NULL        | NULL           |
+---------------+-------------------+--------+-------+---------+-------------+------------+-------+------------+---------+-------------+----------------+
```

&nbsp;

&nbsp;

# Fully qualified name

Fully qualified name consists of database name, schema name & table name

```sql
database_name.schema_name.table_name;
-- or
"database_name.schema_name.table_name";
-- or
"database_name"."schema_name"."table_name";
```

&nbsp;

```sql
SELECT * FROM sf_tuts.test_schema.EMP_BASIC;
SELECT * FROM "sf_tuts.test_schema.EMP_BASIC";
SELECT * FROM "sf_tuts"."test_schema"."EMP_BASIC";
```

&nbsp;

```
+------------+-----------+-------+---------------+------+------------+
| FIRST_NAME | LAST_NAME | EMAIL | STREETADDRESS | CITY | START_DATE |
|------------+-----------+-------+---------------+------+------------|
+------------+-----------+-------+---------------+------+------------+
```

&nbsp;

&nbsp;

# Insert Values Into Table

```sql
INSERT INTO EMP_BASIC(FIRST_NAME,LAST_NAME,EMAIL,STREETADDRESS,CITY,START_DATE)
values('Chaitaly','Kundu', 'chaitaly@gmail.com', 'PG house', 'Pune', '12/02/2022');
```

&nbsp;

```
+-------------------------+
| number of rows inserted |
|-------------------------|
|                       1 |
+-------------------------+
```

&nbsp;

&nbsp;

# Insert Multiple Values Into Table

```sql
INSERT INTO EMP_BASIC(FIRST_NAME,LAST_NAME,EMAIL,STREETADDRESS,CITY,START_DATE)
values('Bhavesh','Mahajan', 'bhavesh@gmail.com', 'PG house', 'Pune', '12/02/2022'),
('Ankita','Kundu','abc@gmail.com','','Siliguri','03/12/21');
```

&nbsp;

```
+-------------------------+
| number of rows inserted |
|-------------------------|
|                       2 |
+-------------------------+
```

&nbsp;

&nbsp;

# Show Table Data

```sql
SELECT * FROM EMP_BASIC;
```

&nbsp;

```
+------------+-----------+--------------------+---------------+----------+------------+
| FIRST_NAME | LAST_NAME | EMAIL              | STREETADDRESS | CITY     | START_DATE |
|------------+-----------+--------------------+---------------+----------+------------|
| Chaitaly   | Kundu     | chaitaly@gmail.com | PG house      | Pune     | 2022-12-02 |
| Chaitaly   | Kundu     | chaitaly@gmail.com | PG house      | Pune     | 2022-12-02 |
| Bhavesh    | Mahajan   | bhavesh@gmail.com  | PG house      | Pune     | 2022-12-02 |
| Ankita     | Kundu     | abc@gmail.com      |               | Siliguri | 0021-03-12 |
+------------+-----------+--------------------+---------------+----------+------------+
```