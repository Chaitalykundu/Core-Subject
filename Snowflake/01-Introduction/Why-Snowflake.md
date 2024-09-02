# Overview

- Why Snowflake
- On-premise Meaning
- Workload isolation
- Access control
- Enterprise data warehouse vs data marts

&nbsp;

&nbsp;

&nbsp;

# Why Snowflake

- Snowflake is relatively new and fresh in cloud data warehouse space
- It is purposely built only for cloud platform (AWS, Azure, GCP,)
- Brings many unique features beside workload isolation like -
  - Time Travel feature
  - Data Sharing feature
  - Data Cloning feature (Zero copy clone)
  - Readers account (for non snowflake users)
  - Out of box security (RBAC / DAC) / Encryption / Column level masking / Row level security
  - All popular connector (JDBC / ODBC / Spark and many more)
  - Pay per second billing model (not upfront investment and only pay for actual usage)

&nbsp;

&nbsp;

# On-premise Meaning

"On-premise" refers to a deployment and licensing model for software that is installed and runs on a company's own computers, rather than at a remote facility. The term is also abbreviated as "on-prem".
On-premise software can be hosted on the company's own hardware, either in their own premises or by renting space in a data center. The company can choose to manage and maintain the servers themselves, or they can hire an external IT provider to do so.

&nbsp;

&nbsp;

# Workload isolation

Workload isolation means resources are reserved, exclusively, for a workload group.

Workload Isolation enables you to create and manage isolated environments to contain newly created or migrated workloads.

&nbsp;

&nbsp;

# Access control

Access Control Models allow organizations to grant user permissions and enforce access policies.

There are four types of access control methods: - Mandatory Access Control (MAC), - Role-Based Access Control (RBAC), - Discretionary Access Control (DAC), - Rule-Based Access Control (RBAC or RB-RBAC).

A method is chosen based on the level of access needed by each user, security requirement, infrastructure, etc.

&nbsp;

&nbsp;

# Enterprise data warehouse vs data marts

An enterprise data warehouse stores data from all of an organization's business operations in a single, centralized platform.

On the other hand, data marts are smaller warehousing systems that contain subsets of data for particular departments, business units or groups of users.
