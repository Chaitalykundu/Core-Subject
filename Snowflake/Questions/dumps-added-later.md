/////////////////////////////////////////////////////////////////////////////

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

///////////////////////////////////////////////////////////////

1. Local storage usage can be monitored through a browser's developer tools,
