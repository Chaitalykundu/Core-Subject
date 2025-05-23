1.  Snowflake provides a mechanism for its customers to override its natural clustering algorithms. This method is:

            > Clustering keys

2.  Which of the following are valid Snowflake Virtual Warehouse Scaling Policies? (Choose two.)

            > Economy
            > Standard

3.  True or False: A single database can exist in more than one Snowflake account.

            > False

4.  Which of the following roles is recommended to be used to create and manage users and roles?

            > SECURITYADMIN

5.  True or False: Bulk unloading of data from Snowflake supports the use of a SELECT statement.

            > True

    ```md
    SELECT statement that returns data to be unloaded into files.
    ```

6.  Select the different types of Internal Stages: (Choose three.)

            > Named Stage
            > User Stage,
            > Table Stage

7.  True or False: A customer using SnowSQL / native connectors will be unable to also use the Snowflake Web Interface (UI) unless access to the UI is explicitly granted by support.

            > False

8.  Account-level storage usage can be monitored via:

            > The Snowflake Web Interface (UI) in the Account -> Billing & Usage section

9.  Credit Consumption by the Compute Layer (Virtual Warehouses) is based on: (Choose two.)

            > Warehouse size ,
            > # of clusters for the Warehouse

10. Which statement best describes `clustering`?

            > Clustering represents the way data is grouped together and stored within Snowflake's micro-partitions

11. True or False: The COPY command must specify a File Format in order to execute.

            > False

12. Which of the following commands sets the Virtual Warehouse for a session?

            > USE WAREHOUSE `<<warehouse name>>;`

13. Which of the following objects can be cloned? (Choose four.)

            > A. Tables
            > B. Named File Formats
            > C. Schemas
            > E. Databases

14. Which object allows you to limit the number of credits consumed within a Snowflake account?

            > Resource Monitor

15. Snowflake is designed for which type of workloads? (Choose two.)

            > A. OLAP (Analytics) workloads
            > C. Concurrent workloads

16. What are the three layers that make up Snowflake's architecture? (Choose three.)

            > A. Compute
            > C. Storage
            > D. Cloud Services

17. Why would a customer size a Virtual Warehouse from an X-Small to a Medium?

            > D. To accommodate a more complex workload

18. True or False: Reader Accounts incur no additional Compute costs to the Data Provider since they are simply reading the shared data without making changes.

            > False

19. Which of the following connectors allow Multi-Factor Authentication (MFA) authorization when connecting? (Choose all that apply.)

            > A. JDBC
            > B. SnowSQL
            > C. Snowflake Web Interface (UI)
            > D. ODBC
            > E. Python

20. True or False: Snowflake charges a premium for storing semi-structured data.

            > False

21. Which of the following statements describes a benefit of Snowflake's separation of compute and storage? (Choose all that apply.)

            > B. Storage expands without the requirement to add more compute
            > C. Compute can be scaled up or down without the requirement to add more storage
            > D. Multiple compute clusters can access stored data without contention

22. True or False: It is possible to unload structured data to semi-structured formats such as JSON and Parquet.

            > A. True

23. In which layer of its architecture does Snowflake store its metadata statistics?

            > D. Cloud Services Layer

24. True or False: Data in fail-safe can be deleted by a user or the Snowflake team before it expires.

            > B. False

25. True or False: Snowflake's data warehouse was built from the ground up for the cloud in lieu of using an existing database or a platform, like Hadoop, as a base.

            > A. True

26. Which of the following statements are true of Virtual Warehouses? (Choose all that apply.)

            > A. Customers can change the size of the Warehouse after creation
            > B. A Warehouse can be resized while running
            > C. A Warehouse can be configured to suspend after a period of inactivity
            > D. A Warehouse can be configured to auto-resume when new queries are submitted

            > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* All are right. But A, B are given

            > **Final ANS : ALL**

    > **Final ANS : ALL**

27. The PUT command: (Choose two.)

            > C. Automatically compresses files using Gzip
            > D. Automatically encrypts files

28. Which type of table corresponds to a single Snowflake session?

            > A. Temporary

29. Which interfaces can be used to create and/or manage Virtual Warehouses?

            > D. All of the above (The Snowflake Web Interface (UI), SQL commands, Data integration tools)

30. When a Pipe is recreated using the CREATE OR REPLACE PIPE command:

            > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* A. The Pipe load history is reset to empty

            > Final ANS :A

31. What is the minimum Snowflake edition that customers planning on storing protected information in Snowflake should consider for regulatory compliance?

            > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. Business Critical Edition

            > Final ANS : D

32. Select the three types of tables that exist within Snowflake. (Choose three.)

            > Temporary, Transient, Permanent

33. True or False: Snowpipe via REST API can only reference External Stages as source.

            > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* B. False

            > Final ANS :False

34. True or False: A third-party tool that supports standard JDBC or ODBC but has no Snowflake-specific driver will be unable to connect to Snowflake.

            > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* B. False

            > Final ANS :False

35. True or False: It is possible to load data into Snowflake without creating a named File Format object.

            > A. True

36. True or False: A table in Snowflake can only be queried using the Virtual Warehouse that was used to load the data.

            > B. False

37. Which of the following statements are true of Snowflake data loading? (Choose three.)

            > A. VARIANT null values are not the same as SQL NULL values
            > C. It is recommended to validate the data before loading into the Snowflake target table
            > D. It is recommended to use staging tables to manage MERGE statements

38. Which statements are true of micro-partitions? (Choose two.)

            > A. They are approximately 16MB in size
            > C. They are immutable

39. True or False: Query ID's are unique across all Snowflake deployments and can be used in communication with Snowflake Support to help troubleshoot issues.

            > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* A. True

            > Final ANS : True

40. A deterministic query is run at 8am, takes 5 minutes, and the results are cached. Which of the following statements are true? (Choose two.)

            > B. The same exact query will return the precomputed results if the underlying data hasn't changed and the results were last accessed within previous 24 hour period
            > D. The 24 hour timer on the precomputed results gets renewed every time the exact query is executed

            > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

            > Final ANS : BD

41. Increasing the maximum number of clusters in a Multi-Cluster Warehouse is an example of:

            > C. Scaling out

42. Which statement best describes Snowflake tables?

            > A. Snowflake tables are logical representations of underlying physical data

43. Which item in the Data Warehouse migration process does not apply in Snowflake?

            > C. Migrate Indexes

44. Snowflake provides two mechanisms to reduce data storage costs for short-lived tables. These mechanisms are: (Choose two.)

            > A. Temporary Tables
            > B. Transient Tables

45. What is the maximum compressed row size in Snowflake?

            > B. 16MB

46. Which of the following are main sections of the top navigation of the Snowflake Web Interface (UI)? (Choose three.)

            > A. Databases
            > C. Warehouses
            > D. Worksheets

47. What is the recommended Snowflake data type to store semi-structured data like JSON?

            > D. VARIANT

48. Which of the following statements are true of Snowflake releases: (Choose two.)

            > A. They happen approximately weekly
            > C. During a release, new customer requests/queries/connections transparently move over to the newer version

49. Which of the following are common use cases for zero-copy cloning? (Choose three.)

            > A. Quick provisioning of Dev and Test/QA environments
            > B. Data backups
            > C. Point in time snapshots

50. If a Small Warehouse is made up of 2 servers/cluster, how many servers/cluster make up a Medium Warehouse?

            > A. 4

51. True or False: When a data share is established between a Data Provider and a Data Consumer, the Data Consumer can extend that data share to other Data Consumers.

            > B. False

52. Which is true of Snowflake network policies? A Snowflake network policy: (Choose two.)

            > A. Is available to all Snowflake Editions
            > C. Restricts or enables access to specific IP addresses

53. True or False: Snowflake charges additional fees to Data Providers for each Share they create.

            > B. False

54. Query results are stored in the Result Cache for how long after they are last accessed, assuming no data changes have occurred?

            > D. 24 hours

55. A role is created and owns 2 tables. This role is then dropped. Who will now own the two tables?

            > D. The assumed role that dropped the role

56. Which of the following connectors are available in the Downloads section of the Snowflake Web Interface (UI)? (Choose two.)

            > A. SnowSQL
            > B. ODBC

57. Which of the following DML commands isn't supported by Snowflake?

            > A. UPSERT

58. Which of the following statements is true of zero-copy cloning?

            > D. At the instance/instant a clone is created, all micro-partitions in the original table and the clone are fully shared

59. True or False: When a user creates a role, they are initially assigned ownership of the role and they maintain ownership until it is transferred to another user.

            > B. False

60. The Query History in the Snowflake Web Interface (UI) is kept for approximately:

            > C. 14 days

61. To run a Multi-Cluster Warehouse in auto-scale mode, a user would:

            > D. Set the Minimum Clusters and Maximum Clusters settings to the different values

62. Which of the following terms best describes Snowflake's database architecture?

            > C. Multi-cluster, shared data

63. Which of the following are options when creating a Virtual Warehouse? (Choose two.)

            > C. Auto-resume
            > D. Auto-suspend

64. A Virtual Warehouse's auto-suspend and auto-resume settings apply to:

            > B. The entire Virtual Warehouse

65. Fail-safe is unavailable on which table types? (Choose two.)

            > A. Temporary
            > B. Transient

66. Which of the following objects is not covered by Time Travel?

            > D. Stages

67. True or False: Micro-partition metadata enables some operations to be completed without requiring Compute.

            > A. True

68. Which of the following commands are not blocking operations? (Choose two.)

            > B. INSERT
            > D. COPY

69. Which of the following is true of Snowpipe via REST API? (Choose two.)

            > C. Snowflake automatically manages the compute required to execute the Pipe's COPY INTO commands
            > D. Snowpipe keeps track of which files it has loaded

70. Snowflake recommends, as a minimum, that all users with the following role(s) should be enrolled in Multi-Factor Authentication (MFA):

            > D. ACCOUNTADMIN

71. When can a Virtual Warehouse start running queries?

            > C. When its provisioning is complete

72. True or False: Users are able to see the result sets of queries executed by other users that share their same role.

            > B. False

73. True or False: The user has to specify which cluster a query will run on in a multi-cluster Warehouse.

            > B. False

74. True or False: Pipes can be suspended and resumed.

            > A. True

75. Which of the following languages can be used to implement Snowflake User Defined Functions (UDFs)? (Choose two.)

            > A. Java
            > B. Javascript
            > C. SQL
            > D. Python

            > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* All will be correct. But ans is given A & D

76. When should you consider disabling auto-suspend for a Virtual Warehouse? (Choose two.)

            > B. When managing a steady workload
            > C. When the compute must be available with no delay or lag time

77. Which of the following are valid approaches to loading data into a Snowflake table? (Choose all that apply.)

            > A. Bulk copy from an External Stage
            > B. Continuous load using Snowpipe REST API
            > D. Bulk copy from an Internal Stage

            > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* All will be correct

78. If auto-suspend is enabled for a Virtual Warehouse, the Warehouse is automatically suspended when:

            > D. The Warehouse is inactive for a specified period of time.

79. True or False: Multi-Factor Authentication (MFA) in Snowflake is only supported in conjunction with Single Sign-On (SSO).

            > B. False

80. The number of queries that a Virtual Warehouse can concurrently process is determined by (Choose two.):

            > A. The complexity of each query
            > C. The size of the data required for each query

81. Which of the following statements are true of VALIDATION_MODE in Snowflake? (Choose two.)

            > B. VALIDATION_MODE=RETURN_ALL_ERRORS is a parameter of the COPY command
            > D. The VALIDATION_MODE option will validate data to be loaded by the COPY statement without completing the load and will return possible errors

82. What privileges are required to create a task?

            > D. The role must have access to the target schema and the CREATE TASK privilege on the schema itself.

83. What are the three things customer want most from their enterprise data warehouse solution? (Choose three.)

            > B. Simplicity
            > D. Concurrency
            > E. Performance

84. True or False: Some queries can be answered through the metadata cache and do not require an active Virtual Warehouse.

            > A. True

85. When scaling out by adding clusters to a multi-cluster warehouse, you are primarily scaling for improved:

            > A. Concurrency

86. What is the minimum Snowflake edition that provides data sharing?

            > A. Standard

87. True or False: Each worksheet in the Snowflake Web Interface (UI) can be associated with different roles, databases, schemas, and Virtual Warehouses.

            > A. True

88. True or False: You can query the files in an External Stage directly without having to load the data into a table.

            > A. True

89. The FLATTEN function is used to query which type of data in Snowflake?

            > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. Both of the above

90. True or False: An active warehouse is required to run a COPY INTO statement.

            > A. True

91. True or False: AWS Private Link provides a secure connection from the Customer's on-premise data center to the Snowflake.

            > B. False

92. True or False: Snowflake's Global Services Layer gathers and maintains statistics on all columns in all micro-partitions.

            > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* A. True

93. True or False: It is best practice to define a clustering key on every table.

            > B. False

94. Which of the following statements is true of Snowflake?

            > A. It was built specifically for the cloud

95. What is the minimum Snowflake edition that provides multi-cluster warehouses and up to 90 days of Time Travel?

            > C. Enterprise

96. How many shares can be consumed by a single Data Consumer?

            > D. Unlimited

97. What is the lowest Snowflake edition that offers Time Travel up to 90 days?

            > C. Enterprise Edition

98. Which of the following statements are true about Schemas in Snowflake? (Choose two.)

            > B. A Database may contain one or more Schemas
            > C. A Schema is a logical grouping of Database Objects

99. True or False: You can resize a Virtual Warehouse while queries are running.

            > A. True

100.  What is the most granular object that the Time Travel retention period can be defined on?

            > D. Table

101.  Which of the following statements is true of Snowflake micro-partitioning?

             > C. Micro-partitioning is transparently completed using the ordering that occurs when the data is inserted/loaded

102.  True or False: Snowflake bills for a minimum of five minutes each time a Virtual Warehouse is started.

             > B. False

103.  When scaling up Virtual Warehouses by increasing Virtual Warehouse t-shirt size, you are primarily scaling for improved:

             > B. Performance

104.  As a best practice, clustering keys should only be defined on tables of which minimum size?

             > D. Multi-Terabyte (TB) Range

105.  How a Snowpipe charges calculated?

             > B. Per-second/per-core granularity

106.  True or False: A Snowflake account is charged for data stored in both Internal and External Stages.

             > B. False

107.  True or False: When active, a Pipe requires a dedicated Virtual Warehouse to execute.

             > B. False

108.  True or False: Snowflake supports federated authentication in all editions.

             > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* A. True

109.  True or False: When a new Snowflake object is created, it is automatically owned by the user who created it.

             > B. False

110.  True or False: A Virtual Warehouse consumes Snowflake credits even when inactive.

             > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* B.  False

111.  True or False: During data unloading, only JSON and CSV files can be compressed.

             > B. False

112.  Which of the following are options when creating a Virtual Warehouse? (Choose two.)

             > A. Auto-suspend
             > B. Auto-resume

113.  Which formats are supported for unloading data from Snowflake? (Choose two.)

             > A. Delimited (CSV, TSV, etc.)
             > C. JSON

114.  True or False: Data Providers can share data with only the Data Consumer.

             > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* B. False

115.  The fail-safe retention period is how many days?

             > B. 7 days

116.  True or False: Once created, a micro-partition will never be changed.

             > A. True

117.  What services does Snowflake automatically provide for customers that they may have been responsible for with their on-premise system? (Choose all that apply.)

             > A. Installing and configuring hardware
             > B. Patching software
             > D. Maintaining metadata and statistics

             > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

118.  Which of the following statements would be used to export/unload data from Snowflake?

             > A. COPY INTO @stage

119.  True or False: A 4X-Large Warehouse may, at times, take longer to provision than a X-Small Warehouse.

             > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* A. True

120.  How would you determine the size of the virtual warehouse used for a task?

             > C. If using the stored procedure to execute multiple SQL statements, it's best to test run the stored procedure separately to size the compute resource first
             >  \*\*\*\*\*\*\*\*\* C or D

121.  The Information Schema and Account Usage Share provide storage information for which of the following objects? (Choose three.)

             > B. Tables
             > C. Databases
             > D. Internal Stages

122.  What is the default File Format used in the COPY command if one is not specified?

             > A. CSV

123.  True or False: Reader Accounts are able to extract data from shared data objects for use outside of Snowflake.

             > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* A. True

124.  True or False: You can define multiple columns within a clustering key on a table.

             > A. True

125.  True or False: Snowflake enforces unique, primary key, and foreign key constraints during DML operations.

             > B. False

126.  True or False: Loading data into Snowflake requires that source data files be no larger than 16MB.

             > B. False

127.  True or False: A Virtual Warehouse can be resized while suspended.

             > A. True

128.  True or False: When you create a custom role, it is a best practice to immediately grant that role to ACCOUNTADMIN.

             > B. False

129.  Which of the following accurately represents how a table fits into Snowflake's logical container hierarchy?

             > B. Account -> Database -> Schema -> Table

130.  True or False: All Snowflake table types include fail-safe storage.

             > B. False

131.  What are two ways to create and manage Data Shares in Snowflake? (Choose two.)

             > A. Via the Snowflake Web Interface (UI)
             > C. Via SQL commands

132.  True or False: Fail-safe can be disabled within a Snowflake account.

             > B. False

133.  True or False: It is possible for a user to run a query against the query result cache without requiring an active Warehouse.

             > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* A. True

134.  True or False: When Snowflake is configured to use Single Sign-On (SSO), Snowflake receives the usernames and credentials from the SSO service and loads them into the customer's Snowflake account.

             > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* B. False

135.  Which of the following are best practices for loading data into Snowflake? (Choose three.)

             > A. Aim to produce data files that are between 100 MB and 250 MB in size, compressed.
             > C. Enclose fields that contain delimiter characters in single or double quotes.
             > D. Split large files into a greater number of smaller files to distribute the load among the compute resources in an active warehouse.

136.  Which Snowflake feature is used for both querying and restoring data?

             > B. Time Travel

137.  What do the terms scale up and scale out refer to in Snowflake? (Choose two.)

             > A. Scaling out adds clusters of the same size to a virtual warehouse to handle more concurrent queries.
             > E. Scaling up resizes a virtual warehouse so it can handle more complex workloads.

138.  What is the minimum Snowflake edition that has column-level security enabled?

             > B. Enterprise

139.  What parameter controls if the Virtual Warehouse starts immediately after the CREATE WAREHOUSE statement?

             > A. INITIALLY_SUSPENDED = TRUE/FALSE

140.  When cloning a database, what is cloned with the database? (Choose two.)

             > B. Existing child objects within the database
             > D. Privileges on the schemas within the database

141.  Which of the following describes the Snowflake Cloud Services layer?

             > A. Coordinates activities in the Snowflake account

142.  What is the maximum total Continuous Data Protection (CDP) charges incurred for a temporary table?

             > D. 24 hours

143.  When reviewing a query profile, what is a symptom that a query is too large to fit into the memory?

             > D. The query is spilling to remote storage

144.  What type of query benefits the MOST from search optimization?

             > C. A query that uses equality predicates or predicates that use IN

145.  What transformations are supported in a CREATE PIPE ... AS COPY `¦ FROM (`¦) statement? (Choose two.)

             > C. Columns can be reordered.
             > D. Columns can be omitted.

146.  Which of the following are characteristics of Snowflake virtual warehouses? (Choose two.)

             > C. SnowSQL supports both a configuration file and a command line option for specifying a default warehouse.
             > E. The default virtual warehouse size can be changed at any time.

147.  Which command should be used to load data from a file, located in an external stage, into a table in Snowflake?

             > D. COPY

148.  The Snowflake Cloud Data Platform is described as having which of the following architectures?

             > C. Multi-cluster shared data

149.  Which of the following is a data tokenization integration partner?

             > A. Protegrity

150.  What versions of Snowflake should be used to manage compliance with Personal Identifiable Information (PII) requirements? (Choose two.)

             > B. Virtual Private Snowflake
             > C. Business Critical Edition

             > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* BC or center

151.  What are supported file formats for unloading data from Snowflake? (Choose three.)

             > B. JSON
             > C. Parquet
             > F. CSV

152.  The Snowflake cloud services layer is responsible for which tasks? (Choose two.)

             > B. Authentication and access control
             > C. Metadata management

153.  What is a key feature of Snowflake architecture?

             > C. Snowflake eliminates resource contention with its virtual warehouse implementation.

154.  When publishing a Snowflake Data Marketplace listing into a remote region what should be taken into consideration? (Choose two.)

             > B. The listing is replicated into all selected regions automatically, the data is not.
             > E. For a standard listing the user can wait until the first customer requests the data before replicating it to the target region.

             > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* BE or BC

155.  When loading data into Snowflake via Snowpipe what is the compressed file size recommendation?

             > B. 100-250 MB

156.  Which Snowflake feature allows a user to substitute a randomly generated identifier for sensitive data, in order to prevent unauthorized users access to the data, before loading it into Snowflake?

             > A. External Tokenization

157.  Which of the following are examples of operations that require a Virtual Warehouse to complete, assuming no queries have been executed previously? (Choose three.)

             > B. COPY
             > C. SUM(<< column value >>)
             > D. UPDATE

158.  What is the SNOWFLAKE.ACCOUNT_USAGE view that contains information about which objects were read by queries within the last 365 days (1 year)?

             > C. ACCESS_HISTORY

159.  Which feature is only available in the Enterprise or higher editions of Snowflake?

             > A. Column-level security

160.  Will data cached in a warehouse be lost when the warehouse is resized?

             > A. Possibly, if the warehouse is resized to a smaller size and the cache no longer fits.

             > \*\*\*\*\*\*\*\* A or C

161.  Which semi-structured file formats are supported when unloading data from a table? (Choose two.)

             > D. Parquet
             > E. JSON

162.  A running virtual warehouse is suspended. What is the MINIMUM amount of time that the warehouse will incur charges for when it is restarted?

             > B. 60 seconds

163.  What are the responsibilities of Snowflake's Cloud Service layer? (Choose three.)

             > A. Authentication
             > B. Resource management
             > D. Query parsing and optimization

             > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* ABD or ACD

164.  How long is the Fail-safe period for temporary and transient tables?

             > A. There is no Fail-safe period for these tables.

165.  Which command should be used to download files from a Snowflake stage to a local folder on a client's machine?

             > B. GET

166.  How does Snowflake Fail-safe protect data in a permanent table?

             > C. Fail-safe makes data available for 7 days, recoverable only by Snowflake Support.

167.  A virtual warehouse is created using the following command:

- Create warehouse my_WH with -
- warehouse_size = MEDIUM
- min_cluster_count = 1
- max_cluster_count = 1
- auto_suspend = 60
- auto_resume = true;

The image below is a graphical representation of the warehouse utilization across two days.

<img src="https://www.examtopics.com/assets/media/exam-media/04222/0006500001.jpg">

What action should be taken to address this situation?

            > C. Configure the warehouse to a multi-cluster warehouse.

168.  Which minimum Snowflake edition allows for a dedicated metadata store?

             > D. Virtual Private Snowflake

169.  Network policies can be set at which Snowflake levels? (Choose two.)

             > C. User
             > E. Account

170.  What are the correct parameters for time travel and fail-safe in the Snowflake Enterprise Edition?

             > D. Default Time Travel Retention is set to 1 day. Maximum Time Travel Retention is 90 days. Fail Safe retention time is 7 days.

171.  Which of the following objects are contained within a schema? (Choose two.)

             > B. Stream
             > D. External table

172.  Which of the following statements describe features of Snowflake data caching? (Choose two.)

             > B. When the data cache is full, the least-recently used data will be cleared to make room.
             > E. The RESULT_SCAN table function can access and filter the contents of the query result cache.

             > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* BE or CE

173.  A table needs to be loaded. The input data is in JSON format and is a concatenation of multiple JSON documents. The file size is 3 GB. A warehouse size S is being used. The following COPY INTO command was executed:
      COPY INTO SAMPLE FROM @~/SAMPLE.JSON (TYPE=JSON)
      The load failed with this error:
      Max LOB size (16777216) exceeded, actual size of parsed column is 17894470. How can this issue be resolved?

             > D. Set STRIP_OUTER_ARRAY=TRUE in the COPY INTO command.

174.  What is a feature of a stored procedure in Snowflake?

             > D. They can be created to run with a caller's rights or an owner's rights.

175.  Which columns are part of the result set of the Snowflake LATERAL FLATTEN command? (Choose two.)

             > B. PATH
             > D. INDEX

176.  What is the minimum Snowflake edition required to create a materialized view?

             > B. Enterprise Edition

177.  Which Snowflake function will interpret an input string as a JSON document, and produce a VARIANT value?

             > A. parse_json()

178.  How are serverless features billed?

             > A. Per second multiplied by an automatic sizing for the job

179.  Which Snowflake architectural layer is responsible for a query execution plan?

             > C. Cloud services

             > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C or A

180.  When unloading to a stage, which of the following is a recommended practice or approach?

             > D. Define an individual file format.

181.  Which SQL commands, when committed, will consume a stream and advance the stream offset? (Choose two.)

             > A. UPDATE TABLE FROM STREAM
             > C. INSERT INTO TABLE SELECT FROM STREAM

182.  Which methods can be used to delete staged files from a Snowflake stage? (Choose two.)


    > C. Specify the PURGE copy option in the COPY INTO command.

    > D. Use the REMOVE command after the load completes.

183. On which of the following cloud platforms can a Snowflake account be hosted? (Choose three.)


    > A. Amazon Web Services

    > D. Microsoft Azure Cloud

    > E. Google Cloud Platform

184. What Snowflake role must be granted for a user to create and manage accounts?


    > B. ORGADMIN

    >  \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* B or C

185. Assume there is a table consisting of five micro-partitions with values ranging from A to Z. Which diagram indicates a well-clustered table?


    > A <img src="https://img.examtopics.com/snowpro-core/image1.png">

186. What feature can be used to reorganize a very large table on one or more columns?


    > B. Clustering keys

187. What is an advantage of using an explain plan instead of the query profiler to evaluate the performance of a query?


    > B. An explain plan can be used to conduct performance analysis without executing a query.

188. Which data types are supported by Snowflake when using semi-structured data? (Choose two.)


    > A. VARIANT

    > D. ARRAY

189. Why does Snowflake recommend file sizes of 100-250 MB compressed when loading data?


    > D. Allows optimization of parallel operations

190. Which of the following features are available with the Snowflake Enterprise edition? (Choose two.)


    > D. Extended time travel

    > E. Native support for geospatial data

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

191. What is the default file size when unloading data from Snowflake using the COPY command?


    > C. 16 MB

192. What features that are part of the Continuous Data Protection (CDP) feature set in Snowflake do not require additional configuration? (Choose two.)


    > C. Data encryption

    > D. Time Travel

193. Which Snowflake layer is always leveraged when accessing a query from the result cache?


    > D. Cloud Services

194. Which connectors are available in the downloads section of the Snowflake web interface (UI)? (Choose two.)


    > A. SnowSQL

    > C. ODBC

195. A Snowflake Administrator needs to ensure that sensitive corporate data in Snowflake tables is not visible to end users, but is partially visible to functional managers. How can this requirement be met?


    > B. Use dynamic data masking.

196. Users are responsible for data storage costs until what occurs?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* B. Data expires from Fail-safe

197. A user has an application that writes a new file to a cloud storage location every 5 minutes.What would be the MOST efficient way to get the files into Snowflake?


    > D. Set up cloud provider notifications on the file location and use Snowpipe with auto-ingest.

198. What affects whether the query results cache can be used?


    > C. If the referenced data in the table has changed

199. Which of the following is an example of an operation that can be completed without requiring compute, assuming no queries have been executed previously?


    > C. SELECT MIN(ORDER_AMT) FROM SALES;

200. How many days is load history for Snowpipe retained?


    > C. 14 days

201. What Snowflake features allow virtual warehouses to handle high concurrency workloads? (Choose two.)


    > B. The use of warehouse auto scaling

    > D. Use of multi-clustered warehouses

202. Which COPY INTO command outputs the data into one file?


    > A. SINGLE=TRUE

203. In which scenarios would a user have to pay Cloud Services costs? (Choose two.)


    > A. Compute Credits = 50 Credits Cloud Services = 10

    > E. Compute Credits = 200 Credits Cloud Services = 26

204. A user created a new worksheet within the Snowsight UI and wants to share this with teammates.How can this worksheet be shared?


    > C. Share the worksheet with teammates within Snowsight.

205. How can a row access policy be applied to a table or a view? (Choose two.)


    > B. Within the create table or create view DDL

    > E. Using the command ALTER [object] ADD ROW ACCESS POLICY [policy];

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

206. Which command can be used to load data files into a Snowflake stage?


    > C. PUT

207. What types of data listings are available in the Snowflake Data Marketplace? (Choose two.)


    >D. Standard

    >E. Personalized

208. What is the maximum Time Travel retention period for a temporary Snowflake table?


    > B. 1 day

209. When should a multi-cluster warehouse be used in auto-scaling mode?


    > D. When a large number of concurrent queries are run on the same warehouse

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D or A

210. What happens when a cloned table is replicated to a secondary database? (Choose two.)


    > C. The physical data is replicated.

    > D. Additional costs for storage are charged to a secondary account.

    > \*\*\*\*\*\*\* CD or CE

211. Snowflake supports the use of external stages with which cloud platforms? (Choose three.)


    > A. Amazon Web Services

    > D. Microsoft Azure Cloud

    > E. Google Cloud Platform

212. What is a limitation of a Materialized View?


    > D. A Materialized View cannot be defined with a JOIN

213. In the Snowflake access control model, which entity owns an object by default?


    > D. The role used to create the object

214. What is the minimum Snowflake edition required to use Dynamic Data Masking?


    > B. Enterprise

215. Which services does the Snowflake Cloud Services layer manage? (Choose two.)


    > C. Authentication

    > E. Metadata

216. A company needs to allow some users to see Personally Identifiable Information (PII) while limiting other users from seeing the full value of the PII. Which Snowflake feature will support this?


    > B. Data masking policies

217. A user has unloaded data from a Snowflake table to an external stage. Which command can be used to verify if data has been uploaded to the external stage named my_stage?


    > B. list @my_stage

218. Which tasks are performed in the Snowflake Cloud Services layer? (Choose two.)


    > A. Management of metadata

    > E. Parsing and optimizing queries

219. What is true about sharing data in Snowflake? (Choose two.)


    > C. A Snowflake account can both provide and consume shared data.

    > E. The Data Consumer pays only for compute resources to query the shared data.

220. The following JSON is stored in a VARIANT column called src of the CAR_SALES table:
     <img src="https://img.examtopics.com/snowpro-core/image5.png">
     A user needs to extract the dealership information from the JSON. How can this be accomplished?


    > A. select src:dealership from car_sales;

221. Which of the following significantly improves the performance of selective point lookup queries on a table?


    > D. Search Optimization Service

222. Which of the following accurately describes shares?


    > A. Tables, secure views, and secure UDFs can be shared

223. What are best practice recommendations for using the ACCOUNTADMIN system-defined role in Snowflake? (Choose two.)


    > A. Ensure all ACCOUNTADMIN roles use Multi-factor Authentication (MFA).

    > D. Assign the ACCOUNTADMIN role to at least two users, but as few as possible.

224. In the query profiler view for a query, which components represent areas that can be used to help optimize query performance? (Choose two.)


    > A. Bytes scanned

    > C. Number of partitions scanned

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* AC or CD

225. What is the minimum Snowflake edition required for row level security?


    > B. Enterprise

226. The is the minimum Fail-safe retention time period for transient tables?


    > D. 0 days

227. What is a machine learning and data science partner within the Snowflake Partner Ecosystem?


    > D. Data Robot

228. Which statements are correct concerning the leveraging of third-party data from the Snowflake Data Marketplace? (Choose two.)


    > A. Data is live, ready-to-query, and can be personalized.

    > D. Data is available without copying or moving.

229. What impacts the credit consumption of maintaining a materialized view? (Choose two.)


    > C. How often the base table changes

    > D. Whether the materialized view has a cluster key defined

230. What COPY INTO SQL command should be used to unload data into multiple files?


    > D. SINGLE=FALSE

231. When cloning a database containing stored procedures and regular views, that have fully qualified table references, which of the following will occur?


    > A. The cloned views and the stored procedures will reference the cloned tables in the cloned database.

232. When loading data into Snowflake, how should the data be organized?


    > A. Into single files with 100-250 MB of compressed data per file

233. Which of the following objects can be directly restored using the UNDROP command? (Choose two.)


    > A. Schema

    > D. Table

234. Which Snowflake SQL statement would be used to determine which users and roles have access to a role called MY_ROLE?


    > A. SHOW GRANTS OF ROLE MY_ROLE

235. What is the MINIMUM edition of Snowflake that is required to use a SCIM security integration?


    > B. Standard Edition

236. A user created a transient table and made several changes to it over the course of several days. Three days after the table was created, the user would like to go back to the first version of the table. How can this be accomplished?


    > B. The transient table version cannot be retrieved after 24 hours.

237. When reviewing the load for a warehouse using the load monitoring chart, the chart indicates that a high volume of queries is always queuing in the warehouse. According to recommended best practice, what should be done to reduce the queue volume? (Choose two.)


    > A. Use multi-clustered warehousing to scale out warehouse capacity.

    > D. Migrate some queries to a new warehouse to reduce load.

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* AD or BD

238. Which of the following features, associated with Continuous Data Protection (CDP), require additional Snowflake-provided data storage? (Choose two.)


    > B. Time Travel

    > C. Fail-safe

239. Where can a user find and review the failed logins of a specific user for the past 30 days?


    > B. The LOGIN_HISTORY view in ACCOUNT_USAGE

240. What is the purpose of an External Function?


    > A. To call code that executes outside of Snowflake

241. Which of the following statements apply to Snowflake in terms of security? (Choose two.)


    > A. Snowflake leverages a Role-Based Access Control (RBAC) model.

    > C. All data in Snowflake is encrypted.

242. A single user of a virtual warehouse has set the warehouse to auto-resume and auto-suspend after 10 minutes. The warehouse is currently suspended and the user performs the following actions:

1. Runs a query that takes 3 minutes to complete
1. Leaves for 15 minutes
1. Returns and runs a query that takes 10 seconds to complete
1. Manually suspends the warehouse as soon as the last query was completed

When the user returns, how much billable compute time will have been consumed?

    > C. 14 minutes

243. What can be used to view warehouse usage over time? (Choose two.)


    > D. The WAREHOUSE_METERING_HISTORY view

    > E. The billing and usage tab in the Snowflake web UI

244. What actions will prevent leveraging of the ResultSet cache? (Choose two.)


    > A. Removing a column from the query SELECT list

    > C. Clustering of the data used by the query

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* AC or AE

245. Which statement is true about running tasks in Snowflake?


    > B. A task allows a user to execute a single SQL statement/command using a predefined schedule.

246. Which data types does Snowflake support when querying semi-structured data? (Choose two.)


    > A. VARIANT

    > D. ARRAY

247. In an auto-scaling multi-cluster virtual warehouse with the setting SCALING_POLICY = ECONOMY enabled, when is another cluster started?


    > B. When the system has enough load for 6 minutes

248. What is the following SQL command used for?Select \* from table(validate(t1, job_id => '\_last'));


    > D. To return errors from the last executed COPY command into table t1 in the current session

249. A sales table FCT_SALES has 100 million records.
     The following query was executed:
     SELECT COUNT (1) FROM FCT_SALES;
     How did Snowflake fulfill this query?


    > D. Query against the metadata cache

250. What happens when a virtual warehouse is resized?


    > B. When reducing the size of a warehouse the compute resources are removed only when they are no longer being used to execute any current statements.

251. What tasks can be completed using the COPY command? (Choose two.)


    > C. Columns can be reordered.

    > D. Columns can be omitted.

252. Which Snowflake layer can be configured?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. Query Processing

253. Query compilation occurs in which architecture layer of the Snowflake Cloud Data Platform?


    > D. Cloud services layer

254. If a size Small virtual warehouse is made up of two servers, how many servers make up a Large warehouse?


    > B. 8

255. A clustering key was defined on a table, but it is no longer needed. How can the key be removed?


    > C. ALTER TABLE [TABLE NAME] DROP CLUSTERING KEY

256. What is a core benefit of clustering?


    > B. To increase scan efficiency in queries by improving pruning

257. Which statement is true about Multi-Factor Authentication (MFA) in Snowflake?


    > D. MFA is an integrated Snowflake feature.

258. What data type should be used to store JSON data natively in Snowflake?


    > D. VARIANT

259. What should be considered when deciding to use a Secure View? (Choose two.)


    > A. No details of the query execution plan will be available in the query profiler.

    > C. Secure views do not take advantage of the same internal optimizations as standard views.

260. The information schema provides storage information for which of the following objects? (Choose two.)


    > B. Databases

    > C. Internal stages

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* BC or BE

261. What is a responsibility of Snowflake’s virtual warehouses?


    > C. Query execution

262. Which data type is supported by Snowflake data classification?


    > B. Float

263. When unloading data to an external stage, which compression format can be used for Parquet files with the COPY INTO command?


    > C. LZO

264. Which SQL command can be used to verify the privileges that are granted to a role?


    > C. SHOW GRANTS TO ROLE

265. Which Query Profile result indicates that a warehouse is sized too small?


    > B. Bytes are spilling to external storage.

266. What is the default Time Travel retention period?


    > A. 1 day

267. Which of the following are best practice recommendations that should be considered when loading data into Snowflake? (Choose two.)


    > C. Load files that are approximately 100-250 MB (or larger).

    > D. Avoid using embedded characters such as commas for numeric data types.

268. Which schema has the RESOURCE_MONITORS view?


    > B. READER_ACCOUNT_USAGE

269. What is the purpose of enabling Federated Authentication on a Snowflake account?


    > D. Allows users to connect using secure single sign-on (SSO) through an external identity provider

270. Which Snowflake partner category is represented at the top of this diagram (labeled 1)? <img src="https://img.examtopics.com/snowpro-core/image6.png">


    > D. Data Integration

271. Which object types are protected by Fail-safe? (Choose two.)


    > A. Permanent Tables

    > D. Materialized Views

272. Snowflake's approach to the management of system access combines which of the following models? (Choose two.)


    > B. Role-Based Access Control (RBAC)

    > E. Discretionary Access Control (DAC)

273. According to Snowflake best practice recommendations, which role should be used to create databases?


    > B. SYSADMIN

274. To add or remove search optimization for a table, a user must have which of the following privileges or roles? (Choose two.)


    > B. The OWNERSHIP privilege on the table

    > D. The ADD SEARCH OPTIMIZATION privilege on the schema that contains the table

275. While using a COPY command with a Validation_mode parameter, which of the following statements will return an error?


    > D. Statements that transform data during a load

276. When is the result set cache no longer available? (Choose two.)


    > C. When the underlying data has changed

    > E. When it has been 24 hours since the last query

277. What is the recommended file sizing for data loading using Snowpipe?


    > A. A compressed file size greater than 100 MB, and up to 250 MB

278. Which statements are true concerning Snowflake’s underlying cloud infrastructure? (Choose three.)


    > D. Snowflake uses the core compute and storage services of each cloud provider for its own compute and storage.

    > E. All three layers of Snowflake’s architecture (storage, compute, and cloud services) are deployed and managed entirely on a selected cloud platform.

    > F. Snowflake data and services are deployed in at least three availability zones within a cloud provider’s region.

279. A user unloaded a Snowflake table called mytable to an internal stage called mystage. Which command can be used to view the list of files that has been uploaded to the stage?


    > D. list @mystage;

280. What is a best practice after creating a custom role?


    > B. Assign the custom role to the SYSADMIN role.

281. Which is the MINIMUM required Snowflake edition that a user must have if they want to use AWS/Azure Privatelink or Google Cloud Private Service Connect?


    > D. Business Critical

282. Which of the following query profiler variables will indicate that a virtual warehouse is not sized correctly for the query being executed?


    > D. Remote spillage

283. Which of the following Snowflake capabilities are available in all Snowflake editions? (Choose two.)


    > B. Automatic encryption of all data

    > D. Object-level access control

284. A PUT command can be used to stage local files from which Snowflake interface?


    > A. SnowSQL

285. Which of the following indicates that it may be appropriate to use a clustering key for a table? (Choose two.)


    > D. Queries on the table are running slower than expected.

    > E. The clustering depth for the table is large.

286. Which cache type is used to cache data output from SQL queries?


    > B. Result cache

287. Which of the following describes how clustering keys work in Snowflake?


    > B. Clustering keys sort the designated columns over time, without blocking DML operations.

288. Which of the following operations require the use of a running virtual warehouse? (Choose two.)


    > C. Executing a stored procedure

    > E. Querying data from a materialized view

289. What is used to limit the credit usage of a virtual warehouse within a Snowflake account?


    > B. Resource monitor

290. What are the benefits of the replication feature in Snowflake? (Choose two.)


    > A. Disaster recovery

    > D. Database failover and failback

291. Which of the following roles are recommended to create and manage users and roles? (Choose two.)


    > B. SECURITYADMIN

    > E. USERADMIN

292. When can a newly configured virtual warehouse start running SQL queries?


    > C. When the warehouse provisioning is completed

293. What actions will prevent leveraging of the ResultSet cache?


    > A. Removing a column from the query SELECT list

294. Which of the following are benefits of micro-partitioning? (Choose two.)


    > B. Micro-partitions are immutable objects that support the use of Time Travel.

    > C. Micro-partitions can reduce the amount of I/O from object storage to virtual warehouses.

296. If all virtual warehouse resources are maximized while processing a query workload, what will happen to new queries that are submitted to the warehouse?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. New queries will be queued and executed when capacity is available.

297. Masking policies can be applied to which of the following Snowflake objects? (Choose two.)


    > A. A materialized view

    > C. A table

298. What actions are supported by Snowflake resource monitors? (Choose two.)


    > B. Notify

    > C. Notify and suspend

299. A user executes the following SQL query:

create table SALES_BKP like SALES;

What are the cost implications for processing this query?

    > C. No costs will be incurred as the query will use metadata.

300. What is the maximum length of time travel available in the Snowflake Standard Edition?


    > A. 1 Day

301. What happens when an external or an internal stage is dropped? (Choose two.)


    > A. When dropping an external stage, the files are not removed and only the stage is dropped.

    > D. When dropping an internal stage, the files are deleted with the stage and the files are not recoverable

302. A user has 10 files in a stage containing new customer data. The ingest operation completes with no errors, using the following command:

COPY INTO my_table FROM @my_stage;

The next day the user adds 10 files to the stage so that now the stage contains a mixture of new customer data and updates to the previous data. The user did not remove the 10 original files.

If the user runs the same COPY INTO command what will happen?

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. All data from only the newly-added files will be appended to the table.

303. Which parameter can be used to instruct a COPY command to verify data files instead of loading them into a specified table?


    > D. VALIDATION_MODE

304. Which of the following SQL statements will list the version of the drivers currently being used?


    > C. Execute SELECT CURRENT_CLIENT(); from an application

305. Which Snowflake technique can be used to improve the performance of a query?


    > A. Clustering

306. What happens to the shared objects for users in a consumer account from a share, once a database has been created in that account?


    > C. The shared objects become accessible.

307. Using variables in Snowflake is denoted by using which SQL character?


    > C. $

308. Which commands should be used to grant the privilege allowing a role to select data from all current tables and any tables that will be created later in a schema? (Choose two.)


    > C. grant SELECT on all tables in schema DB1.SCHEMA to role MYROLE;

    > D. grant SELECT on future tables in schema DB1.SCHEMA to role MYROLE;

309. How can a user change which columns are referenced in a view?


    > C. Recreate the view with the required changes

310. Which statement describes pruning?


    > A. The filtering or disregarding of micro-partitions that are not needed to return a query.

311. Which SQL command can be used to see the CREATE definition of a masking policy?


    > C. GET_DDL

312. Which of the following is the Snowflake Account_Usage.Metering_History view used for?


    > A. Gathering the hourly credit usage for an account

313. Query parsing and compilation occurs in which architecture layer of the Snowflake Cloud Data Platform?


    > A. Cloud services layer

314. Which of the following Snowflake objects can be shared using a secure share? (Choose two.)


    > D. Tables

    > E. Secure User Defined Functions (UDFs)

315. What happens to the underlying table data when a CLUSTER BY clause is added to a Snowflake table?


    > D. Data may be colocated by the cluster key within the micro-partitions to improve pruning performance

316. Which of the following conditions must be met in order to return results from the results cache? (Choose two.)


    > A. The user has the appropriate privileges on the objects associated with the query.

    > E. The query has been run within 24 hours of the previously-run query.

317. Which statement about billing applies to Snowflake credits?


    > D. Credits are consumed based on the warehouse size and the time the warehouse is running.

318. A user needs to create a materialized view in the schema MYDB.MYSCHEMA. Which statements will provide this access?


    > A. GRANT ROLE MYROLE TO USER USER1; CREATE MATERIALIZED VIEW ON SCHEMA MYDB.MYSCHEMA TO ROLE MYROLE;

319. What is the purpose of multi-cluster virtual warehouses?


    > C. To eliminate or reduce queuing of concurrent queries

320. Which of the following is a valid source for an external stage when the Snowflake account is located on Microsoft Azure?


    >  \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. A Google Cloud storage bucket

321. Which database objects can be shared with the Snowflake secure data sharing feature? (Choose two.)


    > B. External tables

    > C. Secure User-Defined Functions (UDFs)

322. Which statements reflect key functionalities of a Snowflake Data Exchange? (Choose two.)


    > B. A Data Exchange allows groups of accounts to share data privately among the accounts.

    > E. The sharing of data in a Data Exchange is bidirectional. An account can be a provider for some datasets and a consumer for others.

323. A Snowflake user executed a query and received the results. Another user executed the same query 4 hours later. The data had not changed. What will occur?


    > A. No virtual warehouse will be used, data will be read from the result cache.

324. Which feature allows a user the ability to control the organization of data in a micro-partition?


    > C. Automatic Clustering

325. Which privilege must be granted to a share to allow secure views the ability to reference data in multiple databases?


    > D. REFERENCE_USAGE on databases

326. In which use case does Snowflake apply egress charges?


    > C. Database replication

327. Which of the following compute resources or features are managed by Snowflake? (Choose two.)


    > C. Snowpipe

    > D. AUTOMATIC_CLUSTERING

328. A materialized view should be created when which of the following occurs? (Choose two.)


    > B. The query consumes many compute resources every time it runs.

    > E. The results of the query do not change often and are used frequently.

329. What privilege should a user be granted to change permissions for new objects in a managed access schema?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* A. Grant the OWNERSHIP privilege on the schema

330. What happens when a Data Provider revokes privileges to a share on an object in their source database?


    > A. The object immediately becomes unavailable for all Data Consumers

331. Which command can be used to load data into an internal stage?


    > D. PUT

332. What is the MINIMUM Snowflake edition required to use the periodic rekeying of micro-partitions?


    > A. Enterprise

333.  Which stage type can be altered and dropped?


    > B. External stage

334. Which Snowflake object enables loading data from files as soon as they are available in a cloud storage location?


    > A. Pipe

335. A user is loading JSON documents composed of a huge array containing multiple records into Snowflake. The user enables the STRIP_OUTER_ARRAY file format option. What does the STRIP_OUTER_ARRAY file format do?


    > B. It removes the outer array structure and loads the records into separate table rows.

336. Which of the following describes how multiple Snowflake accounts in a single organization relate to various cloud providers?


    > A. Each Snowflake account can be hosted in a different cloud vendor and region

337. If a Snowflake user decides a table should be clustered, what should be used as the cluster key?


    > D. The columns most actively used in the select filters.

338. What are value types that a VARIANT column can store? (Choose two.)


    > B. OBJECT

    > D. ARRAY

339. A company needs to read multiple terabytes of data for an initial load as part of a Snowflake migration. The company can control the number and size of CSV extract files. How does Snowflake recommend maximizing the load performance?


    > C. Produce a larger number of smaller files and process the ingestion with size Small virtual warehouses.

340. For non-materialized views, what column in Information Schema and Account Usage identifies whether a view is secure or not?


    > B. IS_SECURE

341. The bulk data load history that is available upon completion of the COPY statement is stored where and for how long?


    > C. In the metadata of the target table for 64 days

342. User INQUISITIVE_PERSON has been granted the role DATA_SCIENCE. The role DATA_SCIENCE has privileges OWNERSHIP on the schema MARKETING of the database ANALYTICS_DW. Which command will show all privileges granted to that schema?


    > B. SHOW GRANTS ON SCHEMA ANALYTICS_DW.MARKETING

343. Which set of steps is used to import spreadsheet data into a ServiceNow table?


    > B. Load Data, Create Transform Map, Run Transform

344. Which of the following objects can be shared through secure data sharing?


    > D. External table

345. Which formats does Snowflake store unstructured data in? (Choose two.)


    > B. Array

    > D. Object

346. A user is preparing to load data from an external stage. Which practice will provide the MOST efficient loading performance?


    > A. Organize files into logical paths

347. What effect does WAIT_FOR_COMPLETION = TRUE have when running an ALTER WAREHOUSE command and changing the warehouse size?


    > D. It does not return from the command until the warehouse has finished changing its size.

348. Which of the following can be used when unloading data from Snowflake? (Choose two.)


    > C. The OBJECT_CONSTRUCT function can be used to convert relational data to semi-structured data. Most Voted

    > D. By using the SINGLE = TRUE parameter, a single file up to 5 GB in size can be exported to the storage layer.

349. What data is stored in the Snowflake storage layer? (Choose two.)


    > B. Micro-partitions

    > C. Query history

350. A data provider wants to share data with a consumer who does not have a Snowflake account. The provider creates a reader account for the consumer following these steps:

1. Created a user called "CONSUMER"
1. Created a database to hold the share and an extra-small warehouse to query the data
1. Granted the role PUBLIC the following privileges: Usage on the warehouse, database, and schema, and SELECT on all the objects in the share

Based on this configuration what is true of the reader account?

    > B. The reader account compute will be billed to the provider account.

351. Which of the following activities consume virtual warehouse credits in the Snowflake environment? (Choose two.)


    > D. Running a custom query

    > E. Running COPY commands

352. When loading data into Snowflake, the COPY command supports which of the following?


    > C. Column reordering

353. What is cached during a query on a virtual warehouse?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*  B. Any columns accessed during the query

354. What is the default character set used when loading CSV files into Snowflake?


    > A. UTF-8

355. Which of the following describes external functions in Snowflake?


    > A. They are a type of User-defined Function (UDF).

356. Which of the following are valid methods for authenticating users for access into Snowflake? (Choose three.)


    > B. Federated authentication

    > D. Key-pair authentication

    > E. OAuth

357. A user has a standard multi-cluster warehouse auto-scaling policy in place. Which condition will trigger a cluster to shut-down?


    > D. When after 2-3 consecutive checks the system determines that the load on the least-loaded cluster could be redistributed.

358. What is the minimum Snowflake edition needed for database failover and fail-back between Snowflake accounts for business continuity and disaster recovery?


    > C. Business Critical

359. How would a user execute a series of SQL statements using a task?


    > C. Use a stored procedure executing multiple SQL statements and invoke the stored procedure from the task. CREATE TASK mytask .... AS call stored_proc_multiple_statements_inside();

360. How many resource monitors can be assigned at the account level?


    > A. 1

361. Data storage for individual tables can be monitored using which commands and/or objects? (Choose two.)


    > B. SHOW TABLES;

    > E. Information Schema -> TABLE_STORAGE_METRICS

362. How would a user run a multi-cluster warehouse in maximized mode?


    > C. Set the minimum Clusters and maximum Clusters settings to the same value.

363. What internal stages are available in Snowflake? (Choose three.)


    > B. Named stage

    > C. User stage

    > E. Table stage

364. Which stages are used with the Snowflake PUT command to upload files from a local file system? (Choose three.)


    > B. User Stage

    > D. Table Stage

    > F. Internal Named Stage

365. Which data type can store more than one type of data structure?


    > D. VARIANT

366. User-level network policies can be created by which of the following roles? (Choose two.)


    > B. ACCOUNTADMIN

    > D. SECURITYADNIN

367. What SQL command would be used to view all roles that were granted to USER1?


    > A. show grants to user USER1;

368. Which ACCOUNT_USAGE views are used to evaluate the details of dynamic data masking? (Choose two.)


    > B. POLICY_REFERENCES

    > F. MASKING_POLICIES

369. Which of the following are considerations when using a directory table when working with unstructured data? (Choose two.)


    > B. Directory tables store data file metadata.

    > D. Directory tables do not have their own grantable privileges.

370. The first user assigned to a new account, ACCOUNTADMIN, should create at least one additional user with which administrative privilege?


    > A. USERADMIN

371. Which statement describes how Snowflake supports reader accounts?


    > D. The SHOW MANAGED ACCOUNTS command will view all the reader accounts that have been created for an account

373. Which Snowflake objects can be shared with other Snowflake accounts? (Choose three.)


    > C. Secure Views

    > E. Tables

    > F. Secure User-Defined Functions (UDFs)

374. Which Snowflake feature will allow small volumes of data to continuously load into Snowflake and will incrementally make the data available for analysis?


    > B. CREATE PIPE

375. Which Snowflake partner specializes in data catalog solutions?


    > A. Alation

376. Which of the following can be executed/called with Snowpipe?


    > C. A single COPY_INTO statement

377. Which snowflake objects will incur both storage and cloud compute charges? (Choose two.)


    > A. Materialized view

    > E. Clustered table

378. What file formats does Snowflake support for loading semi-structured data? (Choose three.)


    > B. JSON

    > D. Avro

    > E. Parquet

379. Which of the following statements about data sharing are true? (Choose two.)


    > C. Reader Accounts are created by Data Providers.

    > D. Shared databases are read-only.

380. Credit charges for Snowflake virtual warehouses are calculated based on which of the following considerations? (Choose two.)


    > C. The size of the virtual warehouse

    > D. The length of time the warehouse is running

381. Which of the following are handled by the cloud services layer of the Snowflake architecture? (Choose two.)


    > D. Security

    > E. Authentication and access control

382. What is a responsibility of Snowflake’s virtual warehouses?


    > C. Query execution

383. What features does Snowflake Time Travel enable?


    > B. Restoring data-related objects that have been deleted within the past 90 days

384. Which of the following statements describes a schema in Snowflake?


    > A. A logical grouping of objects that belongs to a single database

385. What is the recommended compressed file size range for continuous data loads using Snowpipe?


    > D. 100-250 MB

387. A company strongly encourages all Snowflake users to self-enroll in Snowflake's default Multi-Factor Authentication (MFA) service to provide increased login security for users connecting to Snowflake. Which application will the Snowflake users need to install on their devices in order to connect with MFA?


    > B. Duo Mobile

388. Which URL type allows users to access unstructured data without authenticating into Snowflake or passing an authorization token?


    > A. Pre-signed URL

389. Where would a Snowflake user find information about query activity from 90 days ago?


    > A. account_usage.query_history view

390. A marketing co-worker has requested the ability to change a warehouse size on their medium virtual warehouse called MKTG_WH. Which of the following statements will accommodate this request?


    > B. GRANT MODIFY ON WAREHOUSE MKTG_WH TO ROLE MARKETING;

391. Which of the following commands cannot be used within a reader account?


    > A. CREATE SHARE

392. Which TABLE function helps to convert semi-structured data to a relational representation?


    > C. FLATTEN

393. Which query profile statistics help determine if efficient pruning is occurring? (Choose two.)


    > C. Partitions total

    > E. Partitions scanned

394. What are the default Time Travel and Fail-safe retention periods for transient tables?


    > C. Time Travel - 1 day, Failsafe - 0 days

395. Which command is used to unload data from a Snowflake table into a file in a stage?


    > A. COPY INTO

396. What are advantages clones have over tables created with CREATE TABLE AS SELECT statement? (Choose two.)


    > C. The clone is created almost instantly.

    > E. The clone saves space by not duplicating storage.

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

397. How often are the Account and Table master keys automatically rotated by Snowflake?


    > A. 30 Days

398. Which privilege is required for a role to be able to resume a suspended warehouse if auto-resume is not enabled?


    > B. OPERATE

399. Which statement MOST accurately describes clustering in Snowflake?


    > B. Clustering is the way data is grouped together and stored within Snowflake micro-partitions.

400. Which of the following practices are recommended when creating a user in Snowflake? (Choose two.)


    > B. Force an immediate password change.

    > C. Set a default role for the user

401. Network policies can be applied to which of the following Snowflake objects? (Choose two.)


    > D. Users

    > E. Accounts

402. Where is Snowflake metadata stored?


    > C. In the cloud services layer

403. What columns are returned when performing a FLATTEN command on semi-structured data? (Choose two.)


    > A. KEY

    > C. VALUE

404. Which of the following Snowflake features provide continuous data protection automatically? (Select TWO).


    > c. Time Travelcorrect

    > E. Fail-safe

405. A developer is granted ownership of a table that has a masking policy. The developer’s role is not able to see the masked data. Will the developer be able to modify the table to read the masked data?


    > D. No, because ownership of a table does not include the ability to change masking policies.

406. How should a virtual warehouse be configured if a user wants to ensure that additional multi-clusters are resumed with no delay?


    > C. Use the standard warehouse scaling policy

407. During periods of warehouse contention, which parameter controls the maximum length of time a warehouse will hold a query for processing?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* B. STATEMENT_QUEUED_TIMEOUT_IN_SECONDS

408. Files have been uploaded to a Snowflake internal stage. The files now need to be deleted. Which SQL command should be used to delete the files?


    > C. REMOVE

409. In a Snowflake role hierarchy, what is the top-level role?


    > C. ACCOUNTADMIN

410. By default, which Snowflake role is required to create a share?


    > D. ACCOUNTADMIN

411. What happens to historical data when the retention period for an object ends?


    > B. The data moves to Fail-safe

412. A company’s security audit requires generating a report listing all Snowflake logins (e.g., date and user) within the last 90 days. Which of the following statements will return the required information?


    > D. SELECT EVENT_TIMESTAMP, USER_NAME
    FROM ACCOUNT_USAGE.LOGIN_HISTORY;

413. What are common issues found by using the Query Profile? (Choose two.)


    > D. Identifying inefficient micro-partition pruning

    > E. Data spilling to a local or remote disk

414. The Snowflake Search Optimization Services supports improved performance of which kind of query?


    > C. Selective point lookup queries

415. Which file formats are supported for unloading data from Snowflake? (Choose two.)


    > B. JSON

    > E. Delimited (CSV, TSV, etc.)

416. Which Snowflake tool would be BEST to troubleshoot network connectivity?


    > D. SnowCD

417. Increasing the size of a virtual warehouse from an X-Small to an X-Large is an example of which of the following?


    > D. Scaling up

418. What are ways to create and manage data shares in Snowflake? (Choose two.)


    > A. Through the Snowflake web interface (UI)

    > C. Through SQL commands

419. What is a characteristic of data micro-partitioning in Snowflake?


    > C. Micro-partitioning happens when the data is loaded

420. Users with the ACCOUNTADMIN role can execute which of the following commands on existing users?


    > A. Can SHOW users DESCRIBE a given user, or ALTER or DROP a user

421. According to Snowflake best practice recommendations, which system-defined roles should be used to create custom roles? (Choose two.)


    > C. SECURITYADMIN

    > D. USERADMIN

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

422. What services are provided by the cloud services layer in Snowflake? (Choose two.)


    > A. Metadata management

    > C. Authentication

423. Which of the following commands are valid options for the VALIDATION_MODE parameter within the Snowflake COPY_INTO command? (Choose two.)


    > C. RETURN_ALL_ERRORS

    > D. RETURN__ROWS

424. Snowflake virtual warehouses are part of which layer of the Snowflake architecture?


    > A. Compute layer

425. Which of the following are characteristics of schemas used in Snowflake? (Choose two.)


    > B. A database may contain one or more schemas.

    > C. A schema represents a logical grouping of database objects.

426. Which Snowflake objects can be used to reduce data storage costs for short-lived tables? (Choose two.)


    > B. Temporary tables

    > C. Transient tables

427. A user has unloaded data from Snowflake to a stage. Which SQL command should be used to validate which data was loaded into the stage?


    > A. list @file_stage

428. What are benefits of using the ACCESS_HISTORY view in the SNOWFLAKE database?


    > A. Identification of unused data

    > E. Identification of who has read data

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* AE or DE

429. Which of the following view types are available in Snowflake? (Choose two.)


    > B. Secure view

    > E. Materialized view

430. Which of the following statements describes a benefit of Snowflake’s separation of compute and storage? (Choose two.)


    > B. Storage expands without the requirement to add more compute.

    > C. Compute can be scaled up or down without the requirement to add more storage.

432. What is the default compression typo when unloading data from Snowflake?


    > D. gzip

433. Which statement describes when a virtual warehouse can be resized?


    > D. A resize can be completed at any time.

434. What is the compressed size limit for semi-structured data loaded into a VARIANT data type using the COPY command?


    > B. 16 MB

435. User A cloned a schema and overwrote a schema that User B was working on. User B no longer has access to their version of the tables. However, this all occurred within the Time Travel retention period defined at the database level. How should the missing tables be restored?


    > C. Rename the cloned schema and use an UNDROP SCHEMA statement.

436. How does Snowflake recommend handling the bulk loading of data batches from files already available in cloud storage?


    > D. Use the COPY command.

437. What is Snowflake's general guideline for files used to load data?


    > D. For delimited files, the default character set is UTF-8.

438. How does a Snowflake user execute an anonymous block of code?


    > B. The statements that define the block must also execute the block.

439. When unloading data from Snowflake, the user executes a COPY INTO command into an internal stage. What additional command is required to load the file onto the local file system?


    > A. GET

440. A Snowflake user has a query that is running for a long time. When the user opens the query profiler, it indicates that a lot of data is spilling to disk. What is causing this to happen?


    > D. The warehouse memory is not sufficient to hold the intermediate query results.

441. What is the MOST performant file format for loading data in Snowflake?


    > C. CSV (Gzipped)

442. Which chart type does Snowsight support to visualize worksheet data?


    > D. Scatterplot

443. Which result shows efficient pruning?


    > B. Partitions scanned is less than partitions total

444. Which clustering indicator will show if a large table in Snowflake will benefit from explicitly defining a clustering key?


    > B. Depth

445. Which file format is MOST performant in Snowflake for data loading?


    > B. CSV

446. What is to be expected when sharing worksheets in Snowsight?


    > B. To run a shared worksheet, a user must be granted the role used for the worksheet session context.

447. Which Snowflake objects track DML changes made to tables, like inserts, updates, and deletes?


    > B. Streams

448. Which table type is automatically deleted after a session is closed and has no Fail-safe or Time Travel cost?


    > A. Temporary

450. Which function is used to profile warehouse credit usage?


    > D. WAREHOUSE_METERING_HISTORY

451. What is a characteristic of the Snowflake query profiler?


    > B. It provides a graphic representation of the main components of the query processing.

452. A Snowflake user wants to share transactional data with retail suppliers. However, some of the suppliers do not use Snowflake. According to best practice, what should the Snowflake user do? (Choose two.)


    > A. Provide each non-Snowflake supplier with their own reader account.

    > D. Use a data share for suppliers in the same cloud region and a replicated proxy share for other cloud deployments.

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

453. Which statement about data sharing is true?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. The Data Consumer can only see objects in the Data Provider’s source database that have been explicitly added to the share.

454. Which command is used to load files into an internal stage within Snowflake?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* A. PUT

455. Which object type is granted permissions for reading a table?


    > B. Role

456. What is the default value in the Snowflake Web Interface (UI) for auto suspending a Virtual Warehouse?


    > C. 10 minutes

457. Several users are using the same virtual warehouse. The users report that the queries are running slowly, and that many queries are being queued. What is the recommended way to resolve this issue?


    > D. Increase the warehouse MAX_CLUSTER_COUNT parameter.

458. Which data types are valid in Snowflake? (Choose two.)


    > B. Geography

    > E. Variant

459. What happens when the size of a virtual warehouse is changed?


    > A. Queries that are running on the current warehouse configuration are not impacted.

460. How often are encryption keys automatically rotated by Snowflake?


    > A. 30 Days

461. As a best practice, all custom roles should be granted to which system-defined role?


    > D. SYSADMIN

462. Which Snowflake object can be accessed in the FROM clause of a query, returning a set of rows having one or more columns?


    > A. A User-Defined Table Function (UDTF)

463. How are micro-partitions typically generated in Snowflake?


    > A. Automatically

464. What does Snowflake recommend regarding database object ownership? (Choose two.)


    > B. Create objects with SYSADMIN.

    > D. Create objects with a custom role and grant this role to SYSADMIN.

465. Other than ownership what privileges does a user need to view and modify resource monitors in Snowflake? (Choose two.)


    > B. MONITOR

    > C. MODIFY

466. What technique does Snowflake recommend for determining which virtual warehouse size to select?


    > B. Experiment by running the same queries against warehouses of different sizes

467. Which command should be used when loading many flat files into a single table?


    > C. COPY INTO

468. How can a Snowflake user share data with another user who does not have a Snowflake account?


    > B. Create a reader account and create a share of the data

469. Which semi-structured data formats can be loaded into Snowflake with a COPY command? (Choose two.)


    > D. ORC

    > E. XML

470. Which statements reflect valid commands when using secondary roles? (Choose two.)


    > C. USE SECONDARY ROLES ALL

    > E. USE SECONDARY ROLES NONE

471. How long is a query visible in the Query History page in the Snowflake Web Interface (UI)?


    > C. 14 days

472. Two users share a virtual warehouse named WH_DEV_01. When one of the users loads data, the other one experiences performance issues while querying data. How does Snowflake recommend resolving this issue?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. Create separate warehouses for each workload

473. What is a feature of a stored procedure in Snowflake?


    > D. They can be created to run with a caller's rights or an owner's rights.

474. Which view will return users who have queried a table?


    > B. SNOWFLAKE.ACCOUNT_USAGE.ACCESS_HISTORY

475. Why do Snowflake’s virtual warehouses have scaling policies?


    > C. To help control the credits consumed by a multi-cluster warehouse running in auto-scale mode

476. Where can a Snowflake user find the query history in Snowsight?


    > B. Activity

477. What is SnowSQL?


    > C. Snowflake's command line client built on the Python connector which is used to connect to Snowflake and execute SQL.

478. The following SQL statements have been executed: What will the output be of the last select statement?


    > C. 7

479. Which statement is true of zero-copy cloning?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. All micro-partitions between the original and cloned tables are fully shared

480. A Snowflake user has been granted the CREATE DATA EXCHANGE LISTING privilege with their role. Which tasks can this user now perform on the Data Exchange? (Choose two.)


    > C. Modify listings properties

    > E. Submit listings for approval/publishing

481. Which parameter prevents streams on tables from becoming stale?


    > A. MAX_DATA_EXTENSION_TIME_IN_DAYS

482. If a virtual warehouse runs for 30 seconds after it is provisioned, how many seconds will the customer be billed for?


    > B. 60 seconds

483. When should a stored procedure be created with caller's rights?


    > C. When the stored procedure needs to run with the privileges of the role that called the stored procedure

484. What JavaScript delimiters are available in Snowflake stored procedures? (Choose two.)


    > B. Single quote (’)

    > E. Double dollar sign ($$)

485. What type of function can be used to estimate the approximate number of distinct values from a table that has trillions of rows?


    > D. HyperLogLog (HLL)

486. Which Data Definition Language (DDL) commands are supported by Snowflake to manage tags? (Choose two.)


    > A. ALTER TAG

    > C. DROP TAG

487. What Snowflake objects can be added to a share? (Choose two.)


    > B. Tables

    > E. Secure views

488. A Query Profile shows a UnionAll operator with an extra Aggregate operator on top. What does this signify?


    > C. UNION without ALL

489. Which data governance control has Snowflake embedded in the application?


    > D. Attribute-based access control

490. What actions does the use of the PUT command do automatically? (Choose two.)


    > C. It compresses all files using GZIP.

    > D. It encrypts the file data in transit.

491. Which command should a Snowflake user execute to load data into a table?


    > B. copy into mytable from @my_int_stage;

492. Which function returns the URL of a stage using the stage name as the input?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. GET_STAGE_LOCATION

493. What is the MAXIMUM number of clusters that can be provisioned with a multi-cluster virtual warehouse?


    > C. 10

494. Which Snowflake table supports unstructured data?


    > A. Directory

495. When unloading data, which file format preserves the data values for floating-point number columns?


    > D. Parquet

496. Which virtual warehouse privilege is required to view a load-monitoring chart?


    > A. MONTTOR

497. Which use case will always cause an exploding join in Snowflake?


    > C. A query that has not specified join criteria for tables.

498. How many resource monitors can be applied to a single virtual warehouse?


    > B. One

499. What are the main differences between the account usage views and the information schema views? (Choose two.)


    > C. Account usage views contain dropped objects but information schema views do not.

    > D. Data retention for account usage views is 1 year but is 7 days to 6 months for information schema views, depending on the view

500. Which file function provides a URL with access to a file on a stage without the need for authentication and authorization?


    > B. GET_PRESIGNED_URL

501. Which view can be used to determine if a table has frequent row updates or deletes?


    > B. TABLE_STORAGE_METRICS

502. How does the Snowflake search optimization service improve query performance?


    > D. It improves the performance of equality searches.

503. How is unstructured data retrieved from data storage?


    > B. SQL functions can be used to create different types of URLs pointing to the unstructured data. These URLs can be used to download the data to a client.

504. What is the recommended way to obtain a cloned table with the same grants as the source table?


    > A. Clone the table with the COPY GRANTS command.

505. What common query issues can be identified using the Query Profile? (Choose two.)


    > B. Exploding joins

    > D. Inefficient pruning

506. What is used to extract the content of PDF files stored in Snowflake stages?


    > D. Java User-Defined Function (UDF)

507. What is used to extract the content of PDF files stored in Snowflake stages?


    > D. Java User-Defined Function (UDF)

508. What happens when a database is cloned?


    > C. It replicates all granted privileges on the corresponding child objects.

509. What does a Query Profile provide in Snowflake?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. A graphical representation of the main components of the processing plan for a query.

510. When executing a COPY INTO command, performance can be negatively affected by using which optional parameter on a large number of files?


    > B. PATTERN

511. Which URL type should be used to get a permanent URL to a file in a stage?


    > A. File URL

512. Which operation will produce an error in Snowflake?


    > B. Inserting a NULL into a column with a NOT NULL constraint

513. How are URLs that access unstructured data in external stages retrieved?


    > B. By querying a directory table

514. What is the Snowflake multi-clustering feature for virtual warehouses used for?


    > C. To improve concurrency for users and queries

515. Which features could be used to improve the performance of queries that return a small subset of rows from a large table? (Choose two.)


    > A. Search optimization service

    > B. Automatic clustering

516. Which command would return an empty sample?


    > B. select * from testtable sample (0);

517. What Snowflake function should be used to unload relational data to JSON?


    > B. OBJECT_CONSTRUCT()

518. Floating point values are truncated when unloaded to which file format?


    > B. CSV

519. Which levels can apply network policies? (Choose two.)


    > A. Account

    > E. User

520. What causes objects in a data share to become unavailable to a consumer account?


    > C. The objects in the data share are being deleted and the grant pattern is not re-applied systematically

521. How can an administrator check for updates (for example, SCIM API requests) sent to Snowflake by the identity provider?


    > D. REST_EVENT_HISTORY

522. A Snowflake user is writing a User-Defined Function (UDF) with some unqualified object names. How will those object names be resolved during execution?


    > B. Snowflake will only check the schema the UDF belongs to.

523. Why should a user select the economy scaling policy for a multi-cluster warehouse?


    > D. To conserve credits by keeping running clusters fully loaded

524. What MINIMUM privilege is required on the external stage for any role in the GET REST API to access unstructured data files using a file URL?


    > C. USAGE

525. Which view in SNOWFLAKE.ACCOUNT_USAGE shows from which IP address a user connected to Snowflake?


    > B. LOGIN_HYSTORY

526. Snowflake Partner Connect is limited to users with a verified email address and which role?


    > C. ACCOUNTADMIN

527. What unit of storage supports efficient query processing in Snowflake?


    > D. Micro-partitions

528. What is the difference between a stored procedure and a User-Defined Function (UDF)?


    > A. Stored procedures can execute database operations while UDFs cannot

529. Which URL type does Snowflake recommend to use when providing unstructured data to other accounts through a share?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. Scoped

531. What is the advantage of using a reader account?


    > A. It can be used by a client that does not have a Snowflake account

532. What command is used to export or unload data from Snowflake?


    > C. Copy INTO @mystage

533. A Snowflake user wants to share data with someone who does not have a Snowflake account. How can the Snowflake user share the data?


    > B. Create a reader account.

534. A user wants to add additional privileges to the system-defined roles for their virtual warehouse. How does Snowflake recommend they accomplish this?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* A. Grant the additional privileges to a custom role.

535. How does Snowflake store a table's underlying data? (Choose two.)


    > A. Columnar file format

    > B. Micro-partitions

536. What is the MAXIMUM number of days a Snowflake-managed encryption key can be used before it gets automatically rotated?


    > C. 30 days

537. Which user object property requires contacting Snowflake Support in order to set a value for it?


    > C. MINS_TO_BYPASS_NETWORK_POLICY

538. How does Snowflake handle the bulk unloading of data into single or multiple files?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* A. It assigns each unloaded data file a unique name.

539. What information is included in the display in the Query Profile? (Choose two.)


    > D. Details and statistics for the overall query

    > E. Graphical representation of the query processing plan

540. A Snowflake user wants to optimize performance for a query that queries only a small number of rows in a table. The rows require significant processing. The data in the table does not change frequently. What should the user do?


    > C. Create a materialized view based on the query.

541. When using the ALLOW_CLIENT_MFA_CACHING parameter, how long is a cached Multi-Factor Authentication (MFA) token valid for?


    > C. 4 hours

542. When unloading data, which file formats are supported by the COPY INTO command? (Choose two.)


    > B. JSON

    > D. Parquet

543. A JSON object is loaded into a column named data using a Snowflake variant datatype. The root node of the object is BIKE. The child attribute for this root node is BIKEID. Which statement will allow the user to access BIKEID?


    > C. select data:BIKE.BIKEID

544. A custom role owns multiple tables. If this role is dropped from the system, who becomes the owner of these tables?


    > D. The role that dropped the custom role.

545. Which function produces a lateral view of a VARIANT column?


    > B. FLATTEN

546. Snowflake strongly recommends that all users with what type of role be required to use Multi-Factor Authentication (MFA)?


    > B. ACCOUNTADMIN

547. What does it mean when the sample function uses the Bernoulli sampling method?


    > A. The data is based on sampling every row.

548. What are characteristics of Snowflake network policies? (Choose two.)


    > A. They can be set for any Snowflake Edition

    > C. They restrict or enable access to specific IP addresses.

549. Which function should be used to find the query ID of the second query executed in a current session?


    > D. Select LAST_QUERY_ID(2)

550. How is the hierarchy of database objects organized in Snowflake?


    > A. A database consists of one or more schemas. A schema contains tables and views.

551. Which role can execute the SHOW ORGANIZATION ACCOUNTS command successfully?


    > C. ORGADMIN

552. Which data types in Snowflake are synonymous for FLOAT? (Choose two.)


    > B. DOUBLE

    > E. REAL

553. What ensures that a user with the role SECURITYADMIN can activate a network policy for an individual user?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. Ownership privilege on both the user and the network policy

554. Which function can be combined with the copy command to unload a relational table into a JSON file?


    > C. OBJECT_CONSTRUCT

555. A user needs to MINIMIZE the cost of large tables that are used to store transitory data. The data does not need to be protected against failures, because the data can be reconstructed outside of Snowflake. What table type should be used?


    > B. Transient

556. While loading data from a JSON file, what enables the removal of the outer array structure from the file and loads the records into separate table rows?


    > C. STRIP_OUTER_ARRAY

557. Which functions can be used to share unstructured data through a secure view? (Choose two.)


    > A. BUILD_SCOPED_FILE_URL

    > D. GET_PRESIGNED_URL

558. Which function will return a row for each for each object in a VARIANT, OBJECT, or ARRAY column?


    > B. FLATTEN

559. What is the MINIMUM size of a table for which Snowflake recommends considering adding a clustering key?


    > D. 1 Terabyte (TB)

560. For the ALLOWED_VALUES tag property, what is the MAXIMUM number of possible string values for a single tag?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. 256

561. Which Snowflake table type is only visible to the user who creates it, can have the same name as permanent tables in the same schema, and is dropped at the end of the session?


    > A. Temporary

562. What is a characteristic of a role in Snowflake?


    > D. Privileges on securable objects can be granted and revoked to a role.

563. What command would a user execute to load unstructured data files into a Snowflake internal stage?


    > A. PUT

564. How do managed access schemas help with data governance?


    > B. They provide centralized privilege management with the schema owner.

565. What is the default period of time the Warehouse Activity section provides a graph of Snowsight activity?


    > C. 2 weeks

566. A Snowflake user wants to unload data from a relational table sized 5 GB using CSV. The extract needs to be as performant as possible. What should the user do?


    > D. Leave the default MAX_FILE_SIZE to 16 MB to take advantage of parallel operations.

567. How is the MANAGE GRANTS privilege applied?


    > A. Globally

568. What is required for a query execution to be served from the result cache?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* B. The SQL texts the same.

569. Which Snowflake URL type is used by directory tables?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* A. File

570. At which point is data encrypted when using a PUT command?


    > C. Before it is sent from the user's machine

571. Which privileges are required for a user to restore an object? (Choose two.)


    > B. OWNERSHIP

    > E. CREATE

572. For a multi-cluster virtual warehouse, which parameters are used to calculate the number of credits billed? (Choose two.)


    > B. Warehouse size

    > C. Number of clusters

573. What happens when the values for both an ALLOWED_IP_LIST and a BLOCKED_IP_LIST are used in a network policy?


    > B. Snowflake applies the BLOCKED_IP_LIST first.

574. What does the orange bar on an operator represent when reviewing the Query Profile?


    > B. The fraction of time that this operator consumed within the query step.

575. When unloading data from Snowflake, what is the default file size of each file?


    > A. 16 MB

576. What is the abbreviated form to get all the files in the stage for the current user?


    > B. LS @~;

577. Which features make up Snowflake's column level security? (Choose two.)


    > B. Dynamic Data Masking

    > C. External Tokenization

578. Which programming languages are supported for Snowflake User-Defined Functions (UDFs)? (Choose two.)


    > B. JavaScript

    > D. Python

579. What is the MAXIMUM number of days that Snowflake resets the 24-hour retention period for a query result every time the result is used?


    > C. 31 days

580. There are 300 concurrent users on a production Snowflake account using a single cluster virtual warehouse. The queries are small, but the response time is very slow. What is causing this to occur?


    > A. The warehouse is queuing the queries, increasing the overall query execution time.

581. Which Snowflake edition offers the highest level of security for organizations that have the strictest requirements?


    > D. Virtual Private Snowflake (VPS)

582. What is the MAXIMUM size limit for a record of a VARIANT data type?


    > B. 16 MB

583. What criteria does Snowflake use to determine the current role when initiating a session? (Choose two.)


    > A. If a role was specified as part of the connection and that role has been granted to the Snowflake user, the specified role becomes the current role.

    > B. If no role was specified as part of the connection and a default role has been defined for the Snowflake user, that role becomes the current role.

584. What command should be used to move data from a Snowflake database table into one or more files in an external stage?


    > B. COPY INTO

585. How does a Snowflake user reference a directory table created on stage mystage in a SQL query?


    > B. SELECT * FROM DIRECTORY (@mystage)

586. Why would a Snowflake user create a secure view instead of a standard view?


    > B. End users are unable to see the view definition, and internal optimizations differ with a secure view.

587. Which command can be added to the COPY command to make it load all files, whether or not the load status of the files is known?


    > A. FORCE = TRUE

588. How can a Snowflake user improve long-running query performance?


    > B. Cluster the underlying table being queried.

589. Which Snowflake feature allows administrators to identify unused data that may be archived or deleted?


    > A. Access history

590. Which SQL commands should be used to write a recursive query if the number of levels is unknown? (Choose two.)


    > A. CONNECT BY

    > E. WITH

591. What information is stored in the ACCESS_HISTORY view?


    > C. Query details such as the objects included and the user who executed the query

592. What privilege does a user need in order to receive or request data from the Snowflake Marketplace?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. IMPORT SHARE

593. Which Snowflake database object can be shared with other accounts?


    > C. Secure User-Defined Functions (UDFs)

594. Which identity providers are valid type values for federated authentication on the SAML_IDENTITY_PROVIDER parameter? (Choose two.)


    > B. Microsoft Active Directory Federation Services (AD FS)

    > D. Okta

595. A Snowflake user wants to share data using my_share with account xy12345. Which command should be used?


    > C. alter share my_share add accounts = xy12345;

596. What role is required to use Partner Connect?


    > A. ACCOUNTADMIN

597. How can a Snowflake user configure a virtual warehouse to support over 100 users if their company has Enterprise Edition?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. Use a multi-cluster warehouse.

598. How is table data compressed in Snowflake?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* A. Each column is compressed as it is stored in a micro-partition.

599. What will be the output of the below query against the table name gold_data? select \* from gold_data tablesample (100);


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. It will return an entire table.

600. A Snowflake query took 40 minutes to run. The results indicate that ‘Bytes spilled to local storage’ was a large number. What is the issue and how can it be resolved?


    > B. The warehouse is too small. Increase the size of the warehouse to reduce the spillage

601. What is the MOST efficient way to load streaming data into Snowflake?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* B. Use Snowpipe.

602. Which COPY INTO statement accurately describes how to unload data from a Snowflake table?


    > C. The OBJECT_CONSTRUCT function can be combined with the COPY command to convert the rows in a relational table to a single VARIANT column.

603. What command is used to download data from a Snowflake stage?


    > C. GET

604. By default, which role has privileges to create tables and views in an account?


    > C. SYSADMIN

605. What does Snowflake recommend as a best practice for using secure views?


    > D. Do not expose the sequence-generated column(s).

606. What is the Fail-safe period for a transient table in the Snowflake Enterprise edition and higher?


    > A. 0 days

607. How does a Snowflake user enable Multi-Factor Authentication (MFA)?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* A. The user must enroll themselves through the web interface.

608. What allows a user to limit the number of credits consumed within a Snowflake account?


    > B. Creating resource monitors

609. Which statement accurately describes Snowflake's architecture?


    > C. It is a hybrid of traditional shared-disk and shared-nothing database architectures.

610. Which Snowflake SQL command is used to get a subset of rows randomly from a table?


    > D. SAMPLE

611. Which statement accurately describes how a virtual warehouse functions?


    > C. Each virtual warehouse is a compute cluster composed of multiple compute nodes allocated by Snowflake from a cloud provider.

612. Which Snowflake object can be used to record DML changes made to a table?


    > C. Stream

613. Which statistic displayed in a Query Profile is specific to external functions?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* B. Total invocations

614. If there is queueing in the virtual warehouse load monitoring chart, what should a Snowflake user do?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. Change the multi-cluster settings to add additional clusters

616. How long is the load history stored in the metadata of the pipe in Snowpipe?


    > C. 14 days

617. What are the key characteristics of ACСOUNT_USAGE views? (Choose two.)


    > B. The data latency can vary from 45 minutes to 3 hours.

    > E. Records for dropped objects are included in each view.

618. How does a scoped URL expire?


    > B. When the persisted query result period ends.

619. What are the available Snowflake scaling modes for configuring multi-cluster virtual warehouses? (Choose two.)


    > A. Auto-Scale

    > C. Maximized

620. Which loop type iterates until a condition is true?


    > C. REPEAT

621. Which property needs to be added to the ALTER WAREHOUSE command to verify the additional compute resources for a virtual warehouse have been fully provisioned?


    > D. WAIT_FOR_COMPLETION

622. How is enhanced authentication achieved in Snowflake? (Choose two.)


    > D. Multi-Factor Authentication (MFA)

    > E. Federated authentication and Single Sign-On (SSO)

623. What are the native data types that Snowflake provides to store semi-structured data? (Choose two.)


    > A. ARRAY

    > E. VARIANT

624. How long is the Fail-safe period for recovering historical data from permanent tables?


    > C. 7 days

625. What does the average_overlaps in the output of SYSTEM$CLUSTERING_INFORMATION refer to?


    > C. The average number of micro-partitions which contain overlapping value ranges.

626. If queries start to queue in a multi-cluster virtual warehouse an additional compute cluster starts immediately under what setting?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. Standard scaling policy

627. When floating-point number columns are unloaded to CSV or JSON files, Snowflake truncates the values to approximately what?


    > D. (15,9)

628. By definition, a secure view is exposed only to users with what privilege?


    > B. OWNERSHIP

629. What happens when a user exits Snowsight during a session that a query is running?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. Snowflake will continue to execute and complete upon the next login.

630. Which native data types are used for storing semi-structured data in Snowflake? (Choose two.)


    > B. OBJECT

    > E. VARIANT

631. Which columns are available in the output of a Snowflake directory table? (Choose two.)


    > C. LAST_MODIFIED

    > D. RELATIVE_PATH

632.What is used to diagnose and troubleshoot network connections to Snowflake?

    > A. SnowCD

633. What Snowflake object records Data Manipulation Language (DML) changes so that actions can be taken using the changed data?


    > B. Stream

634. By default, the COPY INTO statement will separate table data into a set of output files to take advantage of which Snowflake feature?


    > C. Parallel processing

635. Which command can be used to view the allowed and blocked IP list of a network policy?


    > C. DESCRIBE NETWORK POLICY

636. Which file functions are non-deterministic? (Choose two.)


    > A. BUILD_SCOPED_FILE_URL

    > D. GET_PRESIGNED_URL

637. How can a Snowflake user optimize query performance in Snowflake? (Choose two.)


    > B. Cluster a table.

    > C. Enable the search optimization service.

638. What is the MINIMUM role required to set the value for the parameter ENABLE_ACCOUNT_DATABASE_REPLICATION?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. ORGADMIN

639. Which file format will keep floating-point numbers from being truncated when data is unloaded?


    > D. Parquet

640. A user has semi-structured data to load into Snowflake but is not sure what types of operations will need to be performed on the data. Based on this situation, what type of column does Snowflake recommend be used?


    > D. VARIANT

641. Which Snowflake object helps evaluate virtual warehouse performance impacted by query queuing?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. Information_schema.warehouse_load_history

642. Which Snowflake object can be created to be temporary?


    > B. Stage

644. What is the recommended approach for unloading data to a cloud storage location from Snowflake?


    > B. Unload the data directly to the cloud storage location.

645. Which command is used to unload files from an internal or external stage to a local file system?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* B. GET

646. A tabular User-Defined Function (UDF) is defined by specifying a return clause that contains which keyword?


    > B. TABLE

647. Which SQL statement will require a virtual warehouse to run?


    > C. INSERT INTO TBL_EMPLOYEE(EMP_ID, EMP_NAME, EMP_SALARY, DEPT) VALUES(1, 'Adam', 20000, 'Finance’);

648. Which REST API can be used with unstructured data?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. GET /api/files/

649. Which query contains a Snowflake hosted file URL in a directory table for a stage named bronzestage?


    > B. select * from directory(@bronzestage);

650. Which feature is integrated to support Multi-Factor Authentication (MFA) at Snowflake?


    > B. Duo Security

651. In which Snowflake layer does Snowflake reorganize data into its internal optimized, compressed, columnar format?


    > B. Database Storage

652. When can user session variables be accessed in a Snowflake scripting procedure?


    > B. When the procedure is defined to execute as CALLER.

653. What computer language can be selected when creating User-Defined Functions (UDFs) using the Snowpark API?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. Python

654. A user needs to ingest 1 GB of data that is available in an external stage using a COPY INTO command. How can this be done with MAXIMUM performance and the LEAST cost?


    > C. Split the file into smaller files of 100-250 MB each, compress and ingest each of the smaller files.

655. A Snowflake user has two tables that contain numeric values and is trying to find out which values are present in both tables. Which set operator should be used?


    > A. INTERSECT

656. A view is defined on a permanent table. A temporary table with the same name is created in the same schema as the referenced table. What will the query from the view return?


    > B. The data from the temporary table.

657. Which file function generates a Snowflake-hosted file URL to a staged file using the stage name and relative file path as inputs?


    > A. BUILD_STAGE_FILE_URL

658. Which service or feature in Snowflake is used to improve the performance of certain types of lookup and analytical queries that use an extensive set of WHERE conditions?


    > C. Search optimization service

659. What is the name of the SnowSQL file that can store connection information?


    > B. config

660. How do secure views compare to non-secure views in Snowflake?


    > A. Secure views execute slowly compared to non-secure views.

662. When unloading data to an external stage, what is the MAXIMUM file size supported?


    > B. 5 GB

663. How long does Snowflake retain information in the ACCESS_HISTORY view?


    > D. 365 days

664. Which encryption type will enable client-side encryption for a directory table?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. SNOWFLAKE_FULL

665. If file format options are specified in multiple locations, the load operation selects which option FIRST to apply in order of precedence?


    > D. COPY INTO TABLE statement

666. A complex SQL query involving eight tables with joins is taking a while to execute. The Query Profile shows that all partitions are being scanned. What is causing the query performance issue?


    > A. Pruning is not being performed efficiently.

667. What does Snowflake's search optimization service support?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. Tables and views that are not protected by row access policies

668. Which table type is no longer available after the close of the session and therefore has no Fail-safe or Time Travel recovery option?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. Temporary

669. How many network policies can be assigned to an account or specific user at a time?


    > A. One

670. What is a characteristic of a tag associated with a masking policy?


    > B. A tag can have only one masking policy for each data type.

671. Which clients does Snowflake support Multi-Factor Authentication (MFA) token caching for? (Choose two.)


    > C. ODBC driver

    > D. Python connector

672. What is the Snowflake recommended Parquet file size when querying from external tables to optimize the number of parallel scanning operations?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. 256-512 MB

673. Which data types can be used in a Snowflake table that holds semi-structured data? (Choose two.)


    > A. ARRAY

    > D. VARIANT

674. Which constraint is enforced in Snowflake?


    > B. NOT NULL

675. Which pages are included in the Activity area of Snowsight? (Choose two.)


    > C. Copy History

    > D. Query History

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

676. When should a user consider disabling auto-suspend for a virtual warehouse? (Choose two.)


    > B. When managing a steady workload

    > C. When the compute must be available with no delay or lag time

677. What can a Snowflake user do in the Activity section in Snowsight?


    > D. Explore executed query performance.

678. How does Snowflake reorganize data when it is loaded? (Choose two.)


    > B. Columnar format

    > C. Compressed format

679. Which operations are handled in the Cloud Services layer of Snowflake? (Choose two.)


    > A. Security

    > E. Metadata management

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

680. At which point is data encrypted when using a PUT command?


    > C. Before it is sent from the user's machine

681. What type of columns does Snowflake recommend to be used as clustering keys? (Choose two.)


    > D. A column that is most actively used in selective filters

    > E. A column that is most actively used in join predicates

682. Which objects together comprise a namespace in Snowflake? (Choose two.)


    > B. Database

    > C. Schema

684. How do Snowflake data providers share data that resides in different databases?


    > B. Secure views

685. What operations can be performed while loading a simple CSV file into a Snowflake table using the COPY INTO command? (Choose two.)


    > B. Reordering the columns

    > D. Converting the datatypes

686. Which commands support a multiple-statement request to access and update Snowflake data? (Choose two.)


    > B. COMMIT

    > E. ROLLBACK

687. Why should a Snowflake user implement a secure view? (Choose two.)


    > C. To limit access to sensitive data

    > E. To hide view definition and details from unauthorized users

688. At what levels can a resource monitor be configured? (Choose two.)


    > A. Account

    > E. Virtual warehouse

689. What activities can be monitored by a user directly from Snowsight's Activity tab without using the Account_Usage views? (Choose two.)


    > B. Query history

    > C. Copy history

690. What can a Snowflake user do with the information included in the details section of a Query Profile?


    > A. Determine the total duration of the query.

691. How can a Snowflake user access a JSON object, given the following table? (Choose two.)


    > B. src:salesPerson.name

    > D. SRC:salesPerson.name

692. Which term is used to describe information about disk usage for operations where intermediate results cannot be accommodated in a Snowflake virtual warehouse memory?


    > B. Spilling

693. There are two Snowflake accounts in the same cloud provider region: one is production and the other is non-production. How can data be easily transferred from the production account to the non-production account?


    > B. Create a data share from the production account to the non-production account.

694. A user is unloading data to a stage using this command: copy into @message from (select object_construct('id', 1, 'first_name', 'Snowflake', 'last_name', 'User', 'city', 'Bozeman')) file_format = (type = json). What will the output file in the stage be?


    > A. A single compressed JSON file with a single VARIANT column

695. A JSON file that contains lots of dates and arrays needs to be processed in Snowflake. The user wants to ensure optimal performance while querying the data. How can this be achieved?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* A. Flatten the data and store it in structured data types in a flattened table. Query the table.

696. When referring to User-Defined Function (UDF) names in Snowflake, what does the term overloading mean?


    > C. There are multiple SQL UDFs with the same names but with a different number of arguments or argument types.

697. Which key governance feature in Snowflake allows users to identify data objects that contain sensitive data and their related objects?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* B. Data classification

698. What can a Snowflake user do in the Admin area of Snow right?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. Connect to Snowflake partners to explore extended functionality

699. Which function generates a Snowflake hosted file URL to a staged file using the stage name and relative file path as inputs?


    > A. BUILD_STAGE_FILE_URL

700. What is the purpose of using the OBJECT_CONSTRUCT function with the COPY INTO command?


    > B. Convert the rows in a relational table to a single VARIANT column and then unload the rows into a file.

701. Which URL provides access to files in Snowflake without authorization?


    > C. Pre-signed URL

702. What type of NULL values are supported in semi-structured data? (Choose two.)


    > B. JSON

    > E. SQL

703. What are characteristics of transient tables in Snowflake? (Choose two.)


    > C. Transient tables persist until they are explicitly dropped.

    > E. Transient tables have Time Travel retention periods of 0 or 1 day.

704. The INFORMATION_SCHEMA included in each database contains which objects? (Choose two.)


    > A. Views for all the objects contained in the database

    > D. Table functions for historical and usage data across the Snowflake account

705. The use of which technique or tool will improve Snowflake query performance on very large tables?


    > B. Clustering keys

706. Which Snowflake layer is associated with virtual warehouses?


    > B. Query processing

707. Which MINIMUM set of privileges is required to temporarily bypass an active network policy by configuring the user object property MINS_TO_BYPASS_NETWORK_POLICY?


    > D. Only Snowflake Support can set the value for this object property

708. What authentication method does the Kafka connector use within Snowflake?


    > A. Key pair authentication

709. What is the purpose of the Snowflake SPLIT_TO_TABLE function?


    > C. To split a string and flatten the results into rows

710. What feature of Snowflake Continuous Data Protection can be used for maintenance of historical data?


    > D. Time Travel

711. What aspect of an executed query is represented by the remote disk I/O statistic of the Query Profile in Snowflake?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. Time spent reading and writing data from and to remote storage when the data being accessed does not fit into either the virtual warehouse memory or the local disk

712. What action can a user take to address query concurrency issues?


    > C. Add additional clusters to the virtual warehouse

713. What does the client redirect feature in Snowflake enable?


    > B. A redirect of client connections to Snowflake accounts in different regions for business continuity.

714. Which Snowflake feature can be used to find sensitive data in a table or column?


    > B. Data classification

715. Which Snowflake feature allows a user to track sensitive data for compliance, discovery, protection, and resource usage?


    > A. Tags

716. Snowflake’s hierarchical key mode includes which keys? (Choose two.)


    > A. Account master keys

    > C. File keys

717. What can the Snowflake SCIM API be used to manage? (Choose two.)


    > D. Roles

    > E. Users

718. Which privilege is required to use the search optimization service in Snowflake?


    > C. GRANT ADD SEARCH OPTIMIZATION ON SCHEMA TO ROLE

719. What is generally the FASTEST way to bulk load data files from a stage?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* A. Specifying a list of specific files to load

720. How does a Snowflake user extract the URL of a directory table on an external stage for further transformation?


    > D. Use the GET_STAGE_LOCATION function.

721. A Snowflake user needs to share unstructured data from an internal stage to a reporting tool that does not have Snowflake access. Which file function should be used?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. GET_PRESIGNED_URL

722. The use of which Snowflake table type will reduce costs when working with ETL workflows?


    > C. Temporary

723. What is one of the characteristics of data shares?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. Data shares utilize secure views for sharing view objects.

724. What is the MINIMUM configurable idle timeout value for a session policy in Snowflake?


    > B. 5 minutes

725. Which command is used to unload data from a Snowflake table to an external stage?


    > A. COPY INTO

726. What is a characteristic of materialized views in Snowflake?


    > A. Materialized views do not allow joins.

727. Which Snowflake URL type allows users or applications to download or access files directly from Snowflake stage without authentication?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. Pre-signed

728. Which SQL command will download all the data files from an internal table stage named TBL_EMPLOYEE to a local window directory or folder on a client machine in a folder named folder with space within the C drive?


    > B. GET @%TBL_EMPLOYEE 'file://C:/folder with space/';

729. ow can the COPY command be used to unload data from a table to an internal stage?


    > A. COPY INTO

730. How does a Snowflake stored procedure compare to a User-Defined Function (UDF)?


    > B. A single executable statement can call only one stored procedure. In contrast, a single SQL statement can call multiple UDFs.

731. Which command should be used to unload all the rows from a table into one or more files in a named stage?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* A. COPY INTO

732. Which command is used to unload data from a table or move a query result to a stage?


    > A. COPY INTO

733. What privileges are necessary for a consumer in the Data Exchange to make a request and receive data? (Choose two.)


    > A. CREATE DATABASE

    > B. IMPORT SHARE

734. What are benefits of using Snowpark with Snowflake? (Choose two.)


    > C. Snowpark does not require that a separate cluster be running outside of Snowflake.

    > E. Snowpark executes as much work as possible in the source databases for all operations including User-Defined Functions (UDFs)

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

735. What are Snowflake best practices when assigning the ACCOUNTADMIN role to users? (Choose two.)


    > A. The ACCOUNTADMIN role should be assigned to at least two users.

    > E. All users assigned the ACCOUNTADMIN role should use Multi-Factor Authentication (MFA).

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

736. What is a recommended approach for optimizing query performance in Snowflake?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. Use a smaller number of larger tables rather than a larger number of smaller tables.

737. When using SnowSQL, which configuration options are required when unloading data from a SQL query run on a local machine? (Choose two.)


    > C. output_file

    > D. output_format

738. Which Snowflake view is used to support compliance auditing?


    > A. ACCESS_HISTORY

739. How can a Snowflake user load duplicate files with a COPY INTO command?


    > B. The COPY INTO options should be set to FORCE = TRUE

740. What is an advantage of using a multi-cluster virtual warehouse as compared to a single-cluster virtual warehouse in Snowflake?


    > D. A user can specify the maximum and minimum number of cluster(s).

741. Which statement describes Snowflake tables?


    > A. Snowflake tables are logical representations of underlying physical data.

742. Which type of charts are supported by Snowsight? (Choose two.)


    > C. Line charts

    > E. Scatterplots

743. A user wants to upload a file to an internal Snowflake stage using a PUT command. Which tools and/or connectors could be used to execute this command? (Choose two.)


    > B. SnowSQL

    > D. Python connector

744. Which Snowflake table is an implicit object layered on a stage, where the stage can be either internal or external?


    > A. Directory table

**\*\***\*\***\*\***\*\***\*\***\*\***\*\*** 745. The Query Profile in the image is for a query executed in Snowsight. Four of the key nodes are highlighted in yellow. Which highlighted node will be the MOST expensive?

    > D. TableScan[3]

746. What is a characteristic of the maintenance of a materialized view?


    > C. A materialized view is automatically refreshed by a Snowflake managed warehouse.

747. Which command should be used to implement a masking policy that was already created in Snowflake?


    > D. SET MASKING POLICY

748. What would be the credit consumption?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. Snowflake will charge for 60 seconds at the rate of 32 credits per hour.

749. Which statement accurately describes a characteristic of a materialized view?


    > A. A materialized view can query only a single table

750. The use of which Snowflake table type will reduce costs when working with ETL workflows?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. Temporary

751. A user wants to unload data from a relational table into a CSV file in an external stage. The table must be named exactly as specified by the user. Which file format option MUST be used to do this?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. single

752. Which account usage view in Snowflake can be used to identify the most-frequently accessed tables?


    > A. Access_History

753. What metadata does Snowflake store concerning all rows stored in a micro-partition? (Choose two.)


    > D. The range of values for each of the columns in the micro-partition

    > E. The number of distinct values for each column in the micro-partition

754. What role has the privileges to create and manage data shares by default?


    > A. ACCOUNTADMIN

755. Which function determines the kind of value stored in a VARIANT column?


    > D. TYPEOF

756. What operation can be performed using Time Travel?


    > C. Creating a clone of an entire table at a specific point in the past from a permanent table

757. What are characteristics of Snowflake directory fables? (Choose two.)


    > D. Directory tables store file-level metadata about the data files in a stage.

    > E. A directory table can be added to a stage when the stage is created, or later.

758. What does the VARIANT data type impose a 16 MB size limit on?


    > C. Individual rows

759. Which activities are included in the Cloud Services layer? (Choose two.)


    > D. User authentication

    > E. Infrastructure management

760. What does the “percentage scanned from cache” represent in the Query Profile?


    > D. The percentage of data scanned from the local disk cache

761. Which role has the ability to create a share from a shared database by default?


    > A. ACCOUNTADMIN

762. Which object-level parameters can be set to help control query processing and concurrency? (Choose two).


    > D. STATEMENT_TIMEOUT_IN_SECONDS

    > E. STATEMENT_QUEUED_TIMEOUT_IN_SECONDS

763. What metadata does Snowflake store for rows in micro-partitions? (Choose two.)


    > A. Range of values

    > B. Distinct values

764. What are valid sub-clauses to the OVER clause for a window function? (Choose two.)


    > C. ORDER BY

    > D. PARTITION BY

765. Which kind of Snowflake table stores file-level metadata for each file in a stage?


    > A. Directory

766. Which privileges apply to stored procedures? (Choose two.)


    > D. OWNERSHIP

    > E. USAGE

767. What column type does a Kafka connector store formatted information in a single column?


    > D. VARIANT

768. If a size Small virtual warehouse costs two credits per hour, what is the credit cost per hour of a size Large virtual warehouse?


    > B. 8

769. Which SQL command will list the files in a named stage?


    > C. list @my_stage;

770. What is the effect of configuring a virtual warehouse auto-suspend value to ‘0’?


    > A. The warehouse will never suspend.

771. Which data types can be used in Snowflake to store semi-structured data? (Choose two.)


    > A. ARRAY

    > E. VARIANT

772. While attempting to avoid data duplication, which COPY INTO option should be used to load files with expired load metadata?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* A. LOAD_UNCERTAIN_FILES

773. What service is provided as an integrated Snowflake feature to enhance Multi-Factor Authentication (MFA) support?


    > A. Duo Security

774. What is the impact on queries that are being executed when a resource monitor set to the “Notify & Suspend” threshold level is exceeded?


    > D. All statements being executed are completed.

775. What tasks can an account administrator perform in the Data Exchange? (Choose two.)


    > A. Add and remove members.

    > C. Approve and deny listing approval requests.

776. Which types of subqueries does Snowflake support? (Choose two.)


    > B. Uncorrelated scalar subqueries in any place that a value expression can be used

    > E. EXISTS, ANY / ALL, and IN subqueries in WHERE clauses: these subqueries can be correlated or uncorrelated

777. How can network and private connectivity security be managed in Snowflake?


    > A. By setting up network policies with IPv4 IP addresses

778. What consideration should be made when loading data into Snowflake?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. The number of data files that are processed in parallel is determined by the virtual warehouse.

779. How can a user improve the performance of a single large complex query in Snowflake?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* A. Scale up the virtual warehouse

780. Who can access a referenced file through a scoped URL?


    > B. Only the user who generates the URL

781. Snowflake will return an error when a user attempts to share which object?


    > C. Standard views

782. What setting in Snowsight determines the databases, tables, and other objects that can be seen and the actions that can be performed on them?


    > A. Active role

783. Why would a Snowflake user decide to use a materialized view instead of a regular view?


    > A. The base tables do not change frequently.

784. When a database is cloned, which objects in the clone inherit all granted privileges from the source object? (Choose two.)


    > C. Schemas

    > D. Tables

785. How does the Access_History view enhance overall data governance pertaining to read and write operations? (Choose two.)


    > A. Shows how the accessed data was moved from the source to the target objects

    > B. Provides a unified picture of what data was accessed and when it was accessed

     > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

786. What does Snowflake recommend a user do if they need to connect to Snowflake with a tool or technology that is not listed in Snowflake’s partner ecosystem?


    > D. Connect through Snowflake’s JDBC or ODBC drivers.

787. What is the expiration period for a file URL used to access unstructured data in cloud storage?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* B. An unlimited amount of time

788. Which applications can use key pair authentication? (Choose two).


    > D. SnowSQL

    > E. Snowflake connector for Python

789. Which commands can only be executed using SnowSQL? (Choose two.)


    > B. GET

    > D. PUT

790. A user has enabled the STRIP_OUTER_ARRAY file format option for the COPY INTO {table} command to remove the outer array structure. What else will this format option and command do?


    > A. Load the records into separate table rows.

791. Which objects will incur storage costs associated with Fail-safe?


    > B. Permanent tables

792. What technique does Snowflake use to limit the number of micro-partitions scanned by each query?


    > D. Pruning

793. What activities can a user with the ORGADMIN role perform? (Choose two.)


    > B. View usage information for all accounts in the organization.
    > D. Enable database replication for an account in the organization.

794. In a managed access schema, who can grant privileges on objects in the schema to other roles? (Choose two.)


    > A. The schema owner role
    > D. The role with the MANAGE GRANTS privilege

795. What are the recommended steps to address poor SQL query performance due to data spilling? (Choose two.)


    > C. Use a larger virtual warehouse.

    > D. Process the data in smaller batches.

     > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

796. A Snowflake user wants to share unstructured data through the use of secure views. Which URL types can be used? (Choose two.)


    > A. Scoped URL
    > E. Pre-signed URL

797. What are characteristics of reader accounts in Snowflake? (Choose two.)


    > A. Reader account users cannot add new data to  the account.
    > E. Reader accounts enable data consumers to access and query data shared by the provider.

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

798. Why should a Snowflake user configure a secure view? (Choose two.)


    > C. To protect hidden data from other users
    > E. To hide the view definition from other users

799. Which activities are managed by Snowflake’s Cloud Services layer? (Choose two.)


    > A. Authentication
    > E. Query parsing and optimization

800. The COPY INTO command can unload data from a table directly into which locations? (Choose two.)


    > A. A named internal stage
    > E. A named external stage that references an external cloud location

801. What does the Activity area of Snowsight allow users to do? (Choose two.)


    > B. Explore each step of an executed query.
    > C. Monitor queries executed by users in an account.

802. In which Snowsight section can a user switch roles, modify their profile, and access documentation?


    > A. The user menu

803. What is the recommended way to change the existing file format type in my_format from CSV to JSON?


    > C. CREATE OR REPLACE FILE FORMAT my_format TYPE=JSON;

804. Which features are included in Snowsight? (Choose two.)


    > A. Worksheet sharing
    > C. Exploring the Snowflake Marketplace

805. How long can a data consumer who has a pre-signed URL access data files using Snowflake?


    > D. Until the expiration_time is exceeded

806. What mechanisms can be used to inform Snowpipe that there are staged files available to load into a Snowflake table? (Choose two.)


    > A. Cloud messaging
    > D. REST endpoints

807. A Snowflake user needs to import a JSON file larger than 16 MB. What file format option could be used?


    > C. strip_outer_array = true

808. What is a feature of column-level security in Snowflake?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. External tokenization

809. Which common query problems can the Query Profile help a user identify and troubleshoot? (Choose two.)


    > B. When there are exploding joins
    > C. When there is a UNION without ALL

810. What is the Fail-safe retention period for transient and temporary tables?


    > A. 0 days

811. Which Snowflake features can be enabled by calling the SYSTEM$GLOBAL_ACCOUNT_SET_PARAMETER function by a user with the ORGADMIN role? (Choose two.)


    > B. Client redirect
    > E. Account and database replication

812. What are characteristics of directory tables when used with unstructured data? (Choose two.)


    > C. Directory tables store a catalog of staged files in cloud storage.

    > D. A directory table can be added explicitly to a stage when the stage is created.

813. Snowflake best practice recommends that which role be used to enforce a network policy on a Snowflake account?


    > B. SECURITYADMIN

814. What is the default behavior of internal stages in Snowflake?


    > D. Each user and table are automatically allocated an internal stage.

815. The MAXIMUM size for a serverless task run is equivalent to what size virtual warehouse?


    > C. 2X-Large

816. What storage cost is completely eliminated when a Snowflake table is defined as transient?


    > B. Fail-safe

817. How can a Snowflake user traverse semi-structured data?


    > A. Insert a colon (:) between the VARIANT column name and any first-level element.

818. Based on Snowflake recommendations, when creating a hierarchy of custom roles, the top-most custom role should be assigned to which role?


    > C. SYSADMIN

819. What happens to the privileges granted to Snowflake system-defined roles?


    > A. The privileges cannot be revoked.

820. By default, which role allows a user to manage a Snowflake Data Exchange share?


    > A. ACCOUNTADMIN

821. How does the PARTITION BY option affect an expression for a COPY INTO command?


    > B. The unload operation partitions table rows into separate files unloaded to the specified stage.

822. How does Snowflake improve the performance of queries that are designed to filter out a significant amount of data?


    > B. The use of pruning

823. A JSON document is stored in the source_column of type VARIANT. The document has an array called elements. The array contains the name key that has a string value. How can a Snowflake user extract the name from the first element?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. source_column:elements[0].name

824. Which function should be used to insert JSON formatted string data into a VARIANT field?


    > C. PARSE_JSON

825. Which permission on a Snowflake virtual warehouse allows the role to resize the warehouse?


    > B. MODIFY

826. What is it called when a customer managed key is combined with a Snowflake managed key to create a composite key for encryption?


    > C. Tri-secret secure encryption

827. What is the COPY INTO command option default for unloading data into multiple files?


    > D. SINGLE = FALSE

828. A size 3X-Large multi-cluster warehouse runs one cluster for one full hour and then runs two clusters for the next full hour. What would be the total number of credits billed?


    > D. 192

829. What is the impact of increasing the number of concurrent users on a Snowflake virtual warehouse?


    > C. Decreased performance for large, complex queries

830. By default, how long is the standard retention period for Time Travel across all Snowflake accounts?


    > B. 1 day

831. What type of query will benefit from the query acceleration service?


    > B. Queries with large scans and selective filters

832. How does the search optimization service help Snowflake users improve query performance?


    > B. It maintains a persistent data structure that keeps track of the values of the table’s columns in each of its micro-partitions.

833. What can be done to reduce queueing on a virtual warehouse?


    > B. Change the warehouse to a multi-cluster warehouse.

834. What are characteristics of Snowsight worksheets? (Choose two.)


    > B. Each worksheet is a unique Snowflake session.
    > E. Users can import worksheets and share them with other users.

835. What are reasons for using the VALIDATE function in Snowflake after a COPY INTO command execution? (Choose two.)

     > A. To validate the files that have been loaded earlier using the COPY INTO command

     > C. To return errors encountered during the execution of the COPY INTO command

836. Which command will unload data from a table into an external stage?


    > C. COPY INTO

837. Which query will return a sample of a table with 1000 rows named testtable, in which each row has a 10% probability of being included in the sample?


    > B. select * from testtable sample (10);

838. Which system function can be used to manage access to the data in a share and display certain data only to paying customers?


    > D. SYSTEM$IS_LISTING_PURCHASED

839. Which Snowflake object does not consume any storage costs?


    > A. Secure view

840. What does the LATERAL modifier for the FLATTEN function do?


    > C. Joins information outside the object with the flattened data

841. How can a Snowflake user validate data that is unloaded using the COPY INTO command?


    > D. Use the VALIDATION_MODE = RETURN_ROWS    statement.

842. What role in Snowflake separates the management of users and roles from the management of all grants?


    > D. USERADMIN

843. Which command will unload data from a table into an external stage?


    > C. COPY INTO

844. Why is a federated environment used for user authentication in Snowflake?


    > C. To separate user authentication from user access

845. What will happen if a Snowflake user increases the size of a suspended virtual warehouse?


    > C. The provisioning of additional compute resources will be in effect when the warehouse is next resumed.

846. The VALIDATE table function has which parameter as an input argument for a Snowflake user?


    > D. JOB_ID

847. Which Snowflake edition supports Protected Health Information (PHI) data (in accordance with HIPAA and HITRUST CSF regulations), and has a dedicated metadata store and pool of compute resources?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. Virtual Private Snowflake (VPS)

848. Which Snowflake table types are used to manage costs for short-lived tables? (Choose two.)


    > D. Temporary tables
    > E. Transient tables

849. What are key characteristics of virtual warehouses in Snowflake? (Choose two.)


    > B. Warehouses can be started and stopped at any time.
    > C. Warehouses can be resized at any time, even while running.

850. What strategies can be used to optimize the performance of a virtual warehouse? (Choose two.)


    > A. Reduce queuing.
    > D. Increase the warehouse size.

851. How are privileges inherited in a role hierarchy in Snowflake?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* A. Privileges are inherited by any roles above that role in the hierarchy.

852. At what level can the ALLOW_CLIENT_MFA_CACHING parameter be set?


    > A. Account

853. What entity is responsible for hosting and sharing data in Snowflake?


    > A. Data provider

854. Which function will provide the proxy information needed to protect Snowsight?


    > C. SYSTEM$ALLOWLIST

855. The property MINS_TO_BYPASS_NETWORK_POLICY is set at which level?


    > A. User

856. When unloading the data for file format type specified (TYPE = 'CSV'), SQL NULL can be converted to string ‘null’ using which file format option?


    > C. NULL_IF

857. Which table function should be used to view details on a Directed Acyclic Graph (DAG) run that is presently scheduled or is executing?


    > C. CURRENT_TASK_GRAPHS

858. What Snowflake database object is derived from a query specification, stored for later use, and can speed up expensive aggregation on large data sets?


    > D. Materialized view

859. User1, who has the SYSADMIN role, executed a query on Snowsight. User2, who is in the same Snowflake account, wants to view the result set of the query executed by User1 using the Snowsight query history. What will happen if User2 tries to access the query history?


    > D. User2 will be unable to view the result set of the query executed by User1

860. A permanent table and temporary table have the same name, TBL1, in a schema.

What will happen if a user executes select \* from TBL1;?

    > A. The temporary table will take precedence over the permanent table.

861. The effects of query pruning can be observed by evaluating which statistics? (Choose two.)


    > A. Partitions scanned
    > B. Partitions total

862. Which data types optimally store semi-structured data? (Choose two.)


    > A. ARRAY
    > E. VARIANT

863. What compute resource is used when loading data using Snowpipe?


    > C. Snowpipe uses compute resources provided by Snowflake.

864. Which file function gives a user or application access to download unstructured data from a Snowflake stage?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* A. BUILD_SCOPED_FILE_URL or  C. GET_PRESIGNED_URL

865. By default, which role can create resource monitors?


    > A. ACCOUNTADMIN

866. Which DDL/DML operation is allowed on an inbound data share?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. SELECT

867. Which types of charts does Snowsight support? (Choose two.)


    > A. Area charts
    > E. Scorecards

868. Which role in Snowflake allows a user to enable replication for multiple accounts?


    > D. ORGADMIN

869. Which Snowflake tool is recommended for data batch processing?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*B. SnowSQL

870. Which Snowflake mechanism is used to limit the number of micro-partitions scanned by a query?


    > C. Query pruning

871. While clustering a table, columns with which data types can be used as clustering keys? (Choose two.)


    > A. BINARY
    > C. GEOMETRY

872. Which use case does the search optimization service support?


    > D. Conjunctions (AND) of multiple equality predicates

873. What should be used when creating a CSV file format where the columns are wrapped by single quotes or double quotes?


    > C. FIELD_OPTIONALLY_ENCLOSED_BY

874. If a multi-cluster warehouse is using an economy scaling policy, how long will queries wait in the queue before another cluster is started?


    > C. 6 minutes

875. What does the TableScan operator represent in the Query Profile?


    > A. The access to a single table

876. What information is found within the Statistic output in the Query Profile Overview?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* B. Table pruning

877. Which roles can make grant decisions to objects within a managed access schema? (Choose two.)


    > A. ACCOUNTADMIN
    > B. SECURITYADMIN

878. How can a Snowflake user post-process the result of SHOW FILE FORMATS?


    > A. Use the RESULT_SCAN function.

879. A Snowflake account administrator has set the resource monitors as shown in the diagram, with actions defined for each resource monitor as “Notify & Suspend Immediately”. What is the MAXIMUM limit of credits that Warehouse 2 can consume?


    > D. 5000

880. When initially creating an account in Snowflake, which settings can be specified? (Choose two.)


    > D. Region
    > E. Snowflake edition

881. What activities can a user with the ORGADMIN role perform? (Choose two.)


    > A. Create an account for an organization.
    > D. View usage information for all accounts in an organization.

882. What is one of the benefits of using a multi-cluster virtual warehouse?


    > D. It will automatically start and stop additional clusters as needed

883. When should a multi-cluster virtual warehouse be used in Snowflake?


    > A. When queuing is delaying query execution on the warehouse

884. What is used to denote a pre-computed data set derived from a SELECT query specification and stored for later use?


    > C. Materialized view

885. A Snowflake user wants to temporarily bypass a network policy by configuring the user object property MINS_TO_BYPASS_NETWORK_POLICY. What should they do?


    > D. Contact Snowflake Support.

886. What is the default access of a securable object until other access is granted?


    > A. No access

887. From what stage can a Snowflake user omit the FROM clause while loading data into a table?


    > B. The table stage

888. What is used during the FIRST execution of SELECT COUNT(\*) FROM ORDER?


    > D. Metadata-based result

889. What is the purpose of a resource monitor in Snowflake?


    > D. To control costs and credit usage by virtual warehouses

890. Which data formats are supported by Snowflake when unloading semi-structured data? (Choose two.)


    > B. Binary file in Parquet
    > D. Newline Delimited JSON

891. In Snowflake, the use of federated authentication enables which Single Sign-On (SSO) workflow activities? (Choose two.)


    > C. Logging into Snowflake
    > D. Logging out of Snowflake

892. What does the worksheet and database explorer feature in Snowsight allow users to do?


    > B. Move a worksheet to a folder or a dashboard.

893. When unloading data from Snowflake to AWS, what permissions are required? (Choose two.)


    > A. s3:DeleteObject
    > D. s3:PutObject

894. What step can reduce data spilling in Snowflake?


    > A. Using a larger virtual warehouse

895. Which user preferences can be set for a user profile in Snowsight? (Choose two.)


    > A. Multi-Factor Authentication (MFA)
    > D. Notifications
    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

896. What privilege is needed for a Snowflake user to see the definition of a secure view?


    > A. OWNERSHIP

897. What general guideline does Snowflake recommend when setting the auto-suspension time limit?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* B. Set tasks for suspension after 5 minutes.

898. When does Snowflake automatically encrypt data that is loaded into Snowflake? (Choose two.)


    > B. After loading the data into a table.
    > C. After loading the data into an internal stage.

899. When data is loaded into Snowflake, what formats does Snowflake use internally to store the data in cloud storage? (Choose two.)


    > B. Columnar
    > E. Compressed

900. What do temporary and transient tables have in common in Snowflake? (Choose two.)


    > A. Both tables have no Fail-safe period.
    > B. Both tables have data retention period maximums of one day.

901. What are the least privileges needed to view and modify resource monitors? (Choose two.)


    > C. MONITOR
    > D. MODIFY
    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

902. When does a materialized view get suspended in Snowflake?


    > B. When a column is dropped from the base table

903. What happens when a Snowflake user changes the data retention period at the schema level?


    > B. All child objects that do not have an explicit retention period will automatically inherit the new retention period

904. Snowpark provides libraries for which programming languages? (Choose two.)


    > B. Python
    > C. Scala

905. How can a Snowflake user sample 10 rows from a table named SNOWPRO? (Choose two.)


    > B. SELECT * FROM SNOWPRO TABLESAMPLE (10 ROWS)
    > E. SELECT * FROM SNOWPRO SAMPLE BERNOULLI (10 ROWS)
    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

906. Why would a Snowflake user choose to use a transient table?


    > D. To store transitory data that needs to be maintained beyond the session

907. What does a masking policy consist of in Snowflake?


    > A. A single data type, with one or more conditions, and one or more masking functions

908. What actions can be performed by a consumer account on a shared database? (Choose two.)


    > D. Executing the SELECT statement on a shared table

    > E. Joining the data from a shared table with another table

909. What data type is used to ingest semi-structured data into a Snowflake table?


    > D. VARIANT

910. Which security feature is used to connect or log in to a Snowflake account?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. Key pair authentication

911. Given the statement template below, which database objects can be added to a share? (Choose two.)

GRANT [privilege] ON [object] [object_name] TO SHARE [share_name];

    > A. Secure functions
    > D. Tables

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

912. Which Snowflake feature or tool helps troubleshoot issues in SQL query expressions that commonly cause performance bottlenecks?

     D. Query Profile

913. What is a non-configurable feature that provides historical data that Snowflake may recover during a 7-day period?


    > A. Fail-safe

914. Which function should be used to authorize users to access rows in a base table when using secure views with Secure Data Sharing?


    > A. CURRENT_ACCOUNT()

915. What is the purpose of collecting statistics on data in Snowflake?


    > B. To enable efficient pruning based on query filters

916. What type of function returns one value for each invocation?


    > B. Scalar

917. Which file formats support unloading semi-structured data? (Choose two.)


    > B. JSON
    > D. Parquet

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

918. Which system-defined Snowflake role has permission to rename an account and specify whether the original URL can be used to access the renamed account?


    > D. ORGADMIN

919. How can a user get the MOST detailed information about individual table storage details in Snowflake?


    > D. TABLE_STORAGE_METRICS View

920. What type of account can be used to share data with a consumer who does not have a Snowflake account?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* A. Data provider or C. Reader

921. By default, which role has access to the SYSTEM$GLOBAL_ACCOUNT_SET_PARAMETER function?


    > D. ORGADMIN

922. If a virtual warehouse is suspended, what happens to the warehouse cache?


    > A. The cache is dropped when the warehouse is suspended and is no longer available upon restart.

923. What are the primary authentication methods that Snowflake supports for securing REST API interactions? (Choose two.)


    > A. OAuth
    > E. Username and password authentication

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

924. A Snowflake user is trying to load a 125 GB file using SnowSQL. The file continues to load for almost an entire day. What will happen at the 24-hour mark?


    > C. The file loading could be aborted without any portion of the file being committed.

925. What information does the Query Profile provide?


    > B. Statistics for each component of the processing plan

926. Which command is used to start configuring Snowflake for Single Sign-On (SSO)?


    > C. CREATE SECURITY INTEGRATION

927. Which sequence (order) of object privileges should be used to grant a custom role read-only access on a table?

> C

| Object   | privilege |
| -------- | --------- |
| Database | Usage     |
| Schema   | Usage     |
| Table    | Select    |

928. Which command removes a role from another role or a user in Snowflake?


    > B. REVOKE ROLE

929. In which hierarchy is tag inheritance possible?


    > D. Schema » Table » Column

930. What happens when a network policy includes values that appear in both the allowed and blocked IP address lists?


    > B. Those IP addresses are denied access to the Snowflake account as Snowflake applies the blocked IP address list first. Most Voted

931. For directory tables, what stage allows for automatic refreshing of metadata?


    > D. Named external stage

932. Which command is used to unload data from a Snowflake database table into one or more files in a Snowflake stage?


    > C. COPY INTO `[location]`

933. Any user with the appropriate privileges can view data storage for individual tables by using which queries? (Choose two.)


    > B. TABLE_STORAGE_METRICS view in the ACCOUNT_USAGE schema
    > D. TABLE_STORAGE_METRICS view in the INFORMATION_SCHEMA schema

934. A user created a database and set the DATA_RETENTION_TIME_IN_DAYS to 30, but did not set the DATA_RETENTION_TIME_IN_DAYS in table T1. After 5 days, the user accidentally drops table T1.

What are the considerations for recovering table T1?

    > > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* B. The table can be recovered because the table retention period default is at the database level.

935. What table functions in the Snowflake Information Schema can be queried to retrieve information about directory tables? (Choose two.)


    > A. AUTO_REFRESH_REGISTRATION_HISTORY

    > E. STAGE_DIRECTORY_FILE_REGISTRATION_HISTORY

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

936. Which Snowflake table type persists until it is explicitly dropped, is available for all users with relevant privileges (across sessions), and has no Fail-safe period?


    > D. Transient

937. Snowflake’s access control framework combines which models for securing data? (Choose two.)


    > B. Discretionary Access Control (DAC)
    > D. Role-based Access Control (RBAC)

938. Which semi-structured file format is a compressed, efficient, columnar data representation?


    > D. Parquet

939. How does Snowflake describe its unique architecture?


    > B. A multi-cluster shared data architecture using a central data repository and massively parallel processing (MPP)

940. Which data type can be used to load semi-structured data files directly, without explicitly describing the hierarchical structure of the data?


    > B. VARIANT

941. The following settings are configured:

THE MIN_DATA_RETENTION_TIME_IN_DAYS is set to 5 at the account level.
THE DATA_RETENTION_TIME_IN_DAYS is set to 2 at the object level.

For how many days will the data be retained at the object level?

    > C. 5

942. Which key access control concept does Snowflake describe as a defined level of access to an object?


    > B. Privilege

943. Which Snowflake object uses credits for maintenance?


    > C. Materialized view

944. How many credits does a size 3X-Large virtual warehouse consume if it runs continuously for 2 hours?


    > C. 128

945. What is the purpose of a Query Profile?


    > B. To profile a particular query to understand the mechanics of the query, its behavior, and performance.

946. Which common query problems are identified by the Query Profile? (Choose two.)


    > B. Inefficient pruning
    > D. Queries too large to fit in memory

947. While running a query on a virtual warehouse in auto-scale mode, additional clusters are started immediately if which setting is configured?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. MIN_CLUSTER_COUNT is increased and new_min_clusters is greater than running_clusters

948. Which Snowflake role can manage any object grant globally, including modifying and revoking grants?


    > D. SECURITYADMIN

949. What is the MINIMUM permission needed to access a file URL from an external stage?


    > D. USAGE

950. In the Data Exchange, who can get or request data from the listings? (Choose two.)


    > A. Users with ACCOUNTADMIN role
    > D. Users with IMPORT SHARE privilege

951. What does Snowflake attempt to do if any of the compute resources for a virtual warehouse fail to provision during start-up?


    > A. Repair the failed resources.

952. How does Snowflake define its approach to Discretionary Access Control (DAC)?


    > C. Each object has an owner, who can in turn grant access to that object.

953. Which command is used to take away staged files from a Snowflake stage after a successful data ingestion?


    > C. REMOVE

954. The Snowflake VARIANT data type imposes a 16 MB size limit on what?


    > A. An individual row

955. Which Snowflake feature records changes made to a table so actions can be taken using that change data capture?


    > C. Stream

956. Which system-defined, read-only view displays information on column lineage that specifies how data flows from source to target in a SQL write operation?


    > A. ACCESS_HISTORY

957. Who can create network policies within Snowflake? (Choose two.)


    > C. SECURITYADMIN or higher roles
    > D. A role with the CREATE NETWORK POLICY privilege

958. Who can grant object privileges in a regular schema?


    > A. Object owner

959. Which command can be used to list all the file formats for which a user has access privileges?


    > D. SHOW FILE FORMATS

960. Which Snowflake feature supports continuous, serverless data loading into tables as soon as new data arrives?


    > D. Snowpipe

962. Regardless of which notation is used, what are considerations for writing the column name and element names when traversing semi-structured data?


    > D. The column name is case-insensitive but element names are case-sensitive.

963. Which Snowflake data type is used to store JSON key value pairs?


    > D. VARIANT

964. How are network policies defined in Snowflake?


    > D. They are a set of rules that control access to Snowflake accounts by specifying the IP addresses or ranges of IP addresses that are allowed to connect to Snowflake.

965. What is the only supported character set for loading and unloading data from all supported file formats?


    > A. UTF-8

966. Which function is used to convert rows in a relational table to a single VARIANT column?


    > D. OBJECT_CONSTRUCT

967. Which command can be used to delete staged files from a Snowflake stage when the files are no longer needed?


    > C. REMOVE

968. A virtual warehouse initially suffers from poor performance as a result of queries from multiple concurrent processes that are queuing. Over time, the problem resolved.

What action can be taken to prevent this from happening again?

    > C. Change the multi-cluster settings to add additional clusters.

969. What action can be performed using the GET command in Snowflake?


    > C. Download data files from Snowflake internal stages to a local directory/folder.

970. Which validation option is the only one that supports the COPY INTO [location] command?


    > A. RETURN_ROWS

971. What are the correct settings for column and element names, regardless of which notation is used while accessing elements in a JSON object?


    > D. The column name is case-insensitive and the element name is case-sensitive.

972. How can the Query Profile be used to identify the costliest operator of a query?


    > B. Find the operator node with the highest fraction of time or percentage of total time.

973. In order to access Snowflake Marketplace listings, who needs to accept the Snowflake Consumer Terms of Service?


    > D. ORGADMIN

974. Which statistics are displayed in a Query Profile that indicate that intermediate results do not fit in memory? (Choose two.)


    > C. Bytes spilled to local storage
    > D. Bytes spilled to remote storage

975. How can a dropped internal stage be restored?


    > D. Recreate the dropped stage.

976. Which command line flags can be used to log into a Snowflake account using SnowSQL? (Choose two.)


    > A. -d
    > D. -a

977. What is a key benefit of using organizations in Snowflake?


    > C. Ability to consolidate account management and billing

978. Which privilege is required on a virtual warehouse to abort any existing executing queries?


    > B. OPERATE

979. Which command should be used to look into the validity of an XML object in Snowflake?


    > D. CHECK_XML

980. Who can activate a network policy for users in a Snowflake account? (Choose two.)


    > A. ACCOUNTADMIN
    > E. Any role that has the global ATTACH POLICY privilege

981. For which use cases is running a virtual warehouse required? (Choose two.)


    > B. When loading data into a table
    > C. When unloading data from a table

982. What action should be taken if a Snowflake user wants to share a newly created object in a database with consumers?


    > D. Use the GRANT privilege ... TO SHARE command to grant the necessary privileges.

983. Which Snowflake privilege is required on a pipe object to pause or resume pipes?


    > A. OPERATE

984. Which commands can a Snowflake user execute to specify a cluster key for a table? (Choose two.)


    > A. CREATE
    > C. ALTER

985. Authorization to execute CREATE [object] statements comes only from which role?


    > A. Primary role

986. Which VALIDATION_MODE value will return the errors across the files specified in a COPY command, including files that were partially loaded during an earlier load?


    > D. RETURN_ALL_ERRORS

987. Which command is used to upload data files from a local directory or folder on a client machine to an internal stage, for a specified table?


    > B. PUT

988. Which governance feature is supported by all Snowflake editions?


    > D. OBJECT_DEPENDENCIES view

989. Which chart type is supported in Snowsight for Snowflake users to visualize data with dashboards?


    > C. Heat grid

990. At what level is the MIN_DATA_RETENTION_TIME_IN_DAYS parameter set?


    > A. Account

991. Which function returns an integer between 0 and 100 when used to calculate the similarity of two strings?


    > B. JAROWINKLER_SIMILARITY

992. Which Snowflake data governance feature can support auditing when a user query reads column data?


    > A. Access History

993. Which categories are included in the execution time summary in a Query Profile? (Choose two.)


    > C. Initialization
    > D. Local Disk I/O

994. Which command can be used to list all network policies available in an account?


    > D. SHOW NETWORK POLICIES

995. Which type of loop requires a BREAK statement to stop executing?


    > B. LOOP

996. Which virtual warehouse consideration can help lower compute resource credit consumption?


    > C. Automating the virtual warehouse suspension and resumption settings

997. To use the OVERWRITE option on INSERT, which privilege must be granted to the role?


    > B. DELETE

998. What happens when a suspended virtual warehouse is resized in Snowflake?


    > D. The additional compute resources are provisioned when the warehouse is resumed.

999.  How does Snowflake handle the data retention period for a table if a stream has not been consumed?


    > C. The data retention period is temporarily extended to the stream’s offset.

1000. Which task is supported by the use of Access History in Snowflake?


    > C. Compliance auditing

1002. When enabling access to unstructured data, which URL permits temporary access to a staged file without the need to grant privileges to the stage or to issue access tokens?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* B. Scoped URL

1003. Which Snowflake function is maintained separately from the data and helps to support features such as Time Travel, Secure Data Sharing, and pruning?


    > D. Metadata management

1004. A tag object has been assigned to a table (TABLE_A) in a schema within a Snowflake database. Which CREATE object statement will automatically assign the TABLE_A tag to a target object?


    > A. CREATE TABLE [table_name] LIKE TABLE_A;

1005. In addition to performing all the standard steps to share data, which privilege must be granted on each database referenced by a secure view in order to be shared?


    > C. REFERENCE_USAGE

1006. Which function can be used with the COPY INTO [LOCATION] statement to convert rows from a relational table to a single VARIANT column, and to unload rows into a JSON file?


    > C. OBJECT_CONSTRUCT

1007. Which type of role can be granted to a share?


    > C. Database role

1008. When unloading data with the COPY INTO [location] command, what is the purpose of the PARTITION BY parameter option?


    > D. To split the output into multiple files, one for each distinct value of the specified expression.

1009. What are potential impacts of storing non-native values like dates and timestamps in a VARIANT column in Snowflake?


    > B. Slower query performance and increased storage consumption

1010. Which views are included in the DATA_SHARING_USAGE schema? (Choose two.)


    > D. MONETIZED_USAGE_DAILY

    > E. LISTING_TELEMETRY_DAILY

1011. What does a table with a clustering depth of 1 mean in Snowflake?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. The table has no overlapping micro-partitions.

1012. Which Snowflake object contains all the information required to share a database?


    > D. Share

1013. What is the PRIMARY factor that determines the cost of using a virtual warehouse in Snowflake?


    > D. The length of time the compute resources in each cluster run

1014. Which function generates a Snowflake-hosted file URL to a staged file using the stage name and relative file path as inputs, with a file URL that does not expire?


    > B. BUILD_STAGE_FILE_URL

1015. When a Snowflake user loads CSV data from a stage, which COPY INTO [table] command guideline should they follow?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* B. The number of columns in each row should be consistent.

1016. A user creates a stage using the following command:

CREATE STAGE mystage -
DIRECTORY = (ENABLE = TRUE)
FILE_FORMAT = myformat;

What will be the outcome?

    > B. A stage with a directory table that has metadata that must be manually refreshed will be created

1017. Which statistics on a Query Profile reflect the efficiency of the query pruning? (Choose two.)


    > B. Partitions total

1018. Which operation can be performed on Snowflake external tables?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. ALTER

1019. A user wants to access files stored in a stage without authenticating into Snowflake.

Which type of URL should be used?

    > D. Pre-signed URL

1020. Which table function is used to view all errors encountered during a previous data load?


    > A. VALIDATE

1022. Which role has the ability to create and manage users and roles?


    > B. USERADMIN

1023. What issues can be identified and troubleshooted using the Query Profile? (Choose two.)


    > B. Cartesian products
    > D. Queries too large to fit in memory

1024. What happens to the objects in a reader account when the DROP MANAGED ACCOUNT command is executed?


    > A. The objects are dropped.

1025. What function can be used with the recursive argument to return a list of distinct key names in all nested elements in an object?


    > A. FLATTEN

1026. What does Snowflake recommend when planning virtual warehouse usage for a data load?


    > B. Dedicate a separate warehouse for loading data.

1027. Which Snowflake database object can be used to track data changes made to table data?


    > C. Stream

1028. Who can activate and enforce a network policy for all users in a Snowflake account? (Choose two.)


    > B. A user with a SECURITYADMIN or higher role
    > C. A role that has been granted the ATTACH POLICY privilege

1029. How can a data provider share their Snowflake data? (Choose two.)


    > C. Direct share
    > E. Snowflake Marketplace listing

1030. What will prevent unauthorized access to a Snowflake account from an unknown source?


    > A. Network policy

1031. Which query type is supported for implementing the search optimization service?


    > D. Geography value column searches using geospatial functions

1032. What Snowflake feature provides a data hub for secure data collaboration, with a selected group of invited members?


    > C. Data Exchange

1033. Which semi-structured data function interprets an input string as a JSON document that produces a VARIANT value?


    > A. PARSE_JSON

1034. Which Snowflake data types can be used to build nested hierarchical data? (Choose two.)


    > B. OBJECT
    > C. VARIANT

1035. Which statistics can be used to identify queries that have inefficient pruning? (Choose two.)


    > C. Partitions scanned
    > D. Partitions total

1036. Which element in the Query Profile interface shows the relationship between the nodes in the execution of a query?


    > D. Operator Tree

1037. What will happen if a Snowflake user suspends the updates to a materialized view?


    > A. The queries on that view will generate an error message.

1038. Which Snowflake function will parse a JSON-null into a SQL-null?


    > D. STRIP_NULL_VALUE

1039. Which Snowflake command can be used to unload the result of a query to a single file?


    > C. Use COPY INTO [internal stage] with SINGLE = TRUE followed by a GET command to download the file.

1040. How are micro-partitions enabled on Snowflake tables?


    > B. Micro-partitioning is automatically performed on a table.

1041. What persistent data structures are used by the search optimization service to improve the performance of point lookups?


    > D. Search access paths

1042. Which Snowflake feature provides increased login security for users connecting to Snowflake that is powered by Duo Security service?


    > D. Multi-Factor Authentication (MFA)

1043. A user with which privileges can create or manage other users in a Snowflake account? (Choose two.)


    > D. OWNERSHIP

    > E. CREATE USER

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1044. Which items are considered schema objects in Snowflake? (Choose two.)


    > A. Pipe
    > B. File format

1045. What does SnowCD help Snowflake users to do?


    > C. Troubleshoot network connections to Snowflake.

1046. Awarding a user which privileges on all virtual warehouses is equivalent to granting the user the global MANAGE WAREHOUSES privilege?


    > A. MODIFY, MONITOR and OPERATE privileges

1047. A Snowflake account has activated federated authentication. What will occur when a user with a password that was defined by Snowflake attempts to log in to Snowflake?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. After entering the username and password, the user will be redirected to an Identity Provider (IdP) login page.

1048. Which solution improves the performance of point lookup queries that return a small number of rows from large tables using highly selective filters?


    > D. Search optimization service

1049. What does a Notify & Suspend action for a resource monitor do?


    > C. Send a notification to all account administrators who have notifications enabled, and suspend all assigned warehouses after all statements being executed by the warehouses have completed.

1050. When working with a managed access schema, who has the OWNERSHIP privilege of any tables added to the schema?


    > C. The schema owner

1051. How can a Snowsight user change a Standard virtual warehouse to a Snowpark-optimized virtual warehouse?


    > C. Use the ALTER WAREHOUSE command on a suspended Standard virtual warehouse.

1052. According to best practices, which table type should be used if the data can be recreated outside of Snowflake?


    > C. Transient table

1053. Which function unloads data from a relational table to JSON?


    > D. OBJECT_CONSTRUCT

1054. What is the purpose of the STRIP_NULL_VALUES file format option when loading semi-structured data files into Snowflake?


    > D. It removes object or array elements containing null values.

1055. Which Snowflake edition enables data sharing only through Snowflake Support?


    > A. Virtual Private Snowflake

1056. What is the primary purpose of partitioning staged data files for regular data loads?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* A. To improve the performance of data loads

1057. What is the minimum Snowflake Edition that supports secure storage of Protected Health Information (PHI) data?


    > C. Business Critical Edition

1058. What can a Snowflake user do to reduce queuing on a multi-cluster virtual warehouse?


    > C. Increase the maximum number of clusters.

1059. Which statements describe benefits of Snowflake's separation of compute and storage? (Choose two.)


    > A. The separation allows independent scaling of computing resources.
    > E. Compute can be scaled up or down without the requirement to add more storage.

1060. What should be used to show the status of partial data loads and loading errors?


    > A. The COPY_HISTORY function

1062. Which object can be used with Secure Data Sharing?


    > C. External table

1063. Which parameter can be set at the account level to set the minimum number of days for which Snowflake retains historical data in Time Travel?


    > C. MIN_DATA_RETENTION_TIME_IN_DAYS

1064. Which commands are restricted in owner's rights stored procedures? (Choose two.)


    > A. SHOW
    > E. DESCRIBE

1065. What is the relationship between a Query Profile and a virtual warehouse?


    > A. A Query Profile can help users right-size virtual warehouses.

1066. Which transformation is supported by a COPY INTO [table] command?


    > C. Cast using a SELECT statement

1068. How does conditional data masking work in Snowflake?


    > D. It selectively masks a column value based on another column.

1069. If a virtual warehouse runs for 61 seconds, shuts down, and then restarts and runs for 30 seconds, for how many seconds is it billed?


    > D. 121

1070. What function, combined with the copy command, should be used to unload data from a relational table into a JSON file?


    > D. OBJECT_CONSTRUCT

1072. Which Snowflake table objects can be shared with other accounts? (Choose two.)


    > B. Permanent tables

    > D. External tables

1073. Which metadata table will store the storage utilization information even for dropped tables?


    > B. TABLE_STORAGE_METRICS

1074. How is role hierarchy established in Snowflake?


    > C. By granting one role to another role

1075. What commands can be used to see what files are stored in a stage? (Choose two.)


    > A. LIST
    > C. LS

1076. Which stages are created by default, with no need to use the CREATE STAGE command? (Choose two.)


    > D. Table stage
    > E. User stage

1077. While working with unstructured data, which file function generates a Snowflake-hosted file URL to a staged file using the stage name and relative file path as inputs?


    > A. BUILD_STAGE_FILE_URL

1079. Which command allows for continuous loading of data files as soon as they are available in a stage?


    > C. CREATE PIPE

1080. What is an advantage of using database roles instead of granting privileges on objects directly to a share in Snowflake?


    > C. More control over object-level access for different user groups

1081. What is the order of precedence (highest to lowest) of network policies when applied at the account, user, and security integrations layers?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. User, security integration, account

1082. Which type of Snowflake virtual warehouse provides 16 times the memory for each node, and is recommended for larger workloads like Machine Learning (ML) training?


    > D. A Snowpark-optimized warehouse

1083. Which common query issues can be identified by the Query Profile? (Choose two.)


    > B. Inefficient query pruning
    > D. Exploding joins

1084. In Snowflake, what allows users to perform recursive queries?


    > D. CONNECT BY

1085. A user wants to create objects within a schema but wants to restrict other users’ ability to grant privileges on these objects. What configuration should be used to create the schema?


    > B. Use a managed access schema.

1086. What is the MOST cost-effective way to resolve memory spillage in a virtual warehouse?


    > D. Convert to a Snowpark-optimized warehouse.

1087. What objects in Snowflake are supported by Dynamic Data Masking? (Choose two.)


    > A. Views
    > C. Tables

1088. A user has created a dashboard in Snowflake and wants to share it with colleagues. How can the dashboard be shared?


    > B. By using the share option within Snowsight

1089. When would Snowsight automatically detect if a target account is in a different region and enable cross-cloud auto-fulfillment?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* B. When using a private listing on the Snowflake Marketplace

1090. Which languages require that User-Defined Function (UDF) handlers be written inline? (Choose two.)


    > B. Javascript
    > E. SQL

1091. Which task privilege does a Snowflake role need in order to suspend or resume a task?


    > B. OPERATE

1092. What is a directory table in Snowflake?


    > B. An object layered on a stage that is used to store file-level metadata.

1093. What factors impact storage costs in Snowflake? (Choose two.)


    > A. The account type
    > C. The cloud region used by the account
    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1094. Which ACCOUNT_USAGE schema database role provides visibility into policy-related information?


    > B. GOVERNANCE_VIEWER

1095. How should clustering be used to optimize the performance of queries that run on a very large table?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. Assess the average table depth to identify how clustering is impacting the query.

1096. Which privilege must be granted by one role to another role, and cannot be revoked?


    > C. OWNERSHIP

1097. How can performance be optimized for a query that returns a small amount of data from a very large base table?


    > C. Use the search optimization service

1098. A column named “Data” contains VARIANT data and stores values as follows:
      {
      "Employee":{
      id:100,
      name:John,
      Location:"New Worek"
      }
      }
      How will Snowflake extract the employee’s name from the column data?


    > C. data:Employee.name

1100. Which command should be used to generate a single file when unloading data from a Snowflake table into a file?


    > C. SINGLE = TRUE

1105. Which type of workload traditionally benefits from the use of the query acceleration service?


    > B. Workloads that include on-demand data analyses

1107. When unloading data, which combination of parameters should be used to differentiate between empty strings and NULL values? (Choose two.)


    > C. FIELD_OPTIONALLY_ENCLOSED_BY
    > D. EMPTY_FIELD_AS_NULL

1108. Which role must be used to create resource monitors?


    > B. ACCOUNTADMIN

1109. What step does Snowflake recommend when loading data from a stage?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. Use the LOAD HISTORY function to view the status of loaded files.

1110. How can a user MINIMIZE Continuous Data Protection costs when using large, high-churn, dimension tables?


    > A. Create transient tables and periodically copy them to permanent tables.

1111. Which Snowsight feature can be used to perform data manipulations and transformations using a programming language?


    > C. Python worksheets

1112. In Snowflake's data security framework, how does column-level security contribute to the protection of sensitive information? (Choose two.)


    > D. Column-level security limits access to specific columns within a table based on user privileges.
    > E. Column-level security allows the application of a masking policy to a column within a table or view.

1113. How does Snowflake utilize clustering information to improve query performance?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* A. It prunes unnecessary micro-partitions based on clustering metadata.

1114. How can staged files be removed during data loading once the files have loaded successfully?


    > B. Use the PURGE copy option.

1115. What objects can be cloned within Snowflake? (Choose two.)


    > A. Schemas
    > D. Internal named stages

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1116. What can be used to process unstructured data?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. External functions

1117. Which type of workload is recommended for Snowpark-optimized virtual warehouses?


    > B. Workloads that have large memory requirements

1118. What is the benefit of using the STRIP_OUTER_ARRAY parameter with the COPY INTO [table] command when loading data from a JSON file into a table?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* B. It removes the outer array structure and loads separate rows of data

1119. A query containing a WHERE clause is running longer than expected. The Query Profile shows that all micro-partitions being scanned. How should this query be optimized?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* B. Add a clustering key to the table.

1120. Which access control entity in Snowflake can be created as part of a hierarchy within an account?


    > B. Role

1121. When an object is created in Snowflake, who owns the object?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. The current active primary role

1122. What is the MINIMUM Snowflake edition that must be used in order to see the ACCESS_HISTORY view?


    > B. Enterprise

1123. Which role is responsible for managing the billing and credit data within Snowflake?


    > B. ACCOUNTADMIN

1124. What can be used to identify the database, schema, stage, and file path to a set of files, and to allow a role that has sufficient privileges on the stage to access the files?


    > B. A file URL

1125. Which command is used to remove files from either external cloud storage or an internal stage?


    > B. REMOVE

1126. How does Snowflake recommend defining a clustering key on a high-cardinality column that includes a 15 digit ID numbered column, ID_NUMBER?


    > A. TRUNC(ID_NUMBER, -6)

1128. Which query types will have significant performance improvement when run using the search optimization service? (Choose two.)


    > B. Equality searches
    > D. Queries with IN predicates

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1129. Which Query Profile operator is considered a DML operator?


    > C. Merge

1130. Masking policies are created at what level in Snowflake?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. Schema

1132. What are type predicates used for?


    > C. Determining if a value in a VARIANT column is a particular data type

1133. Which table function is used to perform additional processing on the results of a previously-run query?


    > B. RESULT_SCAN

1134. Which actions can be performed using a resource monitor in Snowflake? (Choose two.)


    > D. Suspend a virtual warehouse when its credit usage reaches a defined limit.
    > E. Trigger a notification to account administrators when credit usage reaches a specified threshold.

1135. Which Snowflake native tool can be used to diagnose and troubleshoot network connections?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. SnowCD

1136. Why would a Snowflake user load JSON data into a VARIANT column instead of a string column?


    > C. A VARIANT column can be used to create a data hierarchy and a string column cannot

1137. How can a 5 GB table be downloaded into a single file MOST efficiently?


    > C. Set the SINGLE parameter to TRUE.

1138. Which security models are used in Snowflake to manage access control? (Choose two.)


    > A. Discretionary Access Control (DAC)
    > D. Role-Based Access Control (RBAC)

1139. Which Snowflake governance feature allows users to assign metadata labels to improve data governance and database access control?


    > C. Object tagging

1141. Which Snowflake function and command combination should be used to convert rows in a relational table to a single VARIANT column, and unload the rows into a file in JSON format? (Choose two.)


    > C. COPY
    > E. OBJECT_CONSTRUCT

1142. What Snowflake recommendation is designed to ensure that staged data is only loaded once?


    > C. Removing data files after loading

1143. Which privilege grants the ability to set a column-level security masking policy on a table or view column?


    > A. APPLY

1144. When sharing data in Snowflake, what privileges does a Provider need to grant along with a share? (Choose two.)


    > C. SELECT on the specific tables in the database.
    > D. USAGE on the database and the schema containing the tables to share.

1145. How can the Query Profile be used to troubleshoot a problematic query?


    > A. It will indicate if a virtual warehouse memory is too small to run the query.

1146. Which data type can be used for floating-point numbers without losing precision?


    > D. DOUBLE

1147. Which data sharing option allows a Snowflake user to set up and manage a group of accounts and offer a share to that group?


    > D. Data Exchange

1148. What kind of authentication do Snowpipe REST endpoints use?


    > B. Key-based

1149. What are the possible values within a METADATA$ACTION column in a Snowflake stream? (Choose two.)


    > A. INSERT
    > C. DELETE

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1150. What is the MINIMUM Snowflake edition that offers data protection for extremely sensitive data, such as Protected Health Information (PHI)?


    > C. Business Critical

1152. Which service or tool is a Command Line Interface (CLI) client used for connecting to Snowflake to execute SQL queries?


    > D. SnowSQL

1153. What Snowflake objects can contain custom application logic written in JavaScript? (Choose two.)


    > E. User-Defined Functions (UDFs)

1154. What is the MINIMUM Snowflake edition required to use the column-level security feature?


    > B. Enterprise

1155. Which command should be used to assign a key to a Snowflake user who needs to connect using key pair authentication?


    > D. ALTER USER jsmith SET RSA_PUBLIC_KEY='MIIBIjANBgkqh...';

1156. Secured Data Sharing is allowed for which Snowflake database objects? (Choose two.)


    > A. Tables
    > C. Secure views

1157. What optional properties can a Snowflake user set when creating a virtual warehouse? (Choose two.)


    > A. Auto-suspend
    > D. Resource monitor

1158. What is the purpose of the use of the VALIDATE command?


    > D. To see all errors from a previously run COPY INTO [table] statement

1159. Which function is used to unload a relational table into a JSON file?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. TO_JSON

1160. How can the ACCESS_HISTORY view in the ACCOUNT_USAGE schema be used to review the data governance settings for an account? (Choose two.)


    > A. Identify queries run by a particular user.
    > D. Identify objects that were modified by a query.

1161. Which command is used to unload data from a Snowflake table into a Snowflake stage?


    > C. COPY INTO [location]

1162. What should an account administrator do to help a user log into Snowflake, if the user cannot authenticate using Multi-Factor Authentication (MFA)?


    > A. Set DISABLE_MFA to TRUE for the user.

1163. Which command can be executed from a reader account?


    > D. COPY INTO [location]

1164. Which command line parameter value can be pre-specified as an environment variable in SnowSQL?


    > A. HOST

1166. Which Snowflake feature improves the performance of point lookup queries?


    > D. Search optimization service

1167. What is the impact of selecting one Snowflake edition over another? (Choose two.)


    > A. The edition will impact the unit costs for storage.

    > C. The edition will determine the unit costs for the compute credits.

1169. A Snowflake user wants to design a series of transformations that need to be executed in a specific order, on a given schedule. What Snowflake objects should be used?


    > B. Tasks

1170. Which command should be used to drop files from an internal or external stage?


    > C. REMOVE

1174. A network policy applied at the user level takes precedence over a network policy applied to what Snowflake object?


    > B. An account

1175. Which Snowflake storage object can be used to store data beyond a single session and will not incur Fail-safe costs?


    > D. Transient table

1177. What metrics will the SHOW TABLES command in Snowsight provide?


    > B. Active bytes

1178. An external stage, my_stage contains many directories, including one, app_files that contains CSV files. How can all the CSV files from this directory be moved into table my_table without scanning files that are not needed?


    > B. COPY INTO my_table FROM @my_stage/app_files PATTERN='.*[.]csv';

1179. Using which object-level parameters will help limit query processing and concurrency slowdowns? (Choose two.)


    > B. ENABLE_QUERY_ACCELERATION
    > E. QUERY_ACCELERATION_MAX_SCALE_FACTOR

1181. Which function will convert semi-structured data to a relational data representation?


    > B. FLATTEN

1182. What triggers the automated maintenance of a table's clustering key after it has been defined?


    > D. A Snowflake determination that the table will benefit from maintenance.

1183. Which Snowflake object will consume credits during automatic background maintenance?


    > D. Materialized view

1184. Snowflake users can create a resource monitor at which levels? (Choose two.)


    > C. Account level
    > E. Virtual warehouse level

1185. Which Snowflake objects can be secured to protect data privacy? (Choose two.)


    > C. Views
    > D. Materialized views

1187. Which resource monitor setting will cancel all active queries in a virtual warehouse when the threshold is met?


    > D. SUSPEND_IMMEDIATE

1188. What role should be used when creating a new user?


    > C. USERADMIN

1189. Which ACCOUNT_USAGE view will identify long-running queries?


    > C. QUERY_HISTORY

1190. When sharing data among multiple Snowflake accounts, what charges are incurred by a data consumer when viewing shared data using their own account?


    > B. Compute charges

1194. What step must be taken to ensure that a user can only access Snowsight from a specific location, or when working from home?


    > D. Add the user's IP address to the network policy allowed list.

1195. What actions will trigger a data pipe to load? (Choose two.)


    > C. Use of the insertFiles REST endpoint
    > E. Set the pipe parameter to auto-ingest

1196. What does a Query Profile metric that shows excessive spillage indicate?


    > A. Poor query optimization

1198. In a SPLIT_PART function, what will the returned value be if the partNumber is out of range?


    > B. An empty string

1200. What Snowflake features are recommended to restrict unauthorized users from accessing Personal Identifiable Information (PI)? (Choose two.)


    > A. Dynamic Data Masking
    > C. Secure views

1201. Which Snowflake keywords help retrieve data without the need to completely scan a table? (Choose two.)


    > D. SAMPLE
    > E. TABLESAMPLE

1202. A security review identified several roles that are no longer being used. Which of the roles can be dropped?


    > C. FINANCEADMIN

1204. How can a Snowflake user automate virtual warehouse operations for optimal credit consumption? (Choose two.)


    > A. Auto-resume when a query is in a queue.
    > E. Auto-suspend after a specified period of inactivity

1205. Which data protection feature should only be used when all other data recovery options have been attempted?


    > D. Fail-safe

1206. A single cluster virtual warehouse has no free resources. What will happen to new queries that are run against this warehouse?


    > C. The queries will be placed in a queue.

1207. How does the search optimization service improve query performance?


    > B. By creating a persistent data structure

1208. Use of what parameter will allow files to be loaded even if the file metadata has expired?


    > D. LOAD_UNCERTAIN_FILES = TRUE

1209. How can a Data Exchange Administrator provide a user with account access to a Data Exchange?


    > B. Add the user to the Data Exchange.

1210. Which features can be used with the Snowflake Standard edition? (Choose two.)


    > A. Materialized views
    > D. Fail-safe

1211. Which function will generate a URL that can be accessed by a non-Snowflake user?


    > A. GET_PRESIGNED_URL

1212. What are valid values for the FIELD_OPTIONALLY_ENCLOSED_BY option in the COPY INTO [location] command used during data unloading? (Choose two.)


    > A. Single quote character (')
    > D. NONE

1213. What identifiers are supported when creating a Snowflake account hostname? (Choose two.)


    > A. Cloud region
    > D. Account locator

1215. What kind of value does a User-Defined Function (UDF) return? (Choose two.)


    > D. Scalar
    > E. Tabular

1216. Which command can be performed on a Snowflake secure view?


    > A. SELECT

1217. Which database objects can be shared with Secure Data Sharing? (Choose two.)


    > D. External tables
    > E. Dynamic tables

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1218. When a transient table in Snowflake is dropped, what happens to the table?


    > A. The table is no longer available for use.

1219. A data provider needs to securely collaborate with data consumers who do not reside in the same region. What Snowflake sharing mechanism should be used?


    > B. Data Exchange

1220. A user needs to know the maximum value of a date field in a table, and runs the following query:

select max(o_orderdate) from ORDERS;

Which part of Snowflake architecture will this query use?

    > D. Compute

1222. When cloning a schema, which Snowflake object will not be included in the clone?


    > A. An external stage

1223. Which command will change the name of shared database role r1 to r4?


    > D. ALTER DATABASE ROLE d1.r1 RENAME TO d1.r4;

1224. What does the Remote Disk I/O statistic in the Query Profile indicate?


    > C. Time when the query processing was blocked by remote disk access.

1225. Use of which virtual warehouse or warehouse configuration will improve the performance of workloads that have large memory requirements, such as Machine Learning (ML) training using a stored procedure?


    > A. Snowpark-optimized warehouse

1226. Which role has the privileges to describe a share?


    > C. SYSADMIN

1227. This command is executed:

CREATE TABLE new_table CLONE existing_table COPY GRANT;

What will happen to the privileges of any cloned objects?

    > C. The clone will inherit all privileges except OWNERSHIP from the source object.

1228. Where does Snowflake store the data output from a query that was executed in the past 24 hours?


    > C. In the result cache layer

1229. What is the default authenticator while using the JDBC driver connection in Snowflake?


    > B. snowlake

1230. When will Snowflake charge credits for the use of the Cloud Services layer?


    > A. Credits will be charged whenever the Cloud Services layer is used.

1231. What is the primary purpose of using a masking policy in Snowflake?


    > A. To protect sensitive data from unauthorized access when queries are run.

1232. How can the performance of queries run on external tables be optimized?


    > C. Use the metadata cache

1233. What are the recommended alternative data types in Snowflake for unsupported large object data types such as BLOB and CLOB? (Choose two.)


    > C. BINARY
    > E. VARCHAR

1234. A network policy set at which level will override all other network policies?


    > B. User

1235. A company needs to share sales data with multiple marketing agency partners.

Which Snowflake data share mechanism is recommended for this use case?

    > C. A reader account

1236. Which role can create and manage Snowflake accounts?


    > C. ORGADMIN

1237. Which security feature is available in all Snowflake editions?


    > B. Object-level access control

1239. Which strings will be converted to TRUE using the TO_BOOLEAN() or CAST() functions when unloading data? (Choose two.)


    > D. on
    > E. yes

1240. Which authentication method requires access to a secure file that is only stored on the user's local device?


    > B. Key-pair authentication

1241. Which drivers or connectors are supported by Snowflake? (Choose two.)


    > C. Go Snowflake Driver
    > E. Snowflake Connector for Python

1242. If a source table is updated while cloning is in progress, what data will be included in the cloned table?


    > C. All data from the timestamp when the clone statement was initiated.

1243. The CUSTOMER table in the T1 database is accidentally dropped.

Which privileges are required to restore this table? (Choose two.)

    > B. OWNERSHIP privilege on the CUSTOMER table

    > E. CREATE TABLE privilege on the T1 database

1244. Which ACCOUNT_USAGE view can be used to identify the masking policy assigned to an object?


    > C. POLICY_REFERENCES

1245. A stream object will advance its offset when it is used in which statement?


    > B. INSERT

1246. Where is metadata management handled in Snowflake?


    > A. Cloud Services

1247. What does an integration between Snowflake and Microsoft Private Link or AWS PrivateLink support?


    > D. A secure, direct connection to Snowflake that does not use the internet.

1248. Which type of URL gives permanent access to files in cloud storage?


    > D. File URL

1249. Which Snowflake data governance feature supports resource usage monitoring?


    > C. Access history

1250. Which steps will help optimize query performance? (Choose two.)


    > A. Using the query acceleration service
    > B. Clustering a table

1251. Which functions can be used to identify the data type stored in a VARIANT column? (Choose two.)


    > B. IS_DATE_VALUE
    > D. IS_XML

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1252. What is the MINIMUM Snowflake edition that supports data sharing?


    > A. Standard

1253. Who can access the data published in a Data Exchange?


    > D. Only the users that the data provider has invited to the Data Exchange

1254. How can data be shared between two users who have different Snowflake accounts?


    > B. Create a share and ensure the proper role is assigned to the share.

1256. A user executed a SELECT query in Snowsight which returned a 1 GB result set. The user then downloads the files.

What will occur?

A. The result set will be successfully downloaded from Snowsight.
B. The result set will be automatically compressed and the data will be downloaded as individual files.
C. The download will fail because the result set needs to be broken up into files no greater than 50 MB before downloading.
D. The download will result in an error because the filters of the SELECT query need to be changed so that Snowsight returns a smaller result set.

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* A o B or C

1257. Which command can be used to unload data into an external named stage in Snowflake?


    > D. COPY INTO [location]

1258. Which file format option should be used when unloading data into a stage to create a CSV or a JSON file?


    > C. FILE_EXTENSION

1259. When creating a virtual warehouse, what setting should be used to avoid both over-provisioning resources and auto-scaling when there is increased concurrency?


    > D. ENABLE_QUERY_ACCELERATION = TRUE

1260. What is the MINIMUM Snowflake edition required to add masking policies to selectively mask plain-text data in a table or in view columns at query time?


    > B. Enterprise

1261. Which command can be used to determine if data from a file has been previously loaded?

> A. COPY_HISTORY

1262. What does Snowflake recommend when configuring the auto-suspend parameter for a virtual warehouse?


    > C. Enable auto-suspend to a low value to minimize credit consumption during inactivity.

1265. Which URL type should be used for custom applications that need to access unstructured data files?


    > C. Pre-signed URL

1266. When would creating and using a standard view be preferable to using a materialized view?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. The view results change often.

1267. When using a direct share, what privileges does a role need to control access to the objects that are in a share that is using database roles? (Choose two.)


    > D. CREATE SHARE
    > E. CREATE DATABASE

1268. What actions can be performed by consumers of shared databases? (Choose two.)


    > C. Query Time Travel data on the database.
    > E. Query data from the objects in the database

1270. At what level is the ALLOW_CLIENT_MFA_CACHING parameter configurable in Snowflake?


    > C. Account

1271. How can data be securely shared across regions and cloud platforms in Snowflake?


    > B. Use replication.

1272. What factors affect how many credits will be charged for virtual warehouse usage? (Choose two.)


    > D. Size of the warehouse
    > E. Length of time the warehouse runs

1273. What privilege is required to view the load statistics on a virtual warehouse?


    > C. MONITOR

1274. Which command will indicate whether a materialized view is being used in a query?


    > C. EXPLAIN

1275. A size X-Small virtual warehouse ran for 90 seconds, and was shut down. The warehouse was then run for another 30 seconds before being shut down again.

How many seconds will be billed?

    > C. 150 seconds

1276. Which virtual warehouse configuration is recommended specifically for a steady workload that has no execution lag?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* D. MIN_CLUSTER_COUNT = 1 -

MAX_CLUSTER_COUNT = 3

1277. Which role allows a Snowflake user to view table-level storage utilization information from the TABLE_STORAGE_METRICS view by default?


    > A. ACCOUNTADMIN

1278. This statement is run:

SELECT { 'key' : { 'subkey': 'value' }} mycolumn;

What notations will retrieve the 'value' from the VARIANT column? (Choose two.)

    > B. mycolumn.key:subkey
    > E. mycolumn:key:subkey

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1279. Which multi-cluster virtual warehouse setting will help process queued queries as quickly as possible?


    > D. Auto-scale mode

1280. Which Snowflake tool provides detailed execution statistics of a query with no cost to the user?


    > A. Query Profile

1281. How can a Snowflake user access near real-time metrics that can be used to identify queries affected by disk spilling?


    > B. Review the history section of the Query Profile.

1282. Which table type is used in the file processing pipeline to process unstructured data in Snowflake?


    > B. Directory

1283. Which metrics in the QUERY_HISTORY Account \_Usage View can be used to assess the pruning efficiency of a query? (Choose two.)


    > B. PARTITIONS_TOTAL
    > E. PARTITIONS_SCANNED

1284. How should a data provider securely share Snowflake objects with a data consumer who does not have a Snowflake account?


    > C. Create a reader account for the consumer.

1285. When unloading Snowflake relational data to a Parquet file format, why should the PARTITION BY clause be used?


    > D. It will optimize query performance by filtering relevant partitions without scanning the entire dataset.

1286. How can a user access information about a query execution plan without consuming virtual warehouse compute resources?


    > A. Use the EXPLAIN function.

1287. If a query is being used to unload a 1 TB table into a stage, which DML operator will be shown in the Query Profile?


    > C. COPY

1288. At what levels can network policies be defined in Snowflake? (Choose two.)


    > A. User
    > B. Account

1289. A Snowflake table that is loaded using a Kafka connector has a schema consisting of which two VARIANT columns? (Choose two.)


    > B. RECORD_CONTENT
    > C. RECORD_KEY

1290. When working with table MY_TABLE that contains 10 rows, which sampling query will always return exactly 5 rows?


    > C. SELECT * FROM MY_TABLE SAMPLE (5 ROWS);

1301. Which query metric can be used to monitor the health of a large table?


    > A. Clustering depth

1302. What function should be used to convert JSON NULL values to SQL NULL values when loading data into a Snowflake table?


    > B. STRIP_NULL_VALUE

1303. What is the recommended way to insert a VARIANT value into a Snowflake table?


    > B. Use the TO_VARIANT function in the INSERT statement.

1304. Which process does Snowflake follow when a stored procedure with owner's rights is called within a session?


    > B. The owner can set the caller's session variables.

1308. Which configuration of the function PARSE_JSON( [expr] ) will retrieve a valid SQL NULL value?


    > B. SELECT parse_json('null')

1309. What is the MINIMUM Snowflake edition that supports the periodic rekeying of encrypted data?


    > B. Enterprise

1311. Which Query Profile operator provides information on pruning efficiency?


    > A. TableScan

1312. What metadata is stored for each micro-partition? (Choose two.)


    > A. The number of distinct values
    > D. The range of values for each of the columns in the full table

1313. Which role has the HIGHEST precedence among roles that will serve as the owners of securable objects?


    > D. ACCOUNTADMIN

1314. How is data protected in Snowflake throughout its lifecycle? (Choose two.)


    > C. Snowflake automatically encrypts data locally before copying the data to the cloud over an encrypted connection.
    > D. Snowflake automatically rotates keys pairs regularly, using a hierarchical key model stored in a hardware security module

1315. Which Snowflake virtual warehouse configuration enables horizontal scaling?


    > B. Increasing the MAX_CLUSTER_COUNT.

1316. Which Snowflake objects can execute both DDL and DML statements?


    > B. Stored procedures

1317. Which object consumes Snowflake credits for its maintenance?


    > A. Materialized view

1318. When connecting to Snowflake using SnowSQL, what are ways to explicitly specify the password? (Choose two.)


    > D. Enter through an interactive prompt
    > E. Specify using SNOWSQL_PWD environment variables

1319. A team is developing a machine learning model by training on the latest Snowflake features. The training is taking much longer than expected to complete.

Which step will accelerate the model training?

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* C. Use a Snowpark-optimized virtual warehouse.

1320. Which object can be shared using Secure Data Sharing?


    > A. Secure view

1321. How is Single Sign-On (SSO) authentication used in Snowflake?


    > C. SSO is an authentication method that allows a user to sign into multiple applications with a single set of credentials.

1322. Which clause is used to define a function that may return different values for different rows?


    > D. VOLATILE

1323. In Snowflake, where can query pruning information statistics be identified?


    > A. Partitions scanned

1324. How does the authorization associated with a pre-signed URL work for an unstructured file?


    > A. Anyone who has the URL can access the referenced file for the life of the token.

1325. What will happen if the volume of data stored in Snowflake increases over time?


    > D. The warehouse performance and size will not be affected when the volume of stored data increases.

1326. What can a reader account user do when accessing shared data? (Choose two.)


    > B. Execute secure User-Defined Functions (UDFs).
    > D. Select data from secure views.

1327. What is a fundamental characteristic of Snowflake micro-partitions?


    > D. Once established, they cannot be changed

1328. What happens when a multi-cluster virtual warehouse is resized?


    > C. The new size applies to all clusters within that warehouse configuration.

1330. Which Snowflake objects use storage? (Choose two.)


    > A. Regular table
    > D. Materialized view

1331. What type of policy states that each object within Snowflake has a unique owner who can grant access to that object?


    > B. Discretionary Access Control (DAC)

1332. Which Snowflake multi-cluster virtual warehouse scaling policy or mode will MINIMIZE query queuing by prioritizing the startup of additional clusters?


    > D. Maximized mode

1333. Which default warehouse configuration has the highest precedence whenever a new session is created by a user?


    > C. Default warehouse specified on a CLI or in drivers/connectors parameters

1334. What type of authentication is recommended when creating a Snowflake service account that will connect to a third-party application?


    > B. Key-pair authentication

1335. Which type of query would benefit from enabling the query acceleration service on the virtual warehouse?


    > D. Queries that contain a high cardinality GROUP BY expression

1336. Which table function will return the output of a previously-run command?


    > D. RESULT_SCAN

1337. How can a relational table be unloaded into a JSON file?


    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* B. Use the COPY INTO [location] command with the file_format set as JSON.

1338. When do Snowflake object owners lose their ability to make grant decisions?


    > C. When the object is part of a managed access schema

1339. Which command allows a user to unload data from a Snowflake database table into one or more files in a Snowflake or external stage?


    > D. COPY INTO [location]

1340. hich Snowflake feature enables loading data from cloud storage as soon as files are available in a stage?


    > C. Snowpipe

1341. Which JSON paths are considered to be equivalent in Snowflake? (Choose two.)


    > A. src['customer']['EMAIL']
    > B. src['CUSTOMER']['Email']

    > \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*

1343. What happens when a table or schema with a standard retention period is dropped?


    > D. The object is retained for the data retention period.

1344. When cloning tables, which INFORMATION_SCHEMA view will show different columns for owned storage and referenced storage?


    > C. TABLE_STORAGE_METRICS

1345. Based on a review of a Query Profile, which scenarios will benefit the MOST from the use of a data clustering key? (Choose two.)


    > A. A column that appears most frequently in ORDER BY operations
    > B. A column that appears most frequently in WHERE operations

1346. When working with dimension tables that change frequently, what is the recommended way to manage costs?


    > B. Make the dimension tables transient with a retention period of 0 days, and backup the table daily to a permanent table. Delete all but the latest backup.

1347. What Snowflake privilege should be granted to allow a non-ACCOUNTADMIN access to billing information?


    > B. MONITOR USAGE

1348. A stream can be created on which Snowflake objects to record data manipulation language (DML) changes? (Choose two.)


    > B. Standard tables
    > C. Standard views

1349. When creating a file format to load JSON data into Snowflake, what command will remove brackets ([]) from the data?


    > D. STRIP_OUTER_ARRAY = TRUE

1350. What virtual warehouse feature or setting will reduce the performance impact when running larger-than-average queries, by offloading portions of the query processing work to shared compute resources?


    > B. Using the query acceleration service

1351. Which schema-level objects allow the user to periodically perform an action under specific conditions, based on data within Snowflake?


    > A. Alerts

1352. Which privilege must be granted to show data categories in a Data Exchange?


    > A. MONITOR PRIVILEGE

1.  Which layer of the Snowflake architecture is responsible for managing user authentication, access control, and query optimization?

    > Service Layer / Cloud Service Layer

2.  Which Snowflake edition offers features such as multi-cluster warehouses and up to 90 days of time travel?

    > Enterprise

3.  What is the minimum Snowflake edition that provides multi-cluster warehouses and up to 90 days of Time Travel?

    > Enterprise

4.  What is the duration for which the query result cache remains valid before it is reset?

    > 24 hours

5.  Snowflake: How are virtual warehouse credits charged?

    > Per second, with a 60 sec minimum

6.  Snowflake offers multiple editions. Which are they?

    > Standard, Enterprise, Business Critical, VPS.

7.  State True or False : Each successive edition builds on the previous edition through the addition of edition-specific features and/or high levels of of service

    > True

8.  A snowflake account can be hosted on which platforms?

    > AWS, Azure, GCP

9.  Does credit cost depend on snowflake edition?

    > Yes

10. Does extendable time travel work for all edition?

    > No. Does not work for standard edition

11. State True or False : All snowflake features are same regardless of cloud platform and region

    > True. Features are different based on edition only

12. State True or False : Each snowflake account hosted in a single region

    > True

13. State True or False : Snowflake edition can be upgraded with the help of snowflake support team

    > True

14. Snowflake edition, cloud provider and region can be found from the classic / legacy web UI
    > True
15. Snowflake provides two types of storage. On-demand & Capacity. Capacity storage comes with discounted pricing and needs up-front commitment

    > True

16. What happens when a running warehouse is resized in Snowflake?

    > Queued queries will execute at the new size while running queries continue at the current size

17. Which of the following features is exclusive to the Business Critical Edition of Snowflake, enhancing its security and compliance capabilities?

    > Data encryption everywhere

18. What is the primary function of the Service Layer in Snowflake's architecture?

    > To accept SQL requests, coordinate queries, and manage transaction results

    ```md
    To store raw data in its original format -

    To manage user roles and permissions - Service layer

    To perform data unloading and loading operations - Query Processing layer
    ```

19. Which of the following features is NOT included in the Standard Edition of Snowflake?

    > Multi-cluster warehouse

20. Each week snowflake deploys how many releases?

    > two Planned releases. Full release & Planned Release

21. What are the names of Snowflake's founders?

    > Thierry and Benoit

22. What were the founders trying to accomplish initially?

    > Re-Architect data storage, in the cloud, from scratch

23. According to the founders, Snowflake's architecture supports:

    > - Fault isolation
    > - Elastic Compute/Adapting based on demand
    > - Cost based on usage, not version licenses
    > - Infinitely scalable storage
    > - Performance isolation

24. The area where we write sql queries is called

    > SQL Entry Pane

25. Data can be downloaded in which format(s) from result pane?

    > TSV
    > CSV

26. Can Data be downloaded from data preview pane?

    > No

27. Downloading data from web interface need virtual warehouse?

    > No.

    ```md
    Running Query needs virtual warehouse. Not downloading
    ```

28. What is the download limit in classic Web UI?

    > 100 mb

29. Account & Notification tabs are available to which role?

    > ACCOUNTADMIN

30. Account tab is available to which role?

    > ACCOUNTADMIN & SECURITYADMIN

31. Query history tab holds queries executed for how many days?

    > 14 days

32. Query history can be accessed from result pane?

    > True

33. The left bar is called -

    > Navigation tree

34. The architecture of Snowflake is

    > shared data

35. Are databases stored within warehouses? Are warehouses stored within databases?

36. Does Snowflake store data with

    - compression?
    - Encryption?
    - Both?

    Ans : Both

37. When a warehouse is resized, what queries are affected? Only current? Current and
    subsequent? Only subsequent?

        Ans : Only subsequent

38. Costs are broken down into what two major categories?

39. Storage costs are based on the daily average of stored data. Is this based on the data's compressed size or uncompressed size?

        >  compressed size

40. What things aren't required because Snowflake is a true SaaS solution?

        > No hardware to purchase or configure.

        > No maintenance upgrades or patches to install.

        > Transparent releases don't require user intervention.

41. Can Snowflake be hosted on a company's internal cloud? What on-premise options are offered by Snowflake?

        > No

42. Can Snowflake be purchased for installation on a company's internal servers or Virtual Private Cloud(VPC)?

        > No

43. Snowflake uses MPP compute clusters. Are these called Virtual Data Marts? or Virtual Warehouses?

44. Does Snowflake recommend only running no more than 2 warehouses simultaneously to avoid contention? 5?

45. Are Snowflake Data Warehouses like Data Marts in that each one is assigned to work on a subset of the data stored in the account?

46. Which installment option versions of Snowflake are available?

    - A. Microsoft Cloud Native Accounts
    - B. Snowflake-Hosted Accounts (on Amazon cloud infrastructure)
    - C. Hybrid On-Premises + Cloud Installation
    - D. Snowflake-Hosted Accounts (on Google Cloud Platform infrastructure)
    - E. On-Premises Custom Installation
    - F. Snowflake-Hosted Accounts (on Azure cloud infrastructure)

            > B. Snowflake-Hosted Accounts (on Amazon cloud infrastructure),
            > D. Snowflake-Hosted Accounts (on Google Cloud Platform infrastructure),
            > F. Snowflake-Hosted Accounts (on Azure cloud infrastructure)

47. What are data storage cost calculations based on in Snowflake?

    - Uncompressed Size
    - Compressed Size
    - Amount Stored on Last Day of Month
    - Amount Stored on First Day of Month
    - Amount Stored - Daily Average

            > Compressed Size,
            > Amount Stored - Daily Average

48. Snowflake compute costs depend on which of the following?

    - The number of rows returned in queries.
    - The amount of time warehouses have run.
    - The total number of warehouses in the account.
    - The sizes of running warehouses.

            > The amount of time warehouses have run
            > The sizes of running warehouses.

49. How often does Snowflake release new features?

Ans : Weekly

17. What common tasks for traditional on-premises database and IT staff are not required with Snowflake?

    - Maintaining metadata
    - Maintaining statistics
    - Maintaining the physical security of a server room (key cards, door locks, etc.)
    - Maintaining database objects

            > Maintaining metadata,
            > Maintaining statistics,
            > Maintaining the physical security of a server room (key cards, door locks, etc.)

1.  COPY INTO `<table>` is a `____` statement

    > DML

        COPY INTO statement manipulates the data in a table so it is a DML statement

1.  MERGE is a `____` statement

    > DML

        MERGE statement manipulates the data in a table so it is a DML statement

1.  Each database belongs to `____` Snowflake account(s)

    > A single

1.  Which installment option versions of Snowflake are available?

    - A. Microsoft Cloud Native Accounts
    - B. Snowflake-Hosted Accounts (on Amazon cloud infrastructure)
    - C. Hybrid On-Premises + Cloud Installation
    - D. Snowflake-Hosted Accounts (on Google Cloud Platform infrastructure)
    - E. On-Premises Custom Installation
    - F. Snowflake-Hosted Accounts (on Azure cloud infrastructure)

      > B. Snowflake-Hosted Accounts (on Amazon cloud infrastructure),
      > D. Snowflake-Hosted Accounts (on Google Cloud Platform infrastructure),
      > F. Snowflake-Hosted Accounts (on Azure cloud infrastructure)

1.  Which ONE of the following terms BEST describes Snowflake's Architecture?

    - A. Shared Disk
    - B. Shared Nothing
    - C. Shared Data
    - D. Shared Memory

      > Shared Data

1.  Which of the following terms or phrases can also be used to describe Snowflake?

    - Native SQL
    - Hybrid Columnar
    - Built from the ground up for the cloud
    - Hadoop-Compliant
    - Multi-cluster
    - Oracle derived

      > Native SQL
      > Hybrid Columnar
      > Built from the ground up for the cloud
      > Multi-cluster

1.  Which statements are true about storage relationships?

    - Snowflake Tables are stored within Schemas
    - Snowflake Databases are stored within Warehouses
    - Snowflake Warehouses are stored within Data Marts
    - Snowflake Schemas are stored within Warehouses
    - Snowflake Warehouses are stored within Databases
    - Snowflake Schemas are stored within Databases

      > Snowflake Tables are stored within Schemas
      > Snowflake Schemas are stored within Databases

1.  Among the options listed, which is not a valid Snowflake Warehouse Size?

    > XXS

1.  As part of release process, snowflake does not move all accounts to release at the same time and follows a staged approached. Select the stage which is named as early access?

    > Stage - 1

         Stage 1 is also known as early access and designated for enterprise ( or higher) edition of snowflake accounts

1.  As part of release process, snowflake does not move all accounts to release at the same time and follows a staged approached. Select the stage which is named as regular access?

    > Stage - 2

         Stage -2 is also know as regular access and designed for Standard accounts

1.  All ingested data stored in snowflake tables is encrypted using `____` strong encryption

    > AES-256

         All files stored in internal stages for data loading & unloading operations is automatically encrypted using AES-256 strong encryption

1.  The 3rd party tools and technologies, as well as the snowflake provided clients is classified as `______`

    > Snowflake Ecosystem tool

1.  Snowflake can run private as well as hosted environment?

    > False

         Snowflake can completely run on **CLOUD** environment. All components of snowflake's service can run in PUBLIC infrastructure.

1.  When data is loaded into snowflake, it stored this optimized data into cloud storage

    > True

         When data is loaded into snowflake, snowflake recognizes that data into its internal optimized, compressed,  columnar format. Snowflake stores this optimized data in cloud storage.

1.  Customers cannot see or directly access the data objects that snowflake stores, they can only do so through SQL query operations that are carried out using snowflake

    > True

        All the data or objects stored are accessible via SQL statements

1.  Query execution is performed in Processing layer. Each virtual warehouse is an independent compute cluster that does not share compute resources with other virtual warehouse

    > True

        Compute layer or Processing layer does not share compute resources with other virtual warehouse

1.  The cloud service layer is a collection of services that co-ordinate activities across snowflake. The cloud services layer also runs on compute instances provisioned by snowflake from cloud provider.

    > True

1.  Only standard edition of snowflake can be hosted all three major cloud providers (AWS, Azure, GCP), higher edition of snowflake can only be in AWS.

    > True

1.  A behavior change, applied by snowflake as part of weekly or monthly release cycle, is defined as any change to existing that returns different results from before and may impact customer code or workloads.

    > True

1.  The stage approach only applies to the full releases of snowflake. For patch releases which includes only fixes, all accounts (standard & higher) are moved on the same day

    > True

        Patch release which includes fixed are moved in the same day for all accounts

1.  Snowflake puts a hard limit on number of databases. You can create only 10,000 databases in a snowflake instance

    > False

        Snowflake does not limit the number of databases.

        You can create or the number of schemas you can create within a database.

        Snowflake also does not limit the number of tables you can create in a schema

1.  A snowflake user can configure multi-factor authentication(MFA) through the snowflake Web-UI

    > True

1.  What is one disadvantage of the shared disk architecture? Choose one correct value.

    > The storage is potentially a single point of failure

1.  What is one disadvantage of the shared nothing architecture? Choose one correct value.

    > Storage and compute is tightly coupled

1.  What makes Snowflake a “cloud native” product? Choose one correct value.

    > Snowflake was designed to make use of the unique capabilities of the cloud

1.  Snowflake implements ANSI standard SQL. True or false?

    > True

1.  Which type of cloud computing service is Snowflake? Choose one correct value.

    > SaaS

1.  Users can SSH into the compute instances which make up a virtual warehouse. True or false?

    > False

1.  What type of data storage format does Snowflake store table data in? Choose one correct value.

    > Columnar

1.  Which statement is incorrect regarding snowflake editions? Choose one correct value.

    > Virtual private snowflakes allows the user to host a deployment of snowflake on their on-premise infrastructure

1.  The object container hierarchy exists in what order? Choose one correct value.

    > Organization -> Account -> Database -> Schema

1.  All objects are individually securable. True or false?

    > True

1.  Snowflake uses the following access control schemes: Role Based Access Control (RBAC) and \***\*\_\_\_\*\***.

    > Discretionary Access Control (DAC)

1.  Which system-define role is it recommended to assign custom roles to? Choose one correct value.

    > SYSADMIN

1.  If the user property DISABLE_MFA was set to true, the user would need to re-enroll to use multi-factor authentication again. True or false?

    > True

1.  Network policies currently support which type of IP address? Choose one correct value.

    > IPv4

1.  Key rotation is the practice of transparently replacing existing account and table encryption keys every \_\_ number of days. Choose one correct value.

    > 30

1.  Only standard views can be designated as secure. True or false?

    > False

    ```md
    Both standard and materialized views can be designated as secure.
    ```

1.  The ACCOUNT_USAGE share contains a database called SNOWFLAKE. The views in this database are used to provide fine-grained metrics at the account and object level. What is the maximum number of months data in these views available for? Choose one correct value.

    > 12

1.  By default, which system-define role can access the SNOWFLAKE database? Choose one correct value.

    > ACCOUNTADMIN

1.  Account usage views record dropped objects. True or false?

    > True

1.  If the role ACCOUNTADMIN was currently active, what would a user see issuing a query that included an email column with the below column masking policy applied to it?

```sql
CREATE MASKING POLICY EMAIL_MASK AS (VAL STRING) RETURN STRING ->

  CASE

      WHEN CURRENT_ROLE() IN ('ADMIN') THEN VAL

      WHEN CURRENT_ROLE() IN ('DEVELOPER') THEN REGEXP_REPLACE(VAL, '.+@', '*****@')

  ELSE '*********'

      END;
```

    > A fully masked email

21. What is a virtual Warehouse? Choose one correct value.

    > A virtual warehouse is a named abstraction for one or more compute nodes

22. The following command is permitted when interacting with a Virtual Warehouse: ALTER WAREHOUSE DE_VW SET WAREHOUSE_SIZE=LARGE. True or false?

    > True

23. If you were to keep a L virtual warehouse active for 4 hours, how many credits would it cost? Choose one correct value.

    > 32

    ```md
    A large Virtual Warehouse costs 8 Snowflake credits per hour while its in the started state.
    ```

24. What data type does the virtual warehouse property AUTO RESUME take? Choose one correct value.

    > BOOLEAN

25. A Virtual warehouse can only be scaled up manually. True or false?

    > True................Scaling up is the process of manually resizing a virtual warehouse via an ALTER WAREHOUSE command.

26. What is the function of the initially suspend property of a virtual Warehouse? Choose one correct value.

    > It specifies if a virtual warehouse should be suspended immediately after it's created

27. What will happen to existing queries if the virtual warehouse executing them is resized? Choose one correct value.

    > Existing queries are not impacted by a virtual warehouse resize

28. What does it mean to scale up a virtual warehouse? Choose one correct value.

    > Increasing the size of a virtual warehouse

29. What does the MIN_CLUSTER_COUNT specify when creating a multi-cluster warehouse? Choose one correct value.

    > The minimum number of warehouse that make up a multi-cluster warehouse

30. The total credit cost of a multi-cluster warehouse is the sum of all the individual running warehouses that make up that cluster. True or false?

    > True

31. What are the potential implications of setting AUTO_RESUME = TRUE on a warehouse in Snowflake?

32. What is the primary purpose of the data cache in Snowflake?

33. What is the primary function of the Result Cache in Snowflake?

<!-- UDEMY -->

1.  The COPY INTO <table> statement does NOT require a virtual warehouse to run. True or false?

    > False

2.  Virtual warehouses are billed on a per second basis. What is the minimum number of seconds a virtual warehouse is billed for? Choose one correct value.

        > 60

3.  A schema cannot be cloned. True or false?

        > False

4.  Which layer of the Multi-cluster Shared Data Architecture handles user authentication? Choose one correct value.

    > Services.

5.  Why would a materialized view be used? Select all that apply.

    > Materialized views make complex queries that are commonly executed readily available.

    > Materialized views can be created on top of external tables to improve their query performance.

6.  How would a user choose the size of a virtual warehouse? Choose one correct value.

    > Experimenting with a representative query of a workload on a variety of virtual warehouse sizes to find the correct fit that matches desired run-times.

7.  What do you configure a SHARE object with? Choose two correct values.

    > Object privileges.
    > Account identifiers.

8.  Which system-defined role is it recommended to assign custom roles to? Choose one correct value.

    > SYSADMIN

9.  The ACCOUNTADMIN can perform the same functions as the SECURITYADMIN, SYSADMIN & ORGAMIN. True or false?

    > False

10. How many database objects can a data provider add to a SHARE object? Choose one correct value.

    > Unlimited

11. Which Snowflake object would be ideal to schedule an execution to refresh a secondary database for replication? Choose one correct value.

    > Task

12. As a data engineer I want to create a file URL that is only valid for 24hours. Which file function would I use? Choose one correct value.

    > BUILD_SCOPED_FILE_URL

13. Which of the following values are Snowflake editions? Choose two correct values.

    > Standard
    > Enterprise

14. To reuse the results cache which of the following requirements must be met? Select all that apply.

    > The role executing the query must have the necessary access privileges for all the tables used in the cached query when executing a SELECT.

    > The new query exactly matches the cached query.

15. Which type of view bypasses some query optimizations to improve data security? Choose one correct value.

    > Secure

16. Once a data provider creates a share object, what two operations must they perform next to ensure a data consumer can read the shared data?

    > Grant privileges on database objects to share & add consumer account(s) to share.

17. If the query profile indicates queries are regularly spilling to remote storage what are the recommended solutions? Select all that apply.

    > Increase the size of the Virtual Warehouse.

    > Process data in smaller batches.

18. Time Travel is not possible on transient tables. True or false?

    > False

19. Micro-partitions can be modified once they have been created. True or false?

    > False

20. Of the following options which is the most accurate definition of a materialized view? Choose one correct value.

    > Stores results of a query definition and periodically refreshes its data.

21. Snowflake partitions files loaded into Snowflake automatically. True or false?

    > True

22. You can execute commands as the ACCOUNTADMIN using the SnowSQL CLI tool. True or False?

    > True

23. User defined functions can NOT be executed in the context of another statement. For example, in a SELECT statement. True or false?

    > False

24. Which properties are not available to a file format object of type CSV? Select all that apply.

    > STRIP_OUTER_ARRAY

    > STRIP_NULL_VALUES

25. Which of the following locations is data storage calculated based on the on-disk bytes? Choose three correct values.

    > Internal stages.

    > Database tables including time travel & fail-safe.

    > Materialized views.

26. Snowflake uses the following access control schemes: role based access control (RBAC) and \***\*\_\*\***. Choose one correct value.

    > Discretionary Access Control (DAC)

27. What is the maximum number of Time Travel days for a table of the permanent type? Choose one correct value.

    > 90

28. The account usage share contains a database called SNOWFLAKE. The views in this database are used to provide fine-grained metrics at the account and object level. What is the maximum number of months data in these views available for? Choose one correct value.

    > 12

29. Which queries would not require the use of a Virtual Warehouse and instead would make use of the metadata cache? Select all that apply.

    > SELECT COUNT(\*) FROM EMPLOYEE;

    > DESCRIBE TABLE EMPLOYEE;

30. Which query would result in an error when parsing a column of type VARIANT given the following JSON:

    ```json
    {
    “employee” : {
    “name” : “Jason Rojas”,
    “_id” : “UNX789544”
    },

    “joined_on” : “10-09-2019”,
    “skills” : [“Java”, “Kotlin”, “Android”]
    }
    ```

Choose one correct value.

    > SELECT SRC:employee.Name FROM EMPLOYEES;

31. What does each database created in an account automatically include? Choose one correct value.

    > Information schema.

32. What is the recommended maximum number of columns (or expressions) defined per clustering key? Choose one correct value.

    > 3 or 4

33. The following query can make use of the results cache: SELECT NAME, EMP_ID, CURRENT_TIME() FROM EMPLOYEE. True of false?

    > False

34. Which function can be used to automatically detect a schema definition? Choose one correct value.

    > INFER_SCHEMA()

35. How many accounts can a data consumer share a shared database with? Choose one correct value.

    > 0

36. What is the default compression format used when unloading files from Snowflake using the GET command? Choose one correct value.

    > GZIP

37. Which sentence most accurately describes what a Virtual Warehouse is? Choose one correct value.

    > A Virtual warehouse is a named abstraction for one or more compute nodes.

38. Which system function is called to retrieve clustering metadata for a column or columns? Choose one correct value.

    > system$clustering_information

39. Which INSERT query would return an error? Choose one correct value.

    > INSERT INTO TABLE MY_TABLE (ID, NAME) SELECT ‘001’, ‘Irene Adler’, ‘10/10/1976’;

40. What’s the maximum number of days a user could set the table property DATA_RETENTION_TIME_IN_DAYS to for a transient table on a business critical edition Snowflake account? Choose one correct value.

    > 1

41. What is the definition of Tri-secret secure? Choose one correct value.

    > A composite encryption key to encrypt data files made up a user provider key and a Snowflake key.

42. If enabled, periodic rekeying happens every \_\_\_ months. Choose one correct value.

    > 12

43. Natural clustering is determined by the order in which data is loaded. True or false?

    > True

44. What is the query to remove a virtual warehouse? Choose one correct value.

    > DROP WAREHOUSE MY_WAREHOUSE;

45. What level of cardinality is it recommended a column have when selected in a query that makes use of a GROUP BY? Choose one correct value.

    > Low cardinality.

46. Network policies currently support which type of IP address? Choose one correct value.

    > IPv4

47. If the PURGE copy option were set to TRUE what would happen to data files that are successfully loaded into Snowflake from an external stage? Choose one correct value.

    > They would be removed from the external stage.

48. What is the function of the AUTO_SUSPEND property of a Virtual Warehouse? Choose one correct value.

    > Specifies the number of seconds of inactivity after which a warehouse is automatically suspended.

49. Every securable object is owned by a single role. True or false?

            > True

50. Filters should be used as \***\*\_\*\*** as possible. Choose one correct value.

        > early

51. How many geographic regions in a cloud platform can a Snowflake account be deployed into? Choose one correct value.

        > 1

52. Users can SSH (Secure Shell) into the compute instances which make up a Virtual Warehouse. True or false?

        > False

53. What attributes make Snowflake a SaaS solution? Choose two correct values.

        > No hardware to manage.
        > Pay for what you use pricing plan.

54. Automatic clustering improves performance on queries that include which of the following constructs? Select all that apply.

        > JOIN
        > WHERE

55. On which version of Snowflake is Secure Data Sharing not available? Choose one correct value.

        > Virtual Private Snowflake (VPS)

56. What is the purpose of the TYPE option when creating a file format object? Choose one correct value.

        > Specifies the type of file the file format object will be configured to parse.

57. When is a table stage not appropriate to use for data loading? Select all that apply.

    > When a single user wants to load data into multiple tables.

    > When multiple users want to load data into multiple tables.

58. Which SQL extensions did Snowflake add for use with the Time Travel feature? Select all that apply.

        > AT
        > UNDROP
        > BEFORE

59. Which languages can be used to develop a User Defined Function (UDF)? Choose four correct values.

        > JavaScript
        > SQL
        > Python
        > Java

60. Which cloud platforms can a Snowflake account be hosted in? Choose three correct values.

        > Amazon Web Services (AWS)
        > Google Cloud Platform
        > Microsoft Azure

61. Which configuration of min_cluster_count & max_cluster_count would put a muti-cluster warehouse in maximized mode? Choose two correct values.

        > MIN_CLUSTER_COUNT=2 & MAX_CLUSTER_COUNT=2
        >  MIN_CLUSTER_COUNT=4 & MAX_CLUSTER_COUNT=4

62. Materialized views contribute to both compute and storage costs. True or false?

        > True

63. Which semi-structured data formats do Snowflake natively store and query? Select all that apply.

        > PARQUET
        > ORC
        > XML
        > JSON
        > AVRO

64. Which symbols are used when referencing a table stage via SQL? Choose one correct value.

        > @%

65. Data loading typically requires the use of a XXL Virtual Warehouse. True or false?

        > False

66. Databases are not required to have a unique identifier. True or false?

        > False

67. Which symbols are used when referencing a user stage via SQL? Choose one correct value.

        > @~

68. What is the function of a row access policy? Choose one correct value.

        > Restricting which rows are returned in a query.

69. Which objects are schema-level objects? Select all that apply.

        > Stored Procedure.
        > Table
        > Stream

70. What is the recommended compressed file size when loading data into Snowflake? Choose one correct value.

        > 100-250mb

71. A Snowflake user creates a clone of a 'TABLE_A' and names it 'TABLE_B'. When new records are inserted into 'TABLE A' what is expected to happen to 'TABLE B'? Choose one correct value.

        > The inserted records do not show at all in TABLE B.

72. What is the default value for the table property DATA_RETENTION_TIME_IN_DAYS for an account on the enterprise edition of Snowflake? Choose one correct value.

        > 1

73. What is the process of eliminating unrequired micro-partitions called during a query? Choose one correct value.

        > Pruning

74. What is the SnowSQL CLI tool used for? Choose one correct value.

        > Connecting to and issuing SQL commands to Snowflake via the command line.

75. Which result from the APPROXIMATE_SIMILARITY estimation function would indicate two sets of rows overlap significantly but are not identical? Choose one correct value.

        > 0.8

76. Fail-safe is available for external tables. True or false?

        > False

77. Which object does an external function make use of to hold security related information? Choose one correct value.

        > API Integration.

78. Data providers can share data with a data consumer in a different cloud region or cloud provider. True or false?

        > False

79. In which state is a Virtual Warehouse billable? Choose one correct value.

        > STARTED

80. What is the function of the INITIALLY_SUSPENDED property of a Virtual Warehouse? Choose one correct value.

        > Specifies if a Virtual Warehouse should be suspended immediately after its created.

81. Which is the most accurate description of the Snowflake Partner Connect? Choose one correct value.

        > The Snowflake Partner Connect allows you to easily create trial account with selected Snowflake business partners and integrate these accounts with Snowflake.

82. How many days is the query history maintained in the history tab of the classic UI? Choose one correct value.

        > 14

83. A data engineer is running some transformation jobs using a M virtual warehouse. The virtual warehouse seems to be suspending between the jobs, making subsequent jobs take longer. What could be the issue? Choose one correct value.

        > The Virtual Warehouse AUTO_SUSPEND property (in seconds) is set too low.

84. Cloning a table copies the underlying data effectively doubling storage costs. True or false?

        > False

85. Which statement is incorrect regarding snowflake editions? Choose one correct value.

        > The Enterprise edition contains all the features of the Business Critical edition.

86. Which table type does have the fail-safe feature? Choose one correct value.

        > Permanent

87. When copying files from a table to an internal stage using the COPY INTO `<location>` command, the results are split into multiple files. Which copy option would I use to ensure only one file is produced? Choose one correct value.

        > SINGLE

88. Which SQL commands would show the contents of a stage? Select all that apply.

        > ls @MY_STAGE;
        > LIST @MY_STAGE;

89. What is the purpose of the VALIDATE function? Choose one correct value.

        > Allows a user to view all errors encountered during a previous COPY INTO execution.

90. Which queries are examples of selective point lookups? Select all that apply.

        > SELECT NAME, ADDRESS FROM EMPLOYEES WHERE EMP_ID IN (‘12867’,’0987SS’);

        > SELECT NAME, ADDRESS FROM EMPLOYEES WHERE EMP_EMAIL = ‘support.help@corp.com’;

91. Snowflake provides a suite of powerful features that ensure the highest possible levels of data security. Which statements are correct regarding Snowflake? Select all that apply.

        > Snowflake uses a hierarchical key model which is rooted in a hardware key.

        > Snowflake support discretionary access control. (DAC)

        > Snowflake makes use of key-pair authentication for programmatic access.

        > Tri-secret secure makes use of a composite key made up of a customer managed key and a Snowflake managed key.

92. Which layers are in Snowflake’s Multi-cluster Shared Data Architecture? Choose two correct values.

        > Compute / Query Processing Layer
        > Storage Layer

93. When setting DATA_RETENTION_TIME_IN_DAYS to 0 on a table, Time Travel is effectively disabled for that table. True or false?

        > True

94. What is the behavior of the COPY INTO <table> command when the ON_ERROR option is set to CONTINUE? Choose one correct value.

        > Load the file if errors are found.

95. External tables can be cloned. True or false?

        > False

96. Which types of notation are used to traverse semi-structured data natively in Snowflake? Select all that apply.

        > Dot notation.

        > Bracket notation.

97. What is the section in bold of the following Snowflake account URL referred to as: xy12345.us-east-2.aws.snowflakecomputing.com? Choose one correct value.

        > Account Identifier

98. What are the two scaling policies that can be defined when creating a multi-cluster warehouse? Choose two correct values.

        > Standard
        > Economy

99. What does it mean to overload a User Defined Function (UDF)? Choose one correct value.

        > The ability for multiple UDFs to exist with the same identifier but different input arguments.

100.  The following command is permitted when interacting with a Virtual Warehouse: ALTER WAREHOUSE DE_VW SET WAREHOUSE_SIZE=LARGE. True or false?

      > True

101.  Materialized views can cause additional costs by …?


    > Serverless cost
    > Database Storage

102. Which copy option needs to be used when the data should not be unloaded into multiple files but only into one file?

     > SINGLE

103. Which statements about roles and privileges are correct?


    > Privileges are granted to roles.
    > Roles can be granted to other roles.

104. What is not managed by the Cloud Services Layer?

     > Query processing
     > Table storage

105. In this scenario, schema_b is created as a clone of schema_a. Accordingly, schema_b.table_a is created as a clone as well. Which statements are true?

     > All privileges in schema_b.table_a are inherited from schema_a.table_a.

     > All clustering keys will also be available in the cloned table.

106. Multiple warehouses can be assigned to one resource monitor.

     > True

107. How can Data Transfer costs apply when loading data from an external stage?

     > There can be costs for Data Transfer when the region/cloud provider that the Snowflake account is based on is different from the region/cloud provider of the external stage.

108. Which functions return information on the clustering depth of a table?

     > SYSTEM$CLUSTERING_DEPTH
        > SYSTEM$CLUSTERING_INFORMATION

109. Multi-factor authentication is available starting from which edition?

     > Standard

110. How is data stored in Snowflake?

     > Compressed
     > In a columnar format

111. What feature is not available in the Snowflake Enterprise edition? Select two.

     > Customer-managed encryption
     > Dedicated metadata storage

112. Which object can be used to insert values into a table by executing a SQL statement based on a schedule?

     > Tasks

113. Which statements about the three distinct layers in the Snowflake architecture are true?

Select all that apply.

        > Snowflake has decoupled compute and storage.

        > Snowflake uses storage of other cloud providers (AWS, GCP, or Azure).

114. What is true about Secure UDFs?

     > They bypass certain optimizations which can reduce query performance.

     > They hide the definition from unauthorized users.

115. What is true about data sharing?

     > Privileges on the shared database and schemas can be defined in the share.

     > External tables can be shared

116. Which layer is referred to as the “brain of the system”?

     > Cloud Services

117. Which entities are part of a federated environment?

     > External identity provider
     > Service provider

118. What is the maximum retention period in days for time travel in the Enterprise Edition?

     > 90

119. What sections can be part of a Snowflake Scripting block?

     > EXCEPTION
     > BEGIN
     > DECLARE
     > END

120. What is true about Federated Authentication?

     > There is native support for Okta.
     > Most SAML 2.0-compliant vendors are supported.

121. What type of transformations are supported during loading?

     > Casting data types
     > Column omitting
     > Column reordering

122. New files arrive regularly in an S3 bucket that must be loaded immediately into a table. How can you set up Snowpipe to do that?

     > Use a cloud notification and set up a cloud notification that triggers a pipe.

123. Tri-Secret Secure is available starting from which edition?

     > Business Critical

124. What is a valid way to access the second array element (“hands-on”) of the formats array in “module1” in “azure” from the following VARIANT value?


    ```json
    {"courses": {
       "snowflake": {
    "module1": {
          	"topic": "Introduction",
    	"difficulty": "All levels"
    		  }
    		 },
       "azure": {
    "module1": {
    	"topic": "Introduction",
    	"formats": [
    	    "video lectures",
    	    "hands-on",
    	    "quizzes"]
    		}
    		}
    	}
    }
    ```
    The column is called RAW and is the only column in this table.

    Select all the apply.

        > SELECT raw:courses.azure.module1.format[1]

        > SELECT $1:courses.azure.module1.format[1]

125. What are recommended methods to reduce data spilling?

     > Divide the data into smaller portions for processing

     > Use a larger warehouse

126. What is true about Internal Stages?

     > The data will be automatically encrypted

     > The data will be automatically compressed

127. What is true about roles and users?

     > Multiple roles can be granted to a single user.

     > The ACCOUNTADMIN role is the top-level role.

128. Which of the following are aspects of access control in Snowflake?


    > Role-based Access Control
    > Discretionary Access Control

129. A resource monitor on a warehouse has defined the action “Notify and Suspend” when 90% of the credit quota is reached. What happens when this 90% of the credit quota is reached and the relevant warehouse is currently executing a query?

     > The query will be processed by the warehouse and then the warehouse shuts down.

130. Which command is sued to show all files in a named internal stage?

     > LIST @stage_name;

131. What is true about clustering?

     > A clustering key can be applied to an expression like casting a timestamp to date.

     > A clustering key can be applied to multiple columns.

132. Which accounts will always get access to new releases on the second day of the release?


    > Business Critical Snowflake edition accounts

    > Virtual Private Snowflake edition accounts

    > Enterprise edition accounts that have not requested Early-Access

133. What is the correct syntax to query from a directory table?

     > SELECT \* FROM DIRECTORY (@stage_name)

134. Which parameter can be used to set the retention period for which data is retained when performing time travel in a specific table?

     > DATA_RETENTION_TIME_IN_DAYS

135. What is the behavior of the VALIDATION_MODE parameter set to RETURN_n_ROWS in the COPY command?

     > Validate the first n rows and return them if no error occurs, otherwise return the first error.

136. Who can create network policies on an account level?

     > Users with CREATE NETWORK POLICY privileges
     > Users with ACCOUNTADMIN role
     > Users with SECURITYADMIN role

137. How is data encrypted in transit?

     > TLS 1.2

138. How much data (calculated uncompressed) is contained in one micro-partition?

     > 50 – 500 MB

139. On which of the following operating systems can SnowSQL be installed on?

     > Linux
     > macOS
     > Windows

140. What is the maximum row length of a VARIANT data type?

     > 16 MB uncompressed

141. Which statements are true about federated authentication?

     > There is native support for AD FS
     > Snowflake is compatible with SCIM 2.0.
     > Most SAML 2.0-compliant vendors are supported.

142. What is the default behavior of the ON_ERROR option in Snowflake COPY command (for bulk loading)?

     > ABORT_STATEMENT

143. For how many seconds are we charged if a warehouse is active for 2:46 minutes?

     > 166 seconds

144. What privilege is needed to perform a PUT operation on an internal stage?

     > WRITE

145. What can be used in Snowflake Scripting?

     > Cursors
     > Conditional logic like IF/ELSE
     > FOR loops

146. Which factors influence the price of credits? Select all that apply.


    > The cloud provider that the account is based on
    > The region that the account is based on
    > The edition of the account

147. Which URL needs to be queried to get a URL that provides open access to a file via browser without the need to authenticate?

     > GET_PRESIGNED_URL

148. What are valid ways to access the “courses” element from the following VARIANT value:


    ```json
    {"courses": {
           "snowflake": {
    	"module1": {
    	      	"topic": "Introduction",
    		"difficulty": "All levels"
    			  },

           "azure": {
    	"module1": {
    		"topic": "Introduction",
    		"formats": [
    		    "video lectures",
    		    "hands-on",
    		    "quizzes"]
    			}
    			}
    		}
    	}
    }
    ```

The column is called RAW.

Select all the apply.

        > SELECT $1:courses
        > SELECT RAW:courses
        > SELECT raw:courses

149. A multi-cluster warehouse has been set up in the mode “Auto-scale” with the scaling policy “Economy”.

When will an additional cluster be provisioned?

        > When the system detects that there is enough workload to keep the clustering running for at least 6 min

150. What results can be taken from the metadata cache without the use of a virtual warehouse?

     > Min value
     > Count rows
     > Number of distinct values

151. How many credits are consumed for a warehouse of the size S when it runs for 43 seconds.

     > 2/60 credits

152. What can be part of a share?

     > Privileges on the object
     > Account identifiers

153. How many public keys can be part of a key pair for key pair authentication? Select all that apply.

     > 2
     > 1

154. Which type of objects can be shared?

     > Secure UDFs
     > External Tables
     > Secure views

155. Which statements are true?


    > Querying table functions in the INFORMATION_SCHEMA can give different results depending on the privileges of the role that executes the query.

    > The INFORMATION_SCHEMA has no information about dropped objects.

156.  You want to have information about a column that has been created 5 min ago. How would you do that?

      > Query the COLUMN view in the INFORMATION_SCHEMA.

157.  What are the relevant factors of a query to benefit significantly from materialized views?

      > Frequently run query
      > Sufficiently complex query

158.  Which privileges are needed to clone a Table?

      > SELECT

159.  We can use our own compute resources from our local data center.

      > False

160.  Where is an external function executed?

      > Outside of Snowflake

161.  How many credits are consumed for a warehouse of the size L per hour?

      > 8 Credits

             XS – 1 credit per hour
             S – 2 credits per hour
             M – 4 credits per hour
             L – 8 credits per hour
