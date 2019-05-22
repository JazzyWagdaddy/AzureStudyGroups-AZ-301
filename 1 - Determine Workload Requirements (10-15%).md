# Determine Workload Requirements (10-15%)

## Gather Information and Requirements 
May include but not limited to: Identify compliance requirements, identity and access management infrastructure, and service-oriented architectures (e.g., integration patterns, service design, service discoverability); identify accessibility (e.g. Web Content Accessibility Guidelines), availability (e.g. Service Level Agreement), capacity planning and scalability, deploy-ability (e.g., repositories, failback, slot-based deployment), configurability, governance, maintainability (e.g. logging, debugging, troubleshooting, recovery, training), security (e.g. authentication, authorization, attacks), and sizing (e.g. support costs, optimization) requirements; recommend changes during project execution (ongoing); evaluate products and services to align with solution; create testing scenarios.

* [Identify compliance requirements](https://docs.microsoft.com/en-us/azure/architecture/cloud-adoption/ready/azure-readiness-guide/govern-org-compliance?tabs=AzurePolicy)
* Identity and access management
    * [What is Azure AD?](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/active-directory-whatis)
    * [What is Azure Active Directory B2C?](https://docs.microsoft.com/en-us/azure/active-directory-b2c/active-directory-b2c-overview)
    * [Azure Active Directory (AD) Domain Services](https://docs.microsoft.com/en-us/azure/active-directory-domain-services/active-directory-ds-overview)
* Service-oriented architectures (e.g., integration patterns, service design, service discoverability)
    * [Architecture Center](https://docs.microsoft.com/en-us/azure/architecture)
    * [Service-oriented architecture](https://docs.microsoft.com/en-us/dotnet/standard/microservices-architecture/architect-microservice-container-applications/service-oriented-architecture)
    * [What is Service Fabric Mesh?](https://docs.microsoft.com/en-us/azure/service-fabric-mesh/service-fabric-mesh-overview)
* [Identify accessibility (e.g. Web Content Accessibility Guidelines)](https://www.essentialaccessibility.com/blog/web-content-accessibility-guidelines-wcag/)	
* [Availability (e.g. Service Level Agreement)	](https://azure.microsoft.com/en-us/support/legal/sla/summary/)
* [Capacity planning and scalability](https://azure.microsoft.com/en-us/pricing/details/devops/azure-devops-services/)
* [Deploy-ability (e.g., repositories, failback, slot-based deployment)	](https://docs.microsoft.com/en-us/azure/app-service/deploy-staging-slots)
* [Configurability](https://docs.microsoft.com/en-us/azure/automation/automation-intro)
* Governance
    * https://docs.microsoft.com/en-us/azure/governance/
    * https://docs.microsoft.com/en-us/azure/governance/azure-management 
    * https://docs.microsoft.com/en-us/azure/governance/policy/overview 
* Maintainability (e.g. logging, debugging, troubleshooting, recovery, training)
    * https://docs.microsoft.com/en-us/azure/security/azure-log-audit 
    * https://docs.microsoft.com/en-us/azure/devops/learn/what-is-monitoring
* [Security (e.g. authentication, authorization, attacks)](https://docs.microsoft.com/en-us/azure/security-center/security-center-intro)
* Sizing (e.g. support costs, optimization) requirements	
    * https://azure.microsoft.com/en-us/pricing/calculator/
    * https://docs.microsoft.com/en-us/azure/cost-management/overview
    * https://docs.microsoft.com/en-us/azure/cost-management/quick-acm-cost-analysis 
* Recommend changes during project execution (ongoing) & Evaluate products and services to align with solution	
    * https://docs.microsoft.com/en-us/azure/devops/learn/what-is-continuous-delivery
    * https://azure.microsoft.com/en-us/services/devops/?&OCID=AID736750_SEM_SzJu1csj&MarinID=SzJu1csj_78821311260582_%2Bazure%20%2Bdevops_bb_c__1261139985823089_kwd-78821448773763:loc-190_
* [Create testing scenarios](https://azure.microsoft.com/en-us/solutions/dev-test/%23references)

## Optimize Consumption Strategy 
May include but not limited to: Optimize app service, compute, identity, network, and storage costs.

* Optimize app service
    * https://docs.microsoft.com/en-us/azure/app-service/overview
    * https://docs.microsoft.com/en-us/azure/app-service/environment/intro
    * https://docs.microsoft.com/en-us/azure/app-service/overview-compare
* [Compute](https://docs.microsoft.com/en-us/azure/app-service/app-service-best-practices?toc=%2fazure%2fapp-service%2fenvironment%2ftoc.json)
* [Identity](https://docs.microsoft.com/en-us/azure/active-directory/develop/)	
* [Network](https://docs.microsoft.com/en-us/azure/app-service/environment/network-info)
* [Storage Costs](https://azure.microsoft.com/en-us/pricing/details/storage/blobs/)	

## Design an Auditing and Monitoring Strategy 
May include but not limited to: Define logical groupings (tags) for resources to be monitored; determine levels and storage locations for logs; plan for integration with monitoring tools; recommend appropriate monitoring tool(s) for a solution; specify mechanism for event routing and escalation; design auditing for compliance requirements; design auditing policies and traceability requirements. 

* [Define logical groupings (tags) for resources to be monitored](https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-using-tags)
* [Determine levels and storage locations for logs](https://docs.microsoft.com/en-us/rest/api/storageservices/enabling-storage-logging-and-accessing-log-data)
* [Plan for integration with monitoring tools](https://azure.microsoft.com/en-us/blog/use-azure-monitor-to-integrate-with-siem-tools/)
* [Recommend appropriate monitoring tool(s) for a solution](https://docs.microsoft.com/en-us/azure/azure-monitor/overview)
* [Specify mechanism for event routing and escalation](https://docs.microsoft.com/en-us/azure/event-grid/overview)
* [Design auditing for compliance requirements](https://docs.microsoft.com/en-us/azure/devops/organizations/security/?view=azure-devops)
* [Design auditing policies and traceability requirements](https://azure.microsoft.com/en-us/services/devops/pipelines/)





