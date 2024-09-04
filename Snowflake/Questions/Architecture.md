# Question

1. Name the layers of snowflake architecture

2. What attributes make snowflake a true SaaS solution?

   - No hardware to purchase or configure
   - No creation of user accounts or roles is required
   - No maintenance upgrade or patches to install
   - No data storage costs
   - No query processing cost
   - Transparent releases don't require user intervention

3. Which installment option versions of Snowflake are available?

   - A. Microsoft Cloud Native Accounts
   - B. Snowflake-Hosted Accounts (on Amazon cloud infrastructure)
   - C. Hybrid On-Premises + Cloud Installation
   - D. Snowflake-Hosted Accounts (on Google Cloud Platform infrastructure)
   - E. On-Premises Custom Installation
   - F. Snowflake-Hosted Accounts (on Azure cloud infrastructure)

4. Which ONE of the following terms BEST describes Snowflake's Architecture?

   - A. Shared Disk
   - B. Shared Nothing
   - C. Shared Data
   - D. Shared Memory

5. Which of the following terms or phrases can also be used to describe Snowflake?

   - Native SQL
   - Hybrid Columnar
   - Built from the ground up for the cloud
   - Hadoop-Compliant
   - Multi-cluster
   - Oracle derived

6. Which of the following terms is associated with the Compute/Warehouse Layer?

   - Query Processing
   - Query Planning
   - Query Optimization
   - Query Design
   - Query Compilation

7. Which of the following terms are associated with the Cloud Services Layer?

   Select all that apply.

   - Query Processing
   - Query Planning
   - Query Optimization
   - Query Design
   - Query Compilation

8. Which of the following are performed by the Cloud Services Layer?

   Select all that apply.

   - Metadata Management
   - User Authentication
   - Metadata Storage
   - Data Security
   - Availability Zone Management

9. Which 3 these terms can be used to refer to the same layer?

   - Compute Layer
   - Virtual Warehouse Layer
   - Catalog Layer
   - Metadata Layer
   - Query Processing Layer

10. Which 2 of these terms refer to the same layer?

    - Cloud Services Layer
    - Virtual Warehouse Layer
    - Services Layer
    - Storage Layer
    - Catalog Layer

11. Which 2 of these terms refer to the same layer?

    - Metadata Layer
    - Virtual Management Layer
    - Catalog Layer
    - Data Layer
    - Storage Layer

12. Snowflake data storage costs are calculated based on

    - Uncompressed size
    - Compressed size
    - Amount stored on last day of month
    - Amount stored on first day of month
    - Amount stored - Daily average

13. Which statements are true about storage relationships?

    - Snowflake Tables are stored within Schemas
    - Snowflake Databases are stored within Warehouses
    - Snowflake Warehouses are stored within Data Marts
    - Snowflake Schemas are stored within Warehouses
    - Snowflake Warehouses are stored within Databases
    - Snowflake Schemas are stored within Databases

14. When a warehouse is resized, which queries make use of the new size?

    - Both current and subsequent queries
    - Only currently running queries
    - Only subsequent queries

15. Snowflake data storage costs include which types of data?

    - Metadata
    - Persistent data stored in permanent tables
    - Data retained to enable data recovery (time travel and fail-safe)
    - Cached results
    - Semi-structured data - additional fees

16. Snowflake compute costs depend on which of the following?

    - The number of rows returned in queries.
    - The amount of time warehouses have run.
    - The total number of warehouses in the account.
    - The sizes of running warehouses.

17. How often does Snowflake release new features?

18. What common tasks for traditional on-premises database and IT staff are not required with Snowflake?

    - Maintaining metadata
    - Maintaining statistics
    - Maintaining the physical security of a server room (key cards, door locks, etc.)
    - Maintaining database objects

19. Snowflake is a packaged software offering that can be installed by a user

    - It is true only for standard edition of snowflake
    - It is true for standard and enterprise edition of snowflake
    - It is not true
    - It is true only for standard edition of snowflake

&nbsp;

&nbsp;

# Answer

1. Name the layers of snowflake architecture

   > - Storage layer
   > - compute layer
   > - cloud service layer

2. What attributes make snowflake a true SaaS solution?

   > - No hardware to purchase or configure
   > - No maintenance upgrade or patches to install
   > - Transparent releases don't require user intervention

3. Which installment option versions of Snowflake are available?

   > - B. Snowflake-Hosted Accounts (on Amazon cloud infrastructure)
   > - D. Snowflake-Hosted Accounts (on Google Cloud Platform infrastructure)
   > - F. Snowflake-Hosted Accounts (on Azure cloud infrastructure)

4. Which ONE of the following terms BEST describes Snowflake's Architecture?

   > C. Shared Data

   It's also Hybrid architecture (Shared disk + shared nothing)

5. Which of the following terms or phrases can also be used to describe Snowflake?

   > - Native SQL
   > - Hybrid Columnar
   > - Built from the ground up for the cloud
   > - Multi-cluster

6. Which of the following terms is associated with the Compute/Warehouse Layer?

   > Query Processing

7. Which of the following terms are associated with the Cloud Services Layer?

   > - Query Planning,
   > - Query Optimization,
   > - Query Compilation,

8. Which of the following are performed by the Cloud Services Layer?

   > - Metadata Management
   > - User Authentication
   > - Metadata Storage
   > - Data Security

9. Which 3 these terms can be used to refer to the same layer?

   > - Compute Layer
   > - Virtual Warehouse Layer
   > - Query Processing Layer

10. Which 2 of these terms refer to the same layer?

    > - Cloud Services Layer
    > - Services Layer

11. Which 2 of these terms refer to the same layer?

    > - Data Layer
    > - Storage Layer

12. Snowflake data storage costs are calculated based on

    > - Compressed size
    > - Amount stored - Daily average

13. Which statements are true about storage relationships?

    > - Snowflake Tables are stored within Schemas
    > - Snowflake Schemas are stored within Databases

14. When a warehouse is resized, which queries make use of the new size?

    > Only subsequent queries

15. Snowflake data storage costs include which types of data?

    > - Persistent data stored in permanent tables
    > - Data retained to enable data recovery (time travel and fail-safe)

16. Snowflake compute costs depend on which of the following?

    > - The amount of time warehouses have run.
    > - The sizes of running warehouses.

17. How often does Snowflake release new features?

    > Weekly

18. What common tasks for traditional on-premises database and IT staff are not required with Snowflake?

    > - Maintaining metadata
    > - Maintaining statistics
    > - Maintaining the physical security of a server room (key cards, door locks, etc.)

19. Snowflake is a packaged software offering that can be installed by a user

    > - It is not true

    Snowflake manages all aspects of software installation & updates
