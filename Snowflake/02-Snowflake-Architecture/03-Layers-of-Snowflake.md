# Overview

- Layers
- Database Storage layer or Data layer
- Compute layer or Query Processing layer or Virtual Warehouse layer
- Services layer or Cloud Services layer (Brain of snowflake)
- How Data Storage layer works
- How Data Compute layer works
- How Data Cloud Services layer works

&nbsp;

Read : <https://hevodata.com/blog/snowflake-architecture-cloud-data-warehouse/#Components_of_Data_Warehouse_Architecture>

&nbsp;

&nbsp;

&nbsp;

# Note

- Each database belongs to a single Snowflake account

- Each schema belongs to a single database.

&nbsp;

&nbsp;

# Layers

Snowflake’s unique architecture consists of **three** key layers:

1. Database Storage layer or Data layer

2. Compute layer or Query Processing layer or Virtual Warehouse layer

3. Services layer or Cloud Services layer (Brain of snowflake)

Each layer can scale independently.

&nbsp;

&nbsp;

# Database Storage layer

When data is loaded into Snowflake, Snowflake reorganizes that data into its internal optimized, compressed, columnar format. Snowflake **_stores this optimized data in cloud storage_**.

Snowflake manages all aspects of **how this data is stored — the organization, file size, structure, compression, metadata, statistics, and other aspects of data storage are handled by Snowflake**.

The data objects stored by Snowflake are not directly visible nor accessible by customers; they are only accessible through **SQL query** operations run using Snowflake.

&nbsp;

### Key points

- Underlying Cloud storage (S3, Azure blob, GCP bucket)
- Virtually infinity storages (Scaling)
- Compressed & Encrypted
- Cloud data redundancy
- Pay only for stored data

&nbsp;

&nbsp;

# Compute or Query Processing or Virtual Warehouse layer

**Query execution** is performed in the processing layer. Snowflake processes queries using **“virtual warehouses”**. Each virtual warehouse is an **MPP (massively parallel processing)** compute cluster composed of multiple compute nodes allocated by Snowflake from a cloud provider.

Each virtual warehouse is an independent compute cluster that does not share compute resources with other virtual warehouses. As a result, each virtual warehouse has no impact on the performance of other virtual warehouses.

&nbsp;

### Key points

- Also called **query engine or virtual warehouse**
- Underlying virtual machine (EC2, Azure-GCP VM)
- Scale up and down as needed (it is not infinite but big enough to accommodate any workload)
- Different size to serve different workloads

&nbsp;

&nbsp;

# Services or Cloud Services layer

The cloud services layer is a collection of services that coordinate activities across Snowflake. These services tie together all of the different components of Snowflake in order to **process user requests, from login to query dispatch**. The cloud services layer also runs on compute instances provisioned by Snowflake from the cloud provider.

&nbsp;

### Services managed in this layer include

- Authentication & Authorization (Access control)
- User and session management
- Query compilation / Parsing, Optimization and Data Caching
- Virtual warehouse management
- Metadata storage and management
- Infrastructure management
- Data Security

&nbsp;

&nbsp;

# How Data Storage layer works

1. Snowflake stores all data into databases and the database is a **logical grouping of schemas** within a snowflake instance and Each database belongs to a single Snowflake account.

2. A schema is a **logical grouping of database objects** (tables, views, etc.). Each schema belongs to a single database.

3. The objects are primarily **tables** (permanent, temporary and transient) and **views** (standard or materialized)

4. These objects are part of one or more schemas

5. You can store any **structured** relational data (standard SQL datatype) or any **semi-structured** relational data (JSON, Parquet, Avro, ORC XML) ( Variant datatypes)

6. Snowflake uses highly secure cloud storage to maintain your structured and semi-structured data

7. As data is loaded into the table, following activities happen

   - Snowflake converts them into optimized columnar compressed format (proprietary to snowflake)

   - This optimized columnar compressed format brings a lot of data access efficiently (faster workload, low compute and storage cost)

   - And encrypt it AES 256 Strong encryption

   - Based on the cloud platform, data is loaded to the cloud storage layer (S3/Azure Blob/GCP Bucket), however, this is not visible to the user how it is stored and retrieved and overhead is taken care of by the snowflake.

   - These compressed and secure data is **accessible only via SQL** and there are no other means that it is accessible.

   - Data storage cost is calculated on the **daily average amount of data (in bytes)** (Short-lived or long-lived tables)

   - If the time travel feature is enabled, it is also part of the data storage cost.

&nbsp;

&nbsp;

# How Compute layer works

- Compute layer is where queries are executed. (Queries means select queries, join queries, data loading, procedure)

- Before any query is executed, compute machines need to provisioned and in snowflake it is called virtual warehouse (VWH)

- This virtual warehouse has to access same data storage or data layer. That's why it's called **Shared data multi-clustered architecture**

- You can choose a virtual warehouse as per the workload required without any contention or performance degradation.

- To create a VWH, you simply need to give **a name and size** (bigger the size more the compute power) (Size x-small = 1 node cluster, small = 2 node cluster, medium = 4 node cluster, 4X-large = 128 node cluster)

- Snowflake handles all the provisioning and configuration of underlying compute resources (In case of AWS, its EC2 instance and for Azure it's Azure VM)

- The VWH can be scaled up or down at any time during the query execution without any hiccups. WHen re-scaling is done, all the sub-sequent queries takes the advantage of the new size of the warehouse.

- When multiple VWH (of different sizes) runs in parallel, snowflake itself takes care of concurrency.

&nbsp;

&nbsp;

# How Cloud Service layer works

- Cloud Storage layer is also called **brain of the snowflake**

- Cloud service layer also co-ordinates and manages the entire system

- This layer is completely independent from the storage layer and compute layer and snowflake ensures that it is highly available (**redundancy and fault tolerance**)

- This layer takes care of the following

  - Authentication & Authorization ( via WebUI, or Connector or vSnowSQL or Native connector, or MFA etc)
  - User & session management
  - Query Planning, Compilation, Optimization and Data Caching
  - Virtual Warehouse Management
  - Co-ordinate data storage / updates
  - Transaction management
  - Metadata management (one of the core activity). This feature supports :

    - Zero copy cloning
    - Time Travel
    - Data sharing
    - Caching

  - Manage and maintain the life cycle of a query

- The service layer is highly scalable and distributed across multiple availability zone

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;
