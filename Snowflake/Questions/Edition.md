# Questions

1. Which layer of the Snowflake architecture is responsible for managing user authentication, access control, and query optimization?
2. Which Snowflake edition offers features such as multi-cluster warehouses and up to 90 days of time travel?
3. What is the minimum Snowflake edition that provides multi-cluster warehouses and up to 90 days of Time Travel?
4. What is the duration for which the query result cache remains valid before it is reset?

5. What happens when a running warehouse is resized in Snowflake?

   - All running queries are immediately terminated

   - Queued queries will execute at the new size while running queries continue at the current size

   - The warehouse must be suspended before resizing can take effect

   - The new size will only apply to future queries after a pause

6. Which of the following features is exclusive to the Business Critical Edition of Snowflake, enhancing its security and compliance capabilities?

   - Multi-cluster warehouses
   - Data encryption everywhere
   - Materialized views
   - Dynamic data masking

7. What is the primary function of the Service Layer in Snowflake's architecture?

   - To store raw data in its original format
   - To manage user roles and permissions
   - To accept SQL requests, coordinate queries, and manage transaction results
   - To perform data unloading and loading operations

8. What are the potential implications of setting AUTO_RESUME = TRUE on a warehouse in Snowflake?
9. What is the primary purpose of the data cache in Snowflake?
10. What is the primary function of the Result Cache in Snowflake?
11. Which of the following features is NOT included in the Standard Edition of Snowflake?
12. What is the primary function of the compute layer in a Virtual Data Warehouse within Snowflake?
13. What is the primary function of the Remote Disk in Snowflake's architecture?
14. When scaling out by adding clusters to a multi-cluster warehouse, you are primarily scaling for improved:
15. What is the primary function of the Local Disk Cache in Snowflake's architecture?
16. Which of the following features distinguishes the Virtual Private Snowflake edition from other Snowflake editions?
17. What is the benefit of a warehouse using an economy scaling policy?
18. Which of the following cache layers in Snowflake is primarily used to store the results of queries for faster retrieval on subsequent executions?
19. What is the primary function of the Storage Layer in Snowflake, often known as Remote Disk?
20. Snowflake: How are virtual warehouse credits charged?

&nbsp;

&nbsp;

# Answers :

1.  Which layer of the Snowflake architecture is responsible for managing user authentication, access control, and query optimization?

    > Service Layer

2.  Which Snowflake edition offers features such as multi-cluster warehouses and up to 90 days of time travel?

    > Enterprise

3.  What is the minimum Snowflake edition that provides multi-cluster warehouses and up to 90 days of Time Travel?

    > Enterprise

4.  What is the duration for which the query result cache remains valid before it is reset?

    > 24 hours

5.  What happens when a running warehouse is resized in Snowflake?

    > Queued queries will execute at the new size while running queries continue at the current size

6.  Which of the following features is exclusive to the Business Critical Edition of Snowflake, enhancing its security and compliance capabilities?

    > Data encryption everywhere

7.  What is the primary function of the Service Layer in Snowflake's architecture?

    > To accept SQL requests, coordinate queries, and manage transaction results
