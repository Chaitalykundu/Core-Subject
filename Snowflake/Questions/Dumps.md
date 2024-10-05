# Questions

1. Snowflake provides a mechanism for its customers to override its natural clustering algorithms. This method is:

   - Micro-partitions
   - Clustering keys
   - Key partitions
   - Clustered partitions

   > Clustering keys

2. Which of the following are valid Snowflake Virtual Warehouse Scaling Policies? (Choose two.)

   - Custom
   - Economy
   - Optimized
   - Standard

   > Economy

   > Standard

3. Select the different types of Internal Stages: (Choose three.)

   - Named Stage
   - User Stage
   - Table Stage
   - Schema Stage

   > Named Stage

   > User Stage

   > Table Stage

4. Account-level storage usage can be monitored via

   - The Snowflake Web Interface (UI) in the Databases section
   - The Snowflake Web Interface (UI) in the Account -> Billing & Usage section
   - The Information Schema -> ACCOUNT_USAGE_HISTORY View
   - The Account Usage Schema -> ACCOUNT_USAGE_METRICS View

   > The Snowflake Web Interface (UI) in the Account -> Billing & Usage section

5. Which statement best describes `clustering`?

   - Clustering represents the way data is grouped together and stored within Snowflake's micro-partitions
   - The database administrator must define the clustering methodology for each Snowflake table
   - The clustering key must be included on the COPY command when loading data into Snowflake
   - Clustering can be disabled within a Snowflake account

   > Clustering represents the way data is grouped together and stored within Snowflake's micro-partitions

6. Which of the following commands sets the Virtual Warehouse for a session?

   - COPY WAREHOUSE FROM `<<config file>>`;
   - SET WAREHOUSE = `<<warehouse name>>`;
   - USE WAREHOUSE `<<warehouse name>>`;
   - USE VIRTUAL_WAREHOUSE `<<warehouse name>>`;

   > USE WAREHOUSE `<<warehouse name>>`;

7. Which object allows you to limit the number of credits consumed within a Snowflake account?

   - Account Usage Tracking
   - Resource Monitor
   - Warehouse Limit Parameter
   - Credit Consumption Tracker

   > Resource Monitor

8. What are the three layers that make up Snowflake's architecture? (Choose three.)

   - Compute
   - Tri-Secret Secure
   - Storage
   - Cloud Services

   > Compute

   > Storage

   > Cloud Services

9. Which of the following connectors allow Multi-Factor Authentication (MFA) authorization when connecting? (Choose all that apply.)

   - JDBC
   - SnowSQL
   - Snowflake Web Interface (UI)
   - ODBC
   - Python

   > JDBC

   > SnowSQL

   > Snowflake Web Interface (UI)

   > ODBC

   > Python

10. Which of the following statements describes a benefit of Snowflake's separation of compute and storage? (Choose all that apply.)

    - Growth of storage and compute are tightly coupled together
    - Storage expands without the requirement to add more compute
    - Compute can be scaled up or down without the requirement to add more storage
    - Multiple compute clusters can access stored data without contention

    > Storage expands without the requirement to add more compute

    > Compute can be scaled up or down without the requirement to add more storage

    > Multiple compute clusters can access stored data without contention

11. In which layer of its architecture does Snowflake store its metadata statistics?

    > Cloud Services Layer

12. Which of the following statements are true of Virtual Warehouses? (Choose all that apply.)

    - Customers can change the size of the Warehouse after creation
    - A Warehouse can be resized while running
    - A Warehouse can be configured to suspend after a period of inactivity
    - A Warehouse can be configured to auto-resume when new queries are submitted

    > Customers can change the size of the Warehouse after creation

    > A Warehouse can be resized while running

    > A Warehouse can be configured to suspend after a period of inactivity

    > A Warehouse can be configured to auto-resume when new queries are submitted

13. The PUT command: (Choose two.)

    - Automatically creates a File Format object
    - Automatically uses the last Stage created
    - Automatically compresses files using Gzip
    - Automatically encrypts files

    > Automatically compresses files using Gzip

    > Automatically encrypts files

14. Which type of table corresponds to a single Snowflake session?

    - Temporary
    - Transient
    - Provisional
    - Permanent

    > Temporary

15. What is the minimum Snowflake edition that customers planning on storing protected information in Snowflake should consider for regulatory compliance?

    > Business Critical Edition

16. Select the three types of tables that exist within Snowflake. (Choose three.)

    - Temporary
    - Transient
    - Provisional
    - Permanent

    > Temporary

    > Transient

    > Permanent

17. Which of the following statements are true of Snowflake data loading? (Choose three.)

    - VARIANT null values are not the same as SQL NULL values
    - It is recommended to do frequent, single row DMLs
    - It is recommended to validate the data before loading into the Snowflake target table
    - It is recommended to use staging tables to manage MERGE statements

    > VARIANT null values are not the same as SQL NULL values

    > It is recommended to validate the data before loading into the Snowflake target table

    > It is recommended to use staging tables to manage MERGE statements

18. Which statements are true of micro-partitions? (Choose two.)

    - They are approximately 16MB in size
    - They are stored compressed only if COMPRESS=TRUE on Table
    - They are immutable
    - They are only encrypted in the Enterprise edition and above

    > They are approximately 16MB in size

    > They are immutable

19. A deterministic query is run at 8am, takes 5 minutes, and the results are cached. Which of the following statements are true? (Choose two.)

    - The exact query will ALWAYS return the precomputed result set for the RESULT_CACHE_ACTIVE = time period
    - The same exact query will return the precomputed results if the underlying data hasn't changed and the results were last accessed within previous 24 hour period
    - The same exact query will return the precomputed results even if the underlying data has changed as long as the results were last accessed within the previous 24 hour period
    - The 24 hour timer on the precomputed results gets renewed every time the exact query is executed

    > The same exact query will return the precomputed results if the underlying data hasn't changed and the results were last accessed within previous 24 hour period

    > The 24 hour timer on the precomputed results gets renewed every time the exact query is executed

20. Increasing the maximum number of clusters in a Multi-Cluster Warehouse is an example of:

    - Scaling rhythmically
    - Scaling max
    - Scaling out
    - Scaling up

    > Scaling out

21. Which statement best describes Snowflake tables?

    - Snowflake tables are logical representations of underlying physical data
    - Snowflake tables are the physical instantiation of data loaded into Snowflake
    - Snowflake tables require that clustering keys be defined to perform optimally
    - Snowflake tables are owned by a user

    > Snowflake tables are logical representations of underlying physical data

22. Which item in the Data Warehouse migration process does not apply in Snowflake?

    - Migrate Users
    - Migrate Schemas
    - Migrate Indexes
    - Build the Data Pipeline

    > Migrate Indexes

23. Snowflake provides two mechanisms to reduce data storage costs for short-lived tables. These mechanisms are: (Choose two.)

    - Temporary Tables
    - Transient Tables
    - Provisional Tables
    - Permanent Tables

    > Temporary Tables

    > Transient Tables

24. What is the maximum compressed row size in Snowflake

    - 8KB
    - 16MB
    - 50MB
    - 4000GB

    > 16MB

25. Which of the following are main sections of the top navigation of the Snowflake Web Interface (UI)? (Choose three.)

    - Databases
    - Tables
    - Warehouses
    - Worksheets

    > Databases

    > Warehouses

    > Worksheets

26. What is the recommended Snowflake data type to store semi-structured data like JSON?

    - VARCHAR
    - RAW
    - LOB
    - VARIANT

    > VARIANT

27. Which of the following are common use cases for zero-copy cloning? (Choose three.)

    - Quick provisioning of Dev and Test/QA environments
    - Data backups
    - Point in time snapshots
    - Performance optimization

    > Quick provisioning of Dev and Test/QA environments

    > Data backups

    > Point in time snapshots

28. If a Small Warehouse is made up of 2 servers/cluster, how many servers/cluster make up a Medium Warehouse?

    - 4
    - 16
    - 32
    - 128

    > 4

29. Which is true of Snowflake network policies? A Snowflake network policy: (Choose two.)

    - Is available to all Snowflake Editions
    - Is only available to customers with Business Critical Edition
    - Restricts or enables access to specific IP addresses
    - Is activated using an ג€ALTER DATABASE command

    > Is available to all Snowflake Editions

    > Restricts or enables access to specific IP addresses

30. Query results are stored in the Result Cache for how long after they are last accessed, assuming no data changes have occurred?

    - 1 Hour
    - 3 Hours
    - 12 hours
    - 24 hours
      > 24 hours

31. A role is created and owns 2 tables. This role is then dropped. Who will now own the two tables?

    - The tables are now orphaned
    - The user that deleted the role
    - SYSADMIN
    - The assumed role that dropped the role

    > The assumed role that dropped the role

32. Which of the following connectors are available in the Downloads section of the Snowflake Web Interface (UI)? (Choose two.)

    - SnowSQL
    - ODBC
    - R
    - HIVE>

    > SnowSQL

    > ODBC

33. Which of the following DML commands isn't supported by Snowflake?

    - UPSERT
    - MERGE
    - UPDATE
    - TRUNCATE TABLE

    > UPSERT

34. Which of the following statements is true of zero-copy cloning?

    - Zero-copy clones increase storage costs as cloning the table requires storing its data twice
    - All zero-copy clone objects inherit the privileges of their original objects
    - Zero-copy cloning is licensed as an additional Snowflake feature
    - At the instance/instant a clone is created, all micro-partitions in the original table and the clone are fully shared

    > At the instance/instant a clone is created, all micro-partitions in the original table and the clone are fully shared

35. To run a Multi-Cluster Warehouse in auto-scale mode, a user would:

    - Configure the Maximum Clusters setting to Auto-Scale
    - Set the Warehouse type to Auto
    - Set the Minimum Clusters and Maximum Clusters settings to the same value
    - Set the Minimum Clusters and Maximum Clusters settings to the different values

    > Set the Minimum Clusters and Maximum Clusters settings to the different values

36. The Query History in the Snowflake Web Interface (UI) is kept for approximately:

    - 60 minutes
    - 24 hours
    - 14 days
    - 30 days
    - 1 year

    > 14 days

37. Which of the following terms best describes Snowflake's database architecture?

    - Columnar shared nothing
    - Shared disk
    - Multi-cluster, shared data
    - Cloud-native shared memory

    > Multi-cluster, shared data

38. Which of the following are options when creating a Virtual Warehouse? (Choose two.)

    - Auto-drop
    - Auto-resize
    - Auto-resume
    - Auto-suspend

    > Auto-resume

    > Auto-suspend

39. A Virtual Warehouse's auto-suspend and auto-resume settings apply to

    - The primary cluster in the Virtual Warehouse
    - The entire Virtual Warehouse
    - The database the Virtual Warehouse resides in
    - The queries currently being run by the Virtual Warehouse

    > The entire Virtual Warehouse

40. Fail-safe is unavailable on which table types? (Choose two.)

    - Temporary
    - Transient
    - Provisional
    - Permanent

    > Temporary

    > Transient

41. Which of the following objects is not covered by Time Travel?

    - Tables
    - Schemas
    - Databases
    - Stages

    > Stages

42. Which of the following commands are not blocking operations? (Choose two.)

    - UPDATE
    - INSERT
    - MERGE
    - COPY

    > INSERT

    > COPY

43. Which of the following is true of Snowpipe via REST API? (Choose two.)

    - You can only use it on Internal Stages
    - All COPY INTO options are available during pipe creation
    - Snowflake automatically manages the compute required to execute the Pipe's COPY INTO commands
    - Snowpipe keeps track of which files it has loaded

    > Snowflake automatically manages the compute required to execute the Pipe's COPY INTO commands

    > Snowpipe keeps track of which files it has loaded

44. Snowflake recommends, as a minimum, that all users with the following role(s) should be enrolled in Multi-Factor Authentication (MFA):

    - SECURITYADMIN, ACCOUNTADMIN, PUBLIC, SYSADMIN
    - SECURITYADMIN, ACCOUNTADMIN, SYSADMIN
    - SECURITYADMIN, ACCOUNTADMIN
    - ACCOUNTADMIN

    > ACCOUNTADMIN

45. When can a Virtual Warehouse start running queries?

    - 12am-5am
    - Only during administrator defined time slots
    - When its provisioning is complete Most Voted
    - After replication

    > When its provisioning is complete

46. When should you consider disabling auto-suspend for a Virtual Warehouse? (Choose two.)

    - When users will be using compute at different times throughout a 24/7 period
    - When managing a steady workload
    - When the compute must be available with no delay or lag time
    - When you do not want to have to manually turn on the Warehouse each time a user needs it

    > When managing a steady workload

    > When the compute must be available with no delay or lag time

47. If auto-suspend is enabled for a Virtual Warehouse, the Warehouse is automatically suspended when:

    - All Snowflakes sessions using the Warehouse are terminated.
    - The last query using the Warehouse completes.
    - There are no users logged into Snowflake.
    - The Warehouse is inactive for a specified period of time.

    > The Warehouse is inactive for a specified period of time.

48. The number of queries that a Virtual Warehouse can concurrently process is determined by (Choose two.):

    - The complexity of each query
    - The CONCURRENT_QUERY_LIMIT parameter set on the Snowflake account
    - The size of the data required for each query
    - The tool that is executing the query

    > The complexity of each query

    > The size of the data required for each query

49. Which of the following statements are true of VALIDATION_MODE in Snowflake? (Choose two.)

    - The VALIDATION_MODE option is used when creating an Internal Stage
    - VALIDATION_MODE=RETURN_ALL_ERRORS is a parameter of the COPY command
    - The VALIDATION_MODE option will validate data to be loaded by the COPY statement while completing the load and will return the rows that could not be loaded without error
    - The VALIDATION_MODE option will validate data to be loaded by the COPY statement without completing the load and will return possible errors

    > VALIDATION_MODE=RETURN_ALL_ERRORS is a parameter of the COPY command

    > The VALIDATION_MODE option will validate data to be loaded by the COPY statement without completing the load and will return possible errors

50. What privileges are required to create a task?

    - The GLOBAL privilege CREATE TASK is required to create a new task.
    - Tasks are created at the Application level and can only be created by the Account Admin role.
    - Many Snowflake DDLs are metadata operations only, and CREATE TASK DDL can be executed without virtual warehouse requirement or task specific grants.
    - The role must have access to the target schema and the CREATE TASK privilege on the schema itself

    > The role must have access to the target schema and the CREATE TASK privilege on the schema itself

51. What are the three things customer want most from their enterprise data warehouse solution? (Choose three.)

    - On-premise availability
    - Simplicity
    - Open source based
    - Concurrency
    - Performance

    > Simplicity

    > Concurrency

    > Performance

52. When scaling out by adding clusters to a multi-cluster warehouse, you are primarily scaling for improved:

    - Concurrency
    - Performance

    > Concurrency

53. What is the minimum Snowflake edition that provides data sharing?

    - Standard
    - Premier
    - Enterprise
    - Business Critical Edition

    > Standard

54. Which of the following statements is true of Snowflake?

    - It was built specifically for the cloud
    - It was built as an on-premises solution and then ported to the cloud
    - It was designed as a hybrid database to allow customers to store data either on premises or in the cloud
    - It was built for Hadoop architecture
    - It's based on an Oracle Architecture

    > It was built specifically for the cloud

&nbsp;

&nbsp;

&nbsp;

# Confusion

1. Which of the following roles is recommended to be used to create and manage users and roles?

   - SYSADMIN
   - SECURITYADMIN
   - PUBLIC
   - ACCOUNTADMIN

   > SECURITYADMIN

2. Snowflake is designed for which type of workloads? (Choose two.)

   - OLAP (Analytics) workloads
   - OLTP (Transactional) workloads
   - Concurrent workloads
   - On-premise workloads

   > OLAP (Analytics) workloads

   > Concurrent workloads

3. Credit Consumption by the Compute Layer (Virtual Warehouses) is based on: (Choose two.)

   - Number of users
   - Warehouse size
   - Amount of data processed
   - no of clusters for the Warehouse

   > Warehouse size

   > no of clusters for the Warehouse

4. Which of the following objects can be cloned? (Choose four.)

   - Tables
   - Named File Formats
   - Schemas
   - Shares
   - Databases
   - Users

   > Tables

   > Named File Formats

   > Schemas

   > Databases

5. Why would a customer size a Virtual Warehouse from an X-Small to a Medium?

   - To accommodate more queries
   - To accommodate more users
   - To accommodate fluctuations in workload
   - To accommodate a more complex workload

   > To accommodate a more complex workload

6. Which interfaces can be used to create and/or manage Virtual Warehouses?

   - The Snowflake Web Interface (UI)
   - SQL commands
   - Data integration tools
   - All of the above

   > All of the above

7. When a Pipe is recreated using the CREATE OR REPLACE PIPE command:

   - The Pipe load history is reset to empty
   - The REFRESH parameter is set to TRUE
   - Previously loaded files will be ignored
   - All of the above

   > The Pipe load history is reset to empty

8. Which of the following statements are true of Snowflake releases: (Choose two.)

   - They happen approximately weekly
   - They roll up and release approximately monthly, but customers can request early release application
   - During a release, new customer requests/queries/connections transparently move over to the newer version
   - A customer is assigned a 30 minute window (that can be moved anytime within a week) during which the system will be unavailable and customer is upgraded

   > They happen approximately weekly

   > During a release, new customer requests/queries/connections transparently move over to the newer version

9. The FLATTEN function is used to query which type of data in Snowflake?

   - Structured data
   - Semi-structured data
   - Both of the above
   - None of the above

   > Semi-structured data

### doubt

46. Which of the following languages can be used to implement Snowflake User Defined Functions (UDFs)? (Choose two.)

    - Java
    - Javascript
    - SQL
    - Python

    > All / Java, Python

&nbsp;

77. Which of the following are valid approaches to loading data into a Snowflake table? (Choose all that apply.)

    - Bulk copy from an External Stage
    - Continuous load using Snowpipe REST API
    - The Snowflake Web Interface (UI) data loading wizard
    - Bulk copy from an Internal Stage

    > All / A,B,D

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

# True False

1. A single database can exist in more than one Snowflake account.

   > False

2. Bulk unloading of data from Snowflake supports the use of a SELECT statement

   > True

3. A customer using SnowSQL / native connectors will be unable to also use the Snowflake Web Interface (UI) unless access to the UI is explicitly granted by support.

   > False

4. The COPY command must specify a File Format in order to execute.

   > False

5. Reader Accounts incur no additional Compute costs to the Data Provider since they are simply reading the shared data without making changes.

   > False

6. Snowflake charges a premium for storing semi-structured data.

   > False

7. It is possible to unload structured data to semi-structured formats such as JSON and Parquet.

   > True

8. Data in fail-safe can be deleted by a user or the Snowflake team before it expires.

   > False

9. Snowflake's data warehouse was built from the ground up for the cloud in lieu of using an existing database or a platform, like Hadoop, as a base.

   > True

10. Snowpipe via REST API can only reference External Stages as source.

    > False

11. It is possible to load data into Snowflake without creating a named File Format object.

    > True

12. A table in Snowflake can only be queried using the Virtual Warehouse that was used to load the data.

    > False

13. When a data share is established between a Data Provider and a Data Consumer, the Data Consumer can extend that data share to other Data
    Consumers.

    > False

14. Micro-partition metadata enables some operations to be completed without requiring Compute.

    > True

15. Users are able to see the result sets of queries executed by other users that share their same role.

    > False

16. The user has to specify which cluster a query will run on in a multi-cluster Warehouse.

    > False

17. Pipes can be suspended and resumed.

    > True

18. Multi-Factor Authentication (MFA) in Snowflake is only supported in conjunction with Single Sign-On (SSO).

    > False

19. Some queries can be answered through the metadata cache and do not require an active Virtual Warehouse.

    > True

20. Each worksheet in the Snowflake Web Interface (UI) can be associated with different roles, databases, schemas, and Virtual Warehouses.

    > True

21. You can query the files in an External Stage directly without having to load the data into a table.

    > True

22. An active warehouse is required to run a COPY INTO statement.

    > True

23. AWS Private Link provides a secure connection from the Customer's on-premise data center to the Snowflake.

    > False

&nbsp;

&nbsp;

# Confusion true/ false

### Doubt

1. A third-party tool that supports standard JDBC or ODBC but has no Snowflake-specific driver will be unable to connect to Snowflake.

   > True

### Doubt

2. Query ID's are unique across all Snowflake deployments and can be used in communication with Snowflake Support to help troubleshoot issues.

   > True

3. Snowflake charges additional fees to Data Providers for each Share they create.

   > False

4. When a user creates a role, they are initially assigned ownership of the role and they maintain ownership until it is transferred to another user.

   > False

5. Snowflake's Global Services Layer gathers and maintains statistics on all columns in all micro-partitions.

   > True

&nbsp;

&nbsp;

&nbsp;

# Important Notes

SYSTEM ROLES:

- **ORGADMIN** manages operations at the organizational level

- **ACCOUNTADMIN** performs administrative functions

- **SECURITYADMIN** creates and manages users and roles, and manages grants

- **USERADMIN** creates users and roles

- **SYSADMIN** creates and manages databases, schemas, and warehouses

- **PUBLIC** is available to all users, but (by default) cannot do anything but log in

&nbsp;

We can use select query in copy into command to load/unload the data.

&nbsp;

Consumption is based on the Size of the Warehouse, Number of Clusters and the amount of time the warehouse is running.

&nbsp;

In Snowflake, the COPY command does not necessarily require specifying a File Format in order to execute.

The COPY command can be used to load data into a table from various file formats such as CSV, JSON, Avro, Parquet, etc.

&nbsp;

Scale up by resizing a warehouse.

Scale out by adding clusters to a multi-cluster warehouse (requires Snowflake Enterprise Edition or higher).

&nbsp;

By default, a newly-created role is not assigned to any user, nor granted to any other role.

&nbsp;

As per docs - Query History page available under Activity Menu on Web UI, holds query data for 14 days.

And you can Query_history view available in Account_Usage schema holds query data for 365 days

&nbsp;

The number of queries that a warehouse can concurrently process is determined by the size and complexity of each query

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
