# SQL CREATE DATABASE Statement

The **_CREATE DATABASE_** statement is used to create a new SQL database.

- Syntax : To create a database

  > CREATE DATABASE database_name;

- Example :

  ```
  CREATE DATABASE students;
  ```

&nbsp;

&nbsp;

# SQL CREATE TABLE Statement

The **_CREATE TABLE_** statement is used to create a new table in a database.

- Syntax :

  > > >

        CREATE TABLE table_name (
        column1 datatype,
        column2 datatype,
        column3 datatype,
        ....
        );

  > > >

* The **column** parameters specify the names of the columns of the table.

* The **datatype** parameter specifies the type of data the column can hold (e.g. varchar, integer, date, etc.).

* Example :

  ```
  CREATE TABLE Persons (
      PersonID int,
      LastName varchar(255),
      FirstName varchar(255),
      Address varchar(255),
      City varchar(255)
  );
  ```

&nbsp;

&nbsp;

# Create Table Using Another Table

- A copy of an existing table can also be created using CREATE TABLE.

- The new table gets the same column definitions. All columns or specific columns can be selected.

- If you create a new table using an existing table, the new table will be filled with the existing values from the old table.

* Syntax

  ```
  CREATE TABLE new_table_name AS
  SELECT column1, column2,...
  FROM existing_table_name
  WHERE ....;
  ```

* Example :

  ```
  The following SQL creates a new table called "TestTables" (which is a copy of the "Customers" table):

            CREATE TABLE TestTable AS
            SELECT customername, contactname
            FROM customers;
  ```
