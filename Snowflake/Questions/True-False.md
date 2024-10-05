# Questions

1. Snowflake can run private as well as hosted environment?

2. When data is loaded into snowflake, it stored this optimized data into cloud storage

3. Customers cannot see or directly access the data objects that snowflake stores, they can only do so through SQL query operations that are carried out using snowflake

4. Query execution is performed in Processing layer. Each virtual warehouse is an independent compute cluster that does not share compute resources with other virtual warehouse

5. The cloud service layer is a collection of services that co-ordinate activities across snowflake. The cloud services layer also runs on compute instances provisioned by snowflake from cloud provider.

6. Only standard edition of snowflake can be hosted all three major cloud providers (AWS, Azure, GCP), higher edition of snowflake can only be in AWS.

7. A behavior change, applied by snowflake as part of weekly or monthly release cycle, is defined as any change to existing that returns different results from before and may impact customer code or workloads.
8. The stage approach only applies to the full releases of snowflake. For patch releases which includes only fixes, all accounts (standard & higher) are moved on the same day

9. Snowflake puts a hard limit on number of databases. You can create only 10,000 databases in a snowflake instance

10. A snowflake user can configure multi-factor authentication(MFA) through the snowflake Web-UI

&nbsp;

&nbsp;

&nbsp;

&nbsp;

# Answers

1. Snowflake can run private as well as hosted environment?

    > False

         Snowflake can completely run on **CLOUD** environment. All components of snowflake's service can run in PUBLIC infrastructure.

2. When data is loaded into snowflake, it stored this optimized data into cloud storage

    > True

         When data is loaded into snowflake, snowflake recognizes that data into its internal optimized, compressed,  columnar format. Snowflake stores this optimized data in cloud storage.

3. Customers cannot see or directly access the data objects that snowflake stores, they can only do so through SQL query operations that are carried out using snowflake

    > True

        All the data or objects stored are accessible via SQL statements

4. Query execution is performed in Processing layer. Each virtual warehouse is an independent compute cluster that does not share compute resources with other virtual warehouse

    > True

        Compute layer or Processing layer does not share compute resources with other virtual warehouse

5. The cloud service layer is a collection of services that co-ordinate activities across snowflake. The cloud services layer also runs on compute instances provisioned by snowflake from cloud provider.

    > True

6. Only standard edition of snowflake can be hosted all three major cloud providers (AWS, Azure, GCP), higher edition of snowflake can only be in AWS.

    > True

7. A behavior change, applied by snowflake as part of weekly or monthly release cycle, is defined as any change to existing that returns different results from before and may impact customer code or workloads.

    > True

8. The stage approach only applies to the full releases of snowflake. For patch releases which includes only fixes, all accounts (standard & higher) are moved on the same day

    > True

        Patch release which includes fixed are moved in the same day for all accounts

9. Snowflake puts a hard limit on number of databases. You can create only 10,000 databases in a snowflake instance

    > False

        Snowflake does not limit the number of databases.

        You can create or the number of schemas you can create within a database.

        Snowflake also does not limit the number of tables you can create in a schema

10. A snowflake user can configure multi-factor authentication(MFA) through the snowflake Web-UI

    > True
