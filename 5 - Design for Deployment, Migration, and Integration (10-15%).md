# Design for Deployment, Migration, and Integration aka Know How to Design Anything in Azure (10-15%) 

Given how broad this chapter is you may want to review the massive [Azure Architecture Center](https://docs.microsoft.com/en-us/azure/architecture/).

## Design Deployments
* Design a:
    * [Compute](https://docs.microsoft.com/en-us/azure/architecture/guide/technology-choices/compute-overview)
    * [Container](https://docs.microsoft.com/en-us/azure/architecture/example-scenario/apps/devops-with-aks)
        * [Deployment Strategies Defined](http://blog.itaysk.com/2017/11/20/deployment-strategies-defined)
    * [Data platform](https://docs.microsoft.com/en-us/azure/architecture/data-guide/)
    * Messaging solution
    * Storage
        * [Deciding when to use Azure Blobs, Azure Files, or Azure Disks](https://docs.microsoft.com/en-us/azure/storage/common/storage-decide-blobs-files-disks)
        * [Design and Implement a Storage Strategy](https://www.lynda.com/Azure-tutorials/Microsoft-Azure-Design-Implement-Storage-Strategy/534642-2.html)
    * Web app
        * [Run a basic web application in Azure](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/app-service-web-app/basic-web-app)
        * [Improve scalability in an Azure web application](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/app-service-web-app/scalable-web-app)
        * [Multitier web application built for high availability and disaster recovery on Azure](https://docs.microsoft.com/en-us/azure/architecture/example-scenario/infrastructure/multi-tier-app-disaster-recovery)
    * Service deployment strategy
        * [Azure Strategy and Implementation Guide](https://azure.microsoft.com/en-us/resources/azure-strategy-and-implementation-guide/en-us/) *(glance over this)*

## Design Migrations

### Required reading for this section:
* *[Best practices for securing and managing workloads migrated to Azure](https://docs.microsoft.com/en-us/azure/migrate/migrate-best-practices-security-management)*
* *[Contoso Migration Series](https://docs.microsoft.com/en-us/azure/migrate/contoso-migration-overview)*

* Recommend a migration strategy
    * [The 5 Rs of rationalization](https://docs.microsoft.com/en-us/azure/architecture/cloud-adoption/digital-estate/5-rs-of-rationalization)

* Design data import/export strategies during migration
* Determine the appropriate application migration, data transfer, and network connectivity method
* Determine migration scope, including redundant, related, trivial, and outdated data
* Determine application and data compatibility


## Design an API Integration Strategy
* [Design an API gateway strategy](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)
* [Determine policies for internal and external consumption of APIs](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-implementation)
* Recommend a hosting structure for API management (*Use same link as above*)