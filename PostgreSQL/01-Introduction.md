# Overview

- What is PostgreSQL
- Features of PostgreSQL
- PostgreSQL Supported programming languages
- What is pgadmin
- Difference between PostgreSQL and pgadmin
- What are the other database engine
- Connect to the Database

&nbsp;

&nbsp;

&nbsp;

# What is PostgreSQL

PostgreSQL is free open-source Object-Relational Database Management System.

PostgreSQL is a back-end database for dynamic websites and web applications.

It is modern

&nbsp;

## Features of PostgreSQL

- Robustness

- Reliability

- Advanced features

- Provides a powerful and scalable platform for managing large number of structured data

- PostgreSQL supports a wide range data types, indexing option and query optimization techniques

- It offers ACID compliance and supports transactions which insures data integrity and reliability.

- PostgreSQL supports both relational (SQL) and non-relational (JSON) queries.

&nbsp;

&nbsp;

# PostgreSQL Supported programming languages

PostgreSQL supports the most important programming languages:

- Python
- Java
- C/C++
- C#
- Node.js
- Go
- Ruby
- Perl
- Tcl

&nbsp;

&nbsp;

# What is pgadmin

- **pgadmin** is a free and open source administration and development platform for managing PostgreSQL databases.

- It is widely used as a primary tool for PostgreSQL database administration.

- It offers a range of features, including database object management (such as creating tables, views and indexes), querying and editing data, monitoring database activity and managing server setting.

&nbsp;

&nbsp;

# Difference between PostgreSQL and pgadmin

| PostgreSQL                                                              | pgadmin                                                 |
| ----------------------------------------------------------------------- | ------------------------------------------------------- |
| It is a SQL Engine that store data, read queries and return information | It is the User Interface for connecting with PostgreSQL |

&nbsp;

&nbsp;

# Other database engine

1. MySQL
2. Oracle
3. SQL Server by microsoft

&nbsp;

&nbsp;

# Connect to the Database

There are several ways to connect to the database, we will look at two ways in this tutorial:

- SQL Shell (psql)
- pgAdmin 4

Both of them comes with the installation of PostgreSQL

&nbsp;

&nbsp;

# Connect to the Database using SQL shell

### Steps

1. open pgadmin
2. open sql shell
3. in sql shell press enter for different options and enter password

&nbsp;

### Note

SQL Shell waits for the semicolon and executes all lines as one SQL statement.

A multiple lines SQL statement is not executed before we include a semicolon at the end.

&nbsp;

&nbsp;

# Check the version

```sql
SELECT version();
```

&nbsp;

&nbsp;

# Connect to the Database using pgadmin

### Steps

1. Start pgAdmin4

2. Enter the password
3. Click on the [Database] option on in the left sidebar
4. Find a database named `postgres`, right-click it choose the "Query Tool"

5. Write SQL Statements

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
