# Design a Data Platform Solution (15-20%)

*Consider completing this course on OpenEdx: [Designing a Data Platform Solution](https://openedx.microsoft.com/courses/course-v1:Microsoft+AZ-301.2+2019_T1/course/).*

*Also consider reading the [Azure Application Architecture Guide](https://docs.microsoft.com/en-us/azure/architecture/guide/).*

## Design a Data Management Strategy

May include but not limited to: Choose between managed and unmanaged data store; choose between relational and non-relational databases; design data auditing and caching strategies; identify data attributes (e.g., relevancy, structure, frequency, size, durability, etc.); recommend Database Transaction Unit (DTU) sizing; design a data retention policy; design for data availability, consistency, and durability; design a data warehouse strategy.

Read the [Azure Data Architecture Guide](https://docs.microsoft.com/en-us/azure/architecture/data-guide/)

* [Choose the right data store](https://docs.microsoft.com/en-us/azure/architecture/guide/technology-choices/data-store-overview)
* [Criteria for choosing a data store](https://docs.microsoft.com/en-us/azure/architecture/guide/technology-choices/data-store-comparison)
* Choose between relational and non-relational databases
    * [Find the database product you need](https://azure.microsoft.com/en-us/product-categories/databases/)
    * [Azure Strategy and Implementation Guide](https://azure.microsoft.com/en-us/resources/azure-strategy-and-implementation-guide/en-us/)
* Design data auditing and caching strategies
    * [Get started with SQL database auditing](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-auditing)
    * [Caching](https://docs.microsoft.com/en-us/azure/architecture/best-practices/caching)
* Identify data attributes (e.g., relevancy, structure, frequency, size, durability, etc.)
* [Recommend Database Transaction Unit (DTU) sizing](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-service-tiers-dtu)
* [Design a data retention policy](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-long-term-retention)
* Design for data availability, consistency, and durability
* Design a data warehouse strategy
    * [What is Azure SQL Data Warehouse?](https://docs.microsoft.com/en-us/azure/sql-data-warehouse/sql-data-warehouse-overview-what-is)
    * [Azure SQL Data Warehouse - Massively parallel processing (MPP) architecture](https://docs.microsoft.com/en-us/azure/sql-data-warehouse/massively-parallel-processing-mpp-architecture)
    * [Best practices for Azure SQL Data Warehouse](https://docs.microsoft.com/en-us/azure/sql-data-warehouse/sql-data-warehouse-best-practices)

## Design a Data Protection Strategy
May include but not limited to: Recommend geographic data storage; design an encryption strategy for data at rest, for data in transmission, and for data in use; design a scalability strategy for data; design secure access to data; design a data loss prevention (DLP) policy.

*Read [Define data protection strategy for your hybrid identity solution](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/plan-hybrid-identity-design-considerations-data-protection-strategy)*
*  Recommend geographic data storage
* Design an encryption strategy for data at rest, for data in transmission, and for data in use
    * [Azure encryption overview](https://docs.microsoft.com/en-us/azure/security/security-azure-encryption-overview)
    * [Transparent Data Encryption (TDE)](https://docs.microsoft.com/en-us/sql/relational-databases/security/encryption/transparent-data-encryption?view=sql-server-2017)
    * [Always Encrypted (Database Engine)](https://docs.microsoft.com/en-us/sql/relational-databases/security/encryption/always-encrypted-database-engine?view=sql-server-2017)
* Design a data loss prevention (DLP) policy
* Design a scalability strategy for data
* Design secure access to data
    * [Row-Level Security](https://docs.microsoft.com/en-us/sql/relational-databases/security/row-level-security?view=sql-server-2017)
    * [Dynamic Data Masking](https://docs.microsoft.com/en-us/sql/relational-databases/security/dynamic-data-masking?view=sql-server-2017)
    * [Azure database security best practices](https://docs.microsoft.com/en-us/azure/security/azure-database-security-best-practices)


## Design and Document Data Flows

May include but not limited to: Identify data flow requirements; create a data flow diagram; design a data flow to meet business requirements; design a data import and export strategy.

*Review the [Azure Data Explorer](https://docs.microsoft.com/en-us/azure/data-explorer/) documentation and [Azure Data Factory Mapping Data Flow Select Transformation](https://docs.microsoft.com/en-us/azure/data-factory/data-flow-select).*
* Identify data flow requirements
    * [What are Mapping Data Flows?](https://docs.microsoft.com/en-us/azure/data-factory/concepts-data-flow-overview)
* Create a data flow diagram
    * [What are Mapping Data Flows?](https://docs.microsoft.com/en-us/azure/data-factory/concepts-data-flow-overview)
* Design a data flow to meet business requirements
    * [Mapping Data Flow Schema Drift](https://docs.microsoft.com/en-us/azure/data-factory/concepts-data-flow-schema-drift)
* Design a data import and export strategy
    * [Copy data from Azure Blob storage to a SQL database by using the Copy Data tool](https://docs.microsoft.com/en-us/azure/data-factory/tutorial-copy-data-tool)
    * [Copy data from an on-premises SQL Server database to Azure Blob storage by using the Copy Data tool](https://docs.microsoft.com/en-us/azure/data-factory/tutorial-hybrid-copy-data-tool)
    * [Copy multiple tables in bulk by using Azure Data Factory](https://docs.microsoft.com/en-us/azure/data-factory/tutorial-bulk-copy-portal)


## Design a Monitoring Strategy for the Data Platform
May include but not limited to: Design for alert notifications; design an alert and metrics strategy.

* Design for alert notifications
    * [Consume monitoring data from Azure](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/data-sources-reference#options-for-data-consumption)
* Design an alert and metrics strategy
    * [Monitoring and diagnostics](https://docs.microsoft.com/en-us/azure/architecture/best-practices/monitoring)  *Note this is a long read*
    * [Find and apply performance recommendations](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-advisor-portal)

