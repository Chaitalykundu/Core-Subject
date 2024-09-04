# Start SnowSQL to connect to Snowflake

1. Open a command line window.

2. Start SnowSQL:

   > snowsql -a <account_identifier> -u <user_name>

&nbsp;

- <account_identifier> is the unique identifier for your Snowflake account. ( this is the part before snowflakecomputing.com)

- <user_name> is the login name for your Snowflake user.

&nbsp;

&nbsp;

If your Snowflake user doesn’t have a default warehouse, database, and schema, or if you didn’t configure SnowSQL to specify a default warehouse, database, and schema, the prompt displays no warehouse, no database, and no schema. For example:

> user-name#(no warehouse)@(no database).(no schema)

&nbsp;

&nbsp;
