# Level : Medium

# Filtering Patients by Weight Range in SQLite

Your challenge is to construct an SQL query to achieve the following:

Retrieve the first_name and last_name of patients table.
The query should only select patients whose weight is within the range of 100 to 120 (inclusive).

&nbsp;

&nbsp;

## Table Schema

You have to make use of the patients table. Here is the complete schema of the table for your reference

`patient_id`

`first_name`

`last_name`

`gender`

`birth_date`

`city`

`province_id`

`allergies`

`height`

`weight`

&nbsp;

&nbsp;

## Key Concepts

- SQLite: A C-language library that provides a lightweight disk-based database. It doesn’t require a separate server process.

- SQL SELECT Statement: Used to select data from a database and fetch the result table. The result can be stored in a table or used as it is.

- SQL WHERE Clause: Used to filter the results and extract only the necessary records.

- BETWEEN Operator: In SQL, the BETWEEN operator is used to filter the result set based on a range. It can be used with numbers, text and even dates.
