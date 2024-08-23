# Overview

- Traditional Data Warehouse Architecture
-
-
-

&nbsp;

&nbsp;

&nbsp;

# Layers

Snowflake’s unique architecture consists of three key layers:

- Database Storage layer
- Compute or Query Processing layer
- Cloud Services layer (Brain of snowflake)

&nbsp;

&nbsp;

# Database Storage layer

When data is loaded into Snowflake, Snowflake reorganizes that data into its internal optimized, compressed, columnar format. Snowflake stores this optimized data in cloud storage.

Snowflake manages all aspects of how this data is stored — the organization, file size, structure, compression, metadata, statistics, and other aspects of data storage are handled by Snowflake. The data objects stored by Snowflake are not directly visible nor accessible by customers; they are only accessible through SQL query operations run using Snowflake.

&nbsp;

- Underlying Cloud storage (S3, Azure blob, GCP bucket)
- Virtually infinity storages (Scaling)
- Compressed & Encrepted
- Cloud data redundancy
- Pay only for stored data

# Compute or Query Processing layer

- Also called query engine or virtual warehouse
- Underlying virtual machine (EC2, Azure-GCP VM)
- Scale up and down as needed (it is not inF)
- Different size to serve different workloads

&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
&nbsp;
