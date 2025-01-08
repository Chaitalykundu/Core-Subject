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

20. Snowflake uses a `_______` repository for persisted data that is accessible from all compute nodes in the platform

    - local data repository
    - in memory repository
    - central data repository
    - cache data repository

21. Snowflake supports loading data from files staged in any of the following locations. Select all that apply

    - Amazon S3
    - Google cloud storage
    - Microsoft Azure blob storage
    - Snowflake internal storage

22. Each Snowflake account is hosted in

    - multiple regions for scalability
    - multiple continents for high availability
    - a single region
    - cross cloud regions for security

23. If latency is a concern for your end users, how should you choose the region for your snowflake instance

    - Any region, as well regions give same performance
    - Only US region as it gives best performance
    - available region with closest geographic proximity to your end users
    - Snowflake does the region selection automatically

24. The unit cost for credit in snowflake is determined by

    - Snowflake edition
    - Cloud region
    - Snowflake edition & Cloud region
    - Cloud Provider like AWS or GCP

25. If you have strong balance between features, level of supports and costs, Which edition of snowflake would you select?

    - Standard
    - Enterprise
    - Business Critical
    - VPS

26. Which minimum edition of snowflake would you choose if you need features which are designed for large scale enterprise like time travel etc?

    - Standard
    - Enterprise
    - Business Critical
    - VPS

27. Which minimum edition of snowflake would you choose if you need features related to data protection and enhanced securities (like PHI and sensitive data etc)

    - Standard
    - Enterprise
    - Business Critical
    - VPS

28. Which edition of snowflake isolates from all other snowflake accounts and data sharing is only possible via snowflake support team

    - Standard
    - Enterprise
    - Business Critical
    - VPS

29. Snowflake deploys new release each week. Mark the true statement

    - Snowflake services go down during the deployment
    - Snowflake services are partially available during the deployment
    - Deployments happen transparently in the background
    - Only select statement works during the deployment

30. Each week, snowflake deploys two planned release - full release and patch release. Select all that is included in the full release

    - New features
    - Feature enhancements
    - Fixed
    - Behavioral Changes

31. The patch release, which is done as part of weekly release cycle includes?

    - Only SQL Feature Enhancements
    - Only Fixes
    - Only Updates
    - Only UI Changes

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

    > Query Processing / Query execution

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

20. Snowflake uses a `_______` repository for persisted data that is accessible from all compute nodes in the platform

    > - central data repository

21. Snowflake supports loading data from files staged in any of the following locations. Select all that apply

    > - Amazon S3
    > - Google cloud storage
    > - Microsoft Azure blob storage
    > - Snowflake internal storage

22. Each Snowflake account is hosted in

    > - a single region

23. If latency is a concern for your end users, how should you choose the region for your snowflake instance

    > - available region with closest geographic proximity to your end users

24. The unit cost for credit in snowflake is determined by

    > - Snowflake edition & Cloud region

25. If you have strong balance between features, level of supports and costs, Which edition of snowflake would you select?

    > Standard

          Standard Edition is our introductory level of offering, providing full, unlimited access to all of snowflake's standard features. It provides a strong balance between features. level of support and cost

26. Which minimum edition of snowflake would you choose if you need features which are designed for large scale enterprise like time travel etc?

    > Enterprise

27. Which minimum edition of snowflake would you choose if you need features related to data protection and enhanced securities (like PHI and sensitive data etc)

    > Business Critical

        Business Critical edition is formally known as Enterprise for Sensitive Data (ESD)

28. Which edition of snowflake isolates from all other snowflake accounts and data sharing is only possible via snowflake support team

    > VPS

        VPS is completely separate snowflake environment, isolated from all other snowflake accounts,.

29. Snowflake deploys new release each week. Mark the true statement

    > Deployments happen transparently in the background

30. Each week, snowflake deploys two planned release - full release and patch release. Select all that is included in the full release

    > - New features
    > - Feature enhancements
    > - Fixed
    > - Behavioral Changes

31. The patch release, which is done as part of weekly release cycle includes?

    > only fixes

&nbsp;

&nbsp;

# Doubt

24. The unit cost for credit in snowflake is determined by
