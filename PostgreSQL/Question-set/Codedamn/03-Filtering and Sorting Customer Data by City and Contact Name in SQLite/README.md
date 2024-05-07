# Level : Easy

&nbsp;

# Filtering and Sorting Customer Data by City and Contact Name in SQLite

&nbsp;

# Introduction

In this lab, you will be working with the SQLite database northwind.sqlite. Your main task is to construct an SQL query to retrieve specific information from the customers table.

&nbsp;

&nbsp;

# Objective

Your SQL query should fulfill the following requirements:

* Retrieve the city, company_name, and contact_name columns from the customers table.
Filter the records to only include rows where the city name contains the letter 'L'.

* Sort the resulting data set by contact_name in ascending order.

&nbsp;

&nbsp;

# Schema

Schema of the patients table for reference


* patient_id

* first_name

* last_name

* gender

* birth_date

* city

* province_id

* allergies

* height

* weight

&nbsp;

&nbsp;

# Key Concepts


* SELECT Statement: Used to select data from a database. The result is then stored in a result table.

* Aggregate Functions: SQL aggregate functions return a single value, calculated from values in a column. The function MAX() is one such function which returns the maximum value of the selected column.
