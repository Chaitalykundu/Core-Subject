# Questions

1. Which layer of the Snowflake architecture is responsible for managing user authentication, access control, and query optimization?

2. Which Snowflake edition offers features such as multi-cluster warehouses and up to 90 days of time travel?

3. What is the minimum Snowflake edition that provides multi-cluster warehouses and up to 90 days of Time Travel?

4. What is the duration for which the query result cache remains valid before it is reset?

5. Snowflake: How are virtual warehouse credits charged?

6. Snowflake offers multiple editions. Which are they?

7. State True or False : Each successive edition builds on the previous edition through the addition of edition-specific features and/or high levels of of service

8. A snowflake account can be hosted on which platforms?

9. Does credit cost depend on snowflake edition?

10. Does extendable time travel work for all edition?

11. State True or False : All snowflake features are same regardless of cloud platform and region

12. State True or False : Each snowflake account hosted in a single region

13. State True or False : Snowflake edition can be upgraded with the help of snowflake support team

14. Snowflake edition, cloud provider and region can be found from the classic / legacy web UI

15. Snowflake provides two types of storage. On-demand & Capacity. Capacity storage comes with discounted pricing and needs up-front commitment

    - True
    - False

16. What happens when a running warehouse is resized in Snowflake?

    - All running queries are immediately terminated

    - Queued queries will execute at the new size while running queries continue at the current size

    - The warehouse must be suspended before resizing can take effect

    - The new size will only apply to future queries after a pause

17. Which of the following features is exclusive to the Business Critical Edition of Snowflake, enhancing its security and compliance capabilities?

    - Multi-cluster warehouses
    - Data encryption everywhere
    - Materialized views
    - Dynamic data masking

18. What is the primary function of the Service Layer in Snowflake's architecture?

    - To store raw data in its original format
    - To manage user roles and permissions
    - To accept SQL requests, coordinate queries, and manage transaction results
    - To perform data unloading and loading operations

19. What are the potential implications of setting AUTO_RESUME = TRUE on a warehouse in Snowflake?
20. What is the primary purpose of the data cache in Snowflake?
21. What is the primary function of the Result Cache in Snowflake?
22. Which of the following features is NOT included in the Standard Edition of Snowflake?

    - Complete SQL Data Warehouse
    - Multi-cluster warehouse
    - 1 day of time travel
    - Enterprise grade encryption

23. What is the primary function of the compute layer in a Virtual Data Warehouse within Snowflake?

24. What is the primary function of the Remote Disk in Snowflake's architecture?

25. When scaling out by adding clusters to a multi-cluster warehouse, you are primarily scaling for improved:

26. What is the primary function of the Local Disk Cache in Snowflake's architecture?

27. Which of the following features distinguishes the Virtual Private Snowflake edition from other Snowflake editions?

28. What is the benefit of a warehouse using an economy scaling policy?

29. Which of the following cache layers in Snowflake is primarily used to store the results of queries for faster retrieval on subsequent executions?

30. What is the primary function of the Storage Layer in Snowflake, often known as Remote Disk?

&nbsp;

&nbsp;

# Answers

1. Which layer of the Snowflake architecture is responsible for managing user authentication, access control, and query optimization?

   > Service Layer / Cloud Service Layer

2. Which Snowflake edition offers features such as multi-cluster warehouses and up to 90 days of time travel?

   > Enterprise

3. What is the minimum Snowflake edition that provides multi-cluster warehouses and up to 90 days of Time Travel?

   > Enterprise

4. What is the duration for which the query result cache remains valid before it is reset?

   > 24 hours

5. Snowflake: How are virtual warehouse credits charged?

   > Per second, with a 60 sec minimum

6. Snowflake offers multiple editions. Which are they?

   > Standard, Enterprise, Business Critical, VPS.

7. State True or False : Each successive edition builds on the previous edition through the addition of edition-specific features and/or high levels of of service

   > True

8. A snowflake account can be hosted on which platforms?

   > AWS, Azure, GCP

9. Does credit cost depend on snowflake edition?

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

19. What are the potential implications of setting AUTO_RESUME = TRUE on a warehouse in Snowflake?

20. What is the primary purpose of the data cache in Snowflake?

21. What is the primary function of the Result Cache in Snowflake?

22. Which of the following features is NOT included in the Standard Edition of Snowflake?
    > Multi-cluster warehouse
