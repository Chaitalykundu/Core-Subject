# ETL incremental data load

- identify what data has changed in the source
- only process rows that have changes since last ETL load
- this problem space is referred to change data capture
- most source won't tell us what has changed

&nbsp;

&nbsp;

# SQL Server change data capture

- SQL server tracts which rows have changed in the source
- Helps you read only rows that have changed
- Easy to determine insert, update and delete actions
- Load data that has changes since last ETL load

&nbsp;

&nbsp;

# Enable CDC in database

- CDC is intended for sources that reside on a sql server 2008 