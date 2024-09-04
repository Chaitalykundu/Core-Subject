# Questions

1. The architecture of Snowflake is

   - shared disk
   - shared nothing
   - shared data?
   - shared memory

2. Are databases stored within warehouses? Are warehouses stored within databases?

3. Does Snowflake store data with - compression? Encryption? Both?

4. When a warehouse is resized, what queries are affected? Only current? Current and

5. Costs are broken down into what two major categories?

6. Storage costs are based on the daily average of stored data. Is this based on the data's compressed size or uncompressed size?

7. What things aren't required because Snowflake is a true SaaS solution?

8. Can Snowflake be hosted on a company's internal cloud? What on-premise options are offered by Snowflake?

9. Can Snowflake be purchased for installation on a company's internal servers or Virtual Private Cloud(VPC)?

10. Snowflake uses MPP compute clusters. Are these called Virtual Data Marts? or Virtual Warehouses?

11. Does Snowflake recommend only running no more than 2 warehouses simultaneously to avoid contention? 5?

12. Are Snowflake Data Warehouses like Data Marts in that each one is assigned to work on a subset of the data stored in the account?

13. Which installment option versions of Snowflake are available?

    - A. Microsoft Cloud Native Accounts
    - B. Snowflake-Hosted Accounts (on Amazon cloud infrastructure)
    - C. Hybrid On-Premises + Cloud Installation
    - D. Snowflake-Hosted Accounts (on Google Cloud Platform infrastructure)
    - E. On-Premises Custom Installation
    - F. Snowflake-Hosted Accounts (on Azure cloud infrastructure)

14. What are data storage cost calculations based on in Snowflake?

    - Uncompressed Size
    - Compressed Size
    - Amount Stored on Last Day of Month
    - Amount Stored on First Day of Month
    - Amount Stored - Daily Average

15. Snowflake compute costs depend on which of the following?

    - The number of rows returned in queries.
    - The amount of time warehouses have run.
    - The total number of warehouses in the account.
    - The sizes of running warehouses.

16. How often does Snowflake release new features?

17. What common tasks for traditional on-premises database and IT staff are not required with Snowflake?

    - Maintaining metadata
    - Maintaining statistics
    - Maintaining the physical security of a server room (key cards, door locks, etc.)
    - Maintaining database objects

&nbsp;

&nbsp;

# Module 1

1. The architecture of Snowflake is

    - shared disk
    - shared nothing
    - shared data
    - shared memory

    Ans : data

2. Are databases stored within warehouses? Are warehouses stored within databases?

3. Does Snowflake store data with

    - compression?
    - Encryption?
    - Both?

    Ans : Both

4. When a warehouse is resized, what queries are affected? Only current? Current and
    subsequent? Only subsequent?

        Ans : Only subsequent

5. Costs are broken down into what two major categories?

6. Storage costs are based on the daily average of stored data. Is this based on the data's compressed size or uncompressed size?

        Ans : compressed size

7. What things aren't required because Snowflake is a true SaaS solution?

        Ans : No hardware to purchase or configure.

        No maintenance upgrades or patches to install.

        Transparent releases don't require user intervention.

8. Can Snowflake be hosted on a company's internal cloud? What on-premise options are offered by Snowflake?

9. Can Snowflake be purchased for installation on a company's internal servers or Virtual Private Cloud(VPC)?

10. Snowflake uses MPP compute clusters. Are these called Virtual Data Marts? or Virtual Warehouses?

11. Does Snowflake recommend only running no more than 2 warehouses simultaneously to avoid contention? 5?

12. Are Snowflake Data Warehouses like Data Marts in that each one is assigned to work on a subset of the data stored in the account?

13. Which installment option versions of Snowflake are available?

    - A. Microsoft Cloud Native Accounts
    - B. Snowflake-Hosted Accounts (on Amazon cloud infrastructure)
    - C. Hybrid On-Premises + Cloud Installation
    - D. Snowflake-Hosted Accounts (on Google Cloud Platform infrastructure)
    - E. On-Premises Custom Installation
    - F. Snowflake-Hosted Accounts (on Azure cloud infrastructure)

Ans : B. Snowflake-Hosted Accounts (on Amazon cloud infrastructure), D. Snowflake-Hosted Accounts (on Google Cloud Platform infrastructure), F. Snowflake-Hosted Accounts (on Azure cloud infrastructure)

14. What are data storage cost calculations based on in Snowflake?

    - Uncompressed Size
    - Compressed Size
    - Amount Stored on Last Day of Month
    - Amount Stored on First Day of Month
    - Amount Stored - Daily Average

Ans : Compressed Size, Amount Stored - Daily Average

15. Snowflake compute costs depend on which of the following?

    - The number of rows returned in queries.
    - The amount of time warehouses have run.
    - The total number of warehouses in the account.
    - The sizes of running warehouses.

Ans The amount of time warehouses have run, The sizes of running warehouses.

16. How often does Snowflake release new features?

Ans : Weekly

17. What common tasks for traditional on-premises database and IT staff are not required with Snowflake?

    - Maintaining metadata
    - Maintaining statistics
    - Maintaining the physical security of a server room (key cards, door locks, etc.)
    - Maintaining database objects

Ans : Maintaining metadata, Maintaining statistics, Maintaining the physical security of a server room (key cards, door locks, etc.)
