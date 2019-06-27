# Design for Deployment, Migration, and Integration aka Know How to Design Anything in Azure (10-15%)

Given how broad this chapter is you may want to review the massive [Azure Architecture Center](https://docs.microsoft.com/en-us/azure/architecture/).

## Design Deployments

Design a compute, container, data platform, messaging solution, storage, and web app and service deployment strategy.

* Design a:
  * Compute
    * [Overview of Azure compute options](https://docs.microsoft.com/en-us/azure/architecture/guide/technology-choices/compute-overview)
  * Container
    * [What is Azure Container Instances?](https://docs.microsoft.com/en-us/azure/container-instances/container-instances-overview)
    * [Deployment Strategies Defined](http://blog.itaysk.com/2017/11/20/deployment-strategies-defined)
  * Data platform
    * [Azure Data Architecture Guide](https://docs.microsoft.com/en-us/azure/architecture/data-guide/)
  * Messaging solution
    * [What are Azure Queues?](https://docs.microsoft.com/en-us/azure/storage/queues/storage-queues-introduction)
  * Storage
    * [Deciding when to use Azure Blobs, Azure Files, or Azure Disks](https://docs.microsoft.com/en-us/azure/storage/common/storage-decide-blobs-files-disks)
    * [Design and Implement a Storage Strategy](https://www.lynda.com/Azure-tutorials/Microsoft-Azure-Design-Implement-Storage-Strategy/534642-2.html)
    * [Introduction to Azure Blob storage](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blobs-introduction)
  * Web app
    * [Run a basic web application in Azure](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/app-service-web-app/basic-web-app)
    * [Improve scalability in an Azure web application](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/app-service-web-app/scalable-web-app)
    * [Multitier web application built for high availability and disaster recovery on Azure](https://docs.microsoft.com/en-us/azure/architecture/example-scenario/infrastructure/multi-tier-app-disaster-recovery)
  * Service deployment strategy
    * [Azure Strategy and Implementation Guide](https://azure.microsoft.com/en-us/resources/azure-strategy-and-implementation-guide/en-us/)
    * [What is Azure Logic Apps?](https://docs.microsoft.com/en-us/azure/logic-apps/logic-apps-overview)
    * [An introduction to Azure Functions](https://docs.microsoft.com/en-us/azure/azure-functions/functions-overview)
    * [WebJobs in Azure App Service](https://docs.microsoft.com/en-us/azure/app-service/webjobs-create)

## Design Migrations

### Required reading for this section

 *[Best practices for securing and managing workloads migrated to Azure](https://docs.microsoft.com/en-us/azure/migrate/migrate-best-practices-security-management)* and *[Contoso Migration Series](https://docs.microsoft.com/en-us/azure/migrate/contoso-migration-overview)*

* Recommend a migration strategy
  * [The 5 Rs of rationalization](https://docs.microsoft.com/en-us/azure/architecture/cloud-adoption/digital-estate/5-rs-of-rationalization)
  * [Choose the right SQL Server option in Azure](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-paas-vs-sql-server-iaas)
* Design data import/export strategies during migration
* Determine the appropriate application migration, data transfer, and network connectivity method
  * [Data transfer for large datasets with moderate to high network bandwidth](https://docs.microsoft.com/en-us/azure/storage/common/storage-solution-large-dataset-moderate-high-network?toc=%2fazure%2fstorage%2fblobs%2ftoc.json)
  * [Choose an Azure solution for data transfer](https://docs.microsoft.com/en-us/azure/storage/common/storage-choose-data-transfer-solution?toc=%2fazure%2fstorage%2fblobs%2ftoc.json)
* Determine migration scope, including redundant, related, trivial, and outdated data
* Determine application and data compatibility
  * [Orchestrating microservices and multi-container applications for high scalability and availability](https://docs.microsoft.com/en-us/dotnet/standard/microservices-architecture/architect-microservice-container-applications/scalable-available-multi-container-microservice-applications)
  * [Azure Container Instances and container orchestrators](https://docs.microsoft.com/en-us/azure/container-instances/container-instances-orchestrator-relationship)
  * [Choosing a batch processing technology in Azure](https://docs.microsoft.com/en-us/azure/architecture/data-guide/technology-choices/batch-processing)

## Design an API Integration Strategy

* [Design an API gateway strategy](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)
* [Determine policies for internal and external consumption of APIs](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-implementation)
* Recommend a hosting structure for API management
  * [API Management access restriction policies](https://docs.microsoft.com/en-us/azure/api-management/api-management-access-restriction-policies)
  * [Advanced request throttling with Azure API Management](https://docs.microsoft.com/en-us/azure/api-management/api-management-sample-flexible-throttling)
