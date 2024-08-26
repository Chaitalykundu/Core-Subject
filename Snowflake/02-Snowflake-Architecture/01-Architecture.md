# Snowflake’s architecture

Snowflake’s Data Cloud is powered by an advanced data platform provided as **a self-managed service**. Snowflake enables data storage, processing, and analytic solutions that are faster, easier to use, and far more flexible than traditional offerings.

The Snowflake data platform is **not built on any existing database technology** or “big data” software platforms such as Hadoop. Instead, Snowflake combines a completely new SQL query engine with an innovative architecture natively designed for the cloud.

To the user, Snowflake provides all of the functionality of an enterprise analytic database, along with many additional special features and unique capabilities.

&nbsp;

&nbsp;

Snowflake’s architecture is a hybrid of traditional shared-disk and shared-nothing database architectures.

Similar to shared-disk architectures, Snowflake uses a central data repository for persisted data that is accessible from all compute nodes in the platform.

But similar to shared-nothing architectures, Snowflake processes queries using MPP (massively parallel processing) compute clusters where each node in the cluster stores a portion of the entire data set locally.

This approach offers the data management simplicity of a shared-disk architecture, but with the performance and scale-out benefits of a shared-nothing architecture.

&nbsp;

&nbsp;

# Data Platform as a Self-managed Service

Snowflake is a true self-managed service, meaning:

- There is **no hardware** (virtual or physical) to select, install, configure, or manage.

- There is virtually **no software** to install, configure, or manage.

- Ongoing maintenance, management, upgrades, and tuning are handled by Snowflake.

&nbsp;

&nbsp;

Snowflake runs completely on cloud** infrastructure**. 

All components of Snowflake’s service (other than optional command line clients, drivers, and connectors), run in **public** cloud infrastructures.

Snowflake uses **virtual compute instances** for its compute needs and a storage service for persistent storage of data.

**_Snowflake cannot be run on private cloud infrastructures (on-premises or hosted)_**
