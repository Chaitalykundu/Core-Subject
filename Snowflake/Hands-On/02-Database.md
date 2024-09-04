# Overview

- What is Database
- Create database
- Create Database followed by comment
- Check current database
- Check all databases
- Change database

&nbsp;

&nbsp;

&nbsp;

# Database

Database is a **collection of similar and organized data**

&nbsp;

&nbsp;

# Create database

## Syntax

```sql
CREATE DATABASE database_name;
```

&nbsp;

## Example

```sql
CREATE DATABASE sf_tuts;
```

&nbsp;

```
+----------------------------------------+
| status                                 |
|----------------------------------------|
| Database SF_TUTS successfully created. |
+----------------------------------------+
```

&nbsp;

&nbsp;

# Create Database followed by comment

## Syntax

```sql
CREATE DATABASE database_name
comment = "This is my demo database";
```

&nbsp;

```
+-----------------------------------------+
| status                                  |
|-----------------------------------------|
| Database STUDENTS successfully created. |
+-----------------------------------------+
```

The database and schema you just created are now in use for your **current session**, as reflected in the SnowSQL command prompt.

&nbsp;

&nbsp;

# Check current database

```sql
 SELECT CURRENT_DATABASE();
```

&nbsp;

```
+--------------------+
| CURRENT_DATABASE() |
|--------------------|
| STUDENTS           |
+--------------------+
```

&nbsp;

&nbsp;

# Check all databases

```sql
SHOW databases;
```

&nbsp;

&nbsp;

# Change database

```sql
USE database_name;
```

&nbsp;

```
+----------------------------------+
| status                           |
|----------------------------------|
| Statement executed successfully. |
+----------------------------------+
```
