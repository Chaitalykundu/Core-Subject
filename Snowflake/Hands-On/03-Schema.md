# Overview

- What is Schema
- Create Schema
- Create Database followed by comment
- Check current Schema
- Check all Schemas
- Change Schema

&nbsp;

&nbsp;

&nbsp;

# Schema

A database schema is a blueprint that defines the structure and organization of a database, including how data is stored and how different elements relate to each other.

&nbsp;

&nbsp;

# Create Schema

## Syntax

```sql
CREATE SCHEMA schema_name;
```

&nbsp;

## Example

```sql
CREATE SCHEMA test_schema;
```

&nbsp;

```
+------------------------------------------+
| status                                   |
|------------------------------------------|
| Schema TEST_SCHEMA successfully created. |
+------------------------------------------+
```

&nbsp;

&nbsp;

# Create Schema followed by comment

## Syntax

```sql
CREATE SCHEMA schema_name
comment = "this is test schema";
```

&nbsp;

```
+-------------------------------------------------------+
| status                                                |
|-------------------------------------------------------|
| Schema TEST_SCHEMA_WITH_COMMENT successfully created. |
+-------------------------------------------------------+
```

The schema you just created are now in use for your **current session**, as reflected in the SnowSQL command prompt.

&nbsp;

&nbsp;

# Check current Schema

```sql
 SELECT CURRENT_SCHEMA();
```

&nbsp;

```
+--------------------------+
| CURRENT_SCHEMA()         |
|--------------------------|
| TEST_SCHEMA_WITH_COMMENT |
+--------------------------+
```

&nbsp;

&nbsp;

# Check all Schemas

```sql
SHOW schemas;
```

&nbsp;

&nbsp;

# Change Schema

```sql
USE SCHEMA schema_name;
```

&nbsp;

```
+----------------------------------+
| status                           |
|----------------------------------|
| Statement executed successfully. |
+----------------------------------+
```
