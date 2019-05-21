# Design a Business Continuity Strategy (15-20%)

*Consider completing this course on OpenEdx: [Designing for Deployment, Migration, and Integration](https://openedx.microsoft.com/courses/course-v1:Microsoft+AZ-301.3+2019_T1/course/).*

*Also consider reading the [Disaster recovery for Azure applications](https://docs.microsoft.com/en-us/azure/architecture/resiliency/disaster-recovery-azure-applications).*

## Design a Site Recovery Strategy
May include but not limited to: Design a recovery solution; design a site recovery replication policy; design for site recovery capacity and for storage replication; design site failover and failback (planned/unplanned); design the site recovery network; recommend recovery objectives (e.g., Azure, on-prem, hybrid, Recovery Time Objective (RTO), Recovery Level Objective (RLO), Recovery Point Objective (RPO)); identify resources that require site recovery; identify supported and unsupported workloads; recommend a geographical distribution strategy

Read the [Azure Site Recovery Overview](https://docs.microsoft.com/en-us/azure/site-recovery/site-recovery-overview) and [Design a recovery solution](https://docs.microsoft.com/en-us/azure/architecture/resiliency/disaster-recovery-azure-applications) articles.

* [Design a site recovery replication policy](https://docs.microsoft.com/en-us/azure/site-recovery/vmware-azure-set-up-replication)
[Design for site recovery capacity and for storage replication](https://docs.microsoft.com/en-us/azure/site-recovery/site-recovery-plan-capacity-vmware)
* [Design site failover and failback (planned/unplanned)](https://docs.microsoft.com/en-us/azure/site-recovery/site-recovery-create-recovery-plans)
* Design the site recovery Network
    * [Azure to Azure](https://docs.microsoft.com/en-us/azure/site-recovery/azure-to-azure-about-networking)
    * [Azure Traffic Manager with Site Recovery](https://docs.microsoft.com/en-us/azure/site-recovery/concepts-traffic-manager-with-site-recovery)
    * [Azure ExpressRoute with Azure Site Recovery](https://docs.microsoft.com/en-us/azure/site-recovery/concepts-expressroute-with-site-recovery)
    * [Network Security Groups with Azure Site Recovery](https://docs.microsoft.com/en-us/azure/site-recovery/concepts-network-security-group-with-site-recovery)
    * [Setup public IP addresses after failover](https://docs.microsoft.com/en-us/azure/site-recovery/concepts-public-ip-address-with-site-recovery)
* Recommend recovery objectives (e.g., Azure, on-prem, hybrid, Recovery Time Objective (RTO) Recovery Level Objective (RLO), Recovery Point Objective (RPO))  
    * [About Site Recovery](https://docs.microsoft.com/en-us/azure/site-recovery/site-recovery-overview)
    * [Recovery Level Objective (RLO), Recovery Point Objective (RPO))](https://docs.microsoft.com/en-us/azure/architecture/resiliency/)
    * [Identify resources that require site recovery](https://docs.microsoft.com/en-us/azure/sql-data-warehouse/sql-data-warehouse-overview-what-is)
    * [Identify supported and unsupported workloads; recommend a geographical distribution strategy](https://docs.microsoft.com/en-us/azure/sql-data-warehouse/massively-parallel-processing-mpp-architecture)
    * [Best practices for Azure SQL Data Warehouse](https://docs.microsoft.com/en-us/azure/sql-data-warehouse/sql-data-warehouse-best-practices)

## Design for High Availability 
May include but not limited to: Design for application redundancy, autoscaling, data center and fault domain redundancy, and network redundancy; identify resources that require high availability; identify storage types for high availability

Read the [Availability Checklist](https://docs.microsoft.com/en-us/azure/architecture/checklist/availability)
* [Design for application redundancy](https://docs.microsoft.com/en-us/azure/architecture/checklist/resiliency)
* [Autoscaling](https://docs.microsoft.com/en-us/azure/architecture/best-practices/auto-scaling)
* [Data center and fault domain redundancy](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/manage-availability)
* [Identify resources that require high availability](https://docs.microsoft.com/en-us/azure/architecture/checklist/resiliency-per-service)
* [Identify storage types for high availability](https://docs.microsoft.com/en-us/azure/architecture/checklist/resiliency)

## Design a Data Archiving Strategy
May include but not limited to: Recommend storage types and methodology for data archiving; identify requirements for data archiving and business compliance requirements for data archiving; identify SLA(s) for data archiving.

* [Recommend storage types and methodology for data archiving](https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-storage-tiers)
* [Identify requirements for data archiving and business compliance requirements for data archiving](https://docs.microsoft.com/en-us/azure/storage/common/storage-compliance-offerings)
* [Identify SLA(s) for data archiving](https://azure.microsoft.com/en-us/support/legal/sla/storage/v1_2/)
