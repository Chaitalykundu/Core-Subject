1. What is one disadvantage of the shared disk architecture? Choose one correct value.

    > The storage is potentially a single point of failure

2. What is one disadvantage of the shared nothing architecture? Choose one correct value.

    > Storage and compute is tightly coupled

3. What makes Snowflake a “cloud native” product? Choose one correct value.

    > Snowflake was designed to make use of the unique capabilities of the cloud

4. Snowflake implements ANSI standard SQL. True or false?

    > True

5. Which type of cloud computing service is Snowflake? Choose one correct value.

    > SaaS

6. Users can SSH into the compute instances which make up a virtual warehouse. True or false?

    > False

7. What type of data storage format does Snowflake store table data in? Choose one correct value.

    > Columnar

8. Which statement is incorrect regarding snowflake editions? Choose one correct value.

    > Virtual private snowflakes allows the user to host a deployment of snowflake on their on-premise infrastructure

9. The object container hierarchy exists in what order? Choose one correct value.

    > Organization -> Account -> Database -> Schema

10. All objects are individually securable. True or false?

    > True

11. Snowflake uses the following access control schemes: Role Based Access Control (RBAC) and ___________.

    > Discretionary Access Control (DAC)

12. Which system-define role is it recommended to assign custom roles to? Choose one correct value.

    > SYSADMIN

13. If the user property DISABLE_MFA was set to true, the user would need to re-enroll to use multi-factor authentication again. True or false?

    > True

14. Network policies currently support which type of IP address? Choose one correct value.

    > IPv4

15. Key rotation is the practice of transparently replacing existing account and table encryption keys every __ number of days. Choose one correct value.

    > 30

16. Only standard views can be designated as secure. True or false?

    > False.............Both standard and materialized views can be designated as secure.

17. The ACCOUNT_USAGE share contains a database called SNOWFLAKE. The views in this database are used to provide fine-grained metrics at the account and object level. What is the maximum number of months data in these views available for? Choose one correct value.

    > 12

18. By default, which system-define role can access the SNOWFLAKE database? Choose one correct value.

    > ACCOUNTADMIN

19. Account usage views record dropped objects. True or false?

    > True

20. If the role ACCOUNTADMIN was currently active, what would a user see issuing a query that included an email column with the below column masking policy applied to it?

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

    > 32............. A large Virtual Warehouse costs 8 Snowflake credits per hour while its in the started state.

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
