# Questions

1. Which of the following roles is recommended to be used to create and manage users and roles?
2. True or False: Bulk unloading of data from Snowflake supports the use of a SELECT statement.

3. What are the three layers that make up Snowflake's architecture? (Choose three.)

4. True or False: Snowflake charges a premium for storing semi-structured data.

5. True or False: It is possible to unload structured data to semi-structured formats such as JSON and Parquet.

6. True or False: Snowflake's data warehouse was built from the ground up for the cloud in lieu of using an existing database or a platform, like Hadoop, as a base.

7. If a Small Warehouse is made up of 2 servers/cluster, how many servers/cluster make up a Medium Warehouse?

8. Which installment option versions of Snowflake are available?

9. Which ONE of the following terms BEST describes Snowflake's Architecture?

10. Which of the following terms or phrases can also be used to describe Snowflake?

11. Which statements are true about storage relationships?

12. Among the options listed, which is not a valid Snowflake Warehouse Size?

    - S
    - XL
    - M
    - XXS

13. As part of release process, snowflake does not move all accounts to release at the same time and follows a staged approached. Select the stage which is named as early access?

    - Stage - 1
    - Stage - 2
    - Stage - 3
    - Stage - 4

14. As part of release process, snowflake does not move all accounts to release at the same time and follows a staged approached. Select the stage which is named as regular access?

    - Stage - 1
    - Stage - 2
    - Stage - 3
    - Stage - 4

15. All ingested data stored in snowflake tables is encrypted using `____` strong encryption

- AES-64
- AES-128
- AES-256
- AES-512

16. The 3rd party tools and technologies, as well as the snowflake provided clients is classified as `______`

- Snowflake Ecosystem tool
- Snowflake Partner tools
- Snowflake Service tools
- Snowflake drivers

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

&nbsp;

# Answers

1. Which of the following roles is recommended to be used to create and manage users and roles?

   - A. SYSADMIN
   - B. SECURITYADMIN
   - C. PUBLIC
   - D. ACCOUNTADMIN

Ans : ACCOUNTADMIN

2. True or False: Bulk unloading of data from Snowflake supports the use of a SELECT statement.
   - A. True
   - B. False

Ans : True

3. What are the three layers that make up Snowflake's architecture? (Choose three.)

   - A. Compute
   - B. Tri-Secret Secure
   - C. Storage
   - D. Cloud Services

Ans : Compute, Storage, Cloud Services

4. True or False: Snowflake charges a premium for storing semi-structured data.
   - A. True
   - B. False

Ans : False

```md
Snowflake does not charge any differently whether you store Structured data vs Semi-structured data. The cost is the same.

This gives you the full flexibility to choose whether to transform your data (i.e. extract your common attributes from your semi-structured data) into structured tables, or choose to load your semi-structured data as is, and interrogate them at a later stage using standard SQL, or even join them with other structured data within the database.
```

5. True or False: It is possible to unload structured data to semi-structured formats such as JSON and Parquet.

   - A. True
   - B. False

Ans : True

6. True or False: Snowflake's data warehouse was built from the ground up for the cloud in lieu of using an existing database or a platform, like Hadoop, as a base.

   - A. True
   - B. False

Ans : False

```md
The Snowflake data platform is not built on any existing database technology or “big data” software platforms such as Hadoop.
```

7. If a Small Warehouse is made up of 2 servers/cluster, how many servers/cluster make up a Medium Warehouse?

   - A. 4
   - B. 16
   - C. 32
   - D. 128

Ans : 4

8. Which installment option versions of Snowflake are available?

   - A. Microsoft Cloud Native Accounts
   - B. Snowflake-Hosted Accounts (on Amazon cloud infrastructure)
   - C. Hybrid On-Premises + Cloud Installation
   - D. Snowflake-Hosted Accounts (on Google Cloud Platform infrastructure)
   - E. On-Premises Custom Installation
   - F. Snowflake-Hosted Accounts (on Azure cloud infrastructure)

Ans : B. Snowflake-Hosted Accounts (on Amazon cloud infrastructure), D. Snowflake-Hosted Accounts (on Google Cloud Platform infrastructure), F. Snowflake-Hosted Accounts (on Azure cloud infrastructure)

9. Which ONE of the following terms BEST describes Snowflake's Architecture?

   - A. Shared Disk
   - B. Shared Nothing
   - C. Shared Data
   - D. Shared Memory

Ans : Shared Data

10. Which of the following terms or phrases can also be used to describe Snowflake?

    - Native SQL
    - Hybrid Columnar
    - Built from the ground up for the cloud
    - Hadoop-Compliant
    - Multi-cluster
    - Oracle derived

Ans : Native SQL, Hybrid Columnar, Built from the ground up for the cloud, Multi-cluster

11. Which statements are true about storage relationships?

    - Snowflake Tables are stored within Schemas
    - Snowflake Databases are stored within Warehouses
    - Snowflake Warehouses are stored within Data Marts
    - Snowflake Schemas are stored within Warehouses
    - Snowflake Warehouses are stored within Databases
    - Snowflake Schemas are stored within Databases

Ans : Snowflake Tables are stored within Schemas, Snowflake Schemas are stored within Databases

12. Among the options listed, which is not a valid Snowflake Warehouse Size?

    > XXS

13. As part of release process, snowflake does not move all accounts to release at the same time and follows a staged approached. Select the stage which is named as early access?

    > Stage - 1

         Stage 1 is also known as early access and designated for enterprise ( or higher) edition of snowflake accounts

14. As part of release process, snowflake does not move all accounts to release at the same time and follows a staged approached. Select the stage which is named as regular access?

    > Stage - 2

         Stage -2 is also know as regular access and designed for Standard accounts

15. All ingested data stored in snowflake tables is encrypted using `____` strong encryption

    > AES-256

         All files stored in internal stages for data loading & unloading operations is automatically encrypted using AES-256 strong encryption

16. The 3rd party tools and technologies, as well as the snowflake provided clients is classified as `______`

    > Snowflake Ecosystem tool
