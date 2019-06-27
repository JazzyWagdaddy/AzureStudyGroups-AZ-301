# Design for Identity and Security (20-25%)

Start by completing the following course on openedx:

* [Designing for Identity and Security](https://openedx.microsoft.com/courses/course-v1:Microsoft+AZ-301.1+2019_T1/course/)

## Design Identity Management

May include but not limited to: Choose an identity management approach; design an identity delegation strategy, identity repository (including directory, application, systems, etc.); design self-service identity management and user and persona provisioning; define personas and roles; recommend appropriate access control strategy (e.g., attribute-based, discretionary access, history-based, identity-based, mandatory, organization-based, role-based, rule-based, responsibility-based).

**Note that the [Cloud Adoption Framework](https://docs.microsoft.com/en-us/azure/architecture/cloud-adoption/overview) and the [Azure security best practices and patterns](https://docs.microsoft.com/en-us/azure/security/security-best-practices-and-patterns) documentation are the key materials to review for this exam objective. THey are relatively lengthy so please plan accordingly.**

* Choose an identity management approach
* Design an identity delegation strategy, identity repository (including directory, application, systems, etc.)
* Design self-service identity management and user and persona provisioning
* Define personas and roles
* Recommend appropriate access control strategy (e.g., attribute-based, discretionary access, history-based, identity-based, mandatory, organization-based, role-based, rule-based, responsibility-based)

## Design Authentication

May include but not limited to: Choose an authentication approach; design a single-sign on approach; design for IPSec, logon, multi-factor, network access, and remote authentication.

* Choose an authentication approach

  * [Choose the right authentication method for your Azure Active Directory hybrid identity solution](https://docs.microsoft.com/en-us/azure/security/azure-ad-choose-authn)
  * [What is password hash synchronization with Azure AD?](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/whatis-phs)
  * [User sign-in with Azure Active Directory Pass-through Authentication](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-pta)

* Design a single-sign on approach

  * [Azure Active Directory Seamless Single Sign-On](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-sso)
  * [Azure Active Directory Seamless Single Sign-On: Technical deep dive](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-sso-how-it-works )
  * [User Privacy and Azure AD Seamless Single Sign-On](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-sso-user-privacy )
  * [Azure Active Directory Seamless Single Sign-On: Quick start](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-sso-quick-start)
  * [Implement password hash synchronization with Azure AD Connect sync](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-password-hash-synchronization)
  * [Azure AD Connect and federation](https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-fed-whatis)
  * [Tutorial: Add an on-premises application for remote access through Application Proxy in Azure Active Directory](https://docs.microsoft.com/en-us/azure/active-directory/manage-apps/application-proxy-add-on-premises-application)

* Design for IPSec, logon, multi-factor, network access, and remote authentication
  * [Design for security in Azure](https://docs.microsoft.com/en-us/learn/modules/design-for-security-in-azure/)

## Design Authorization

May include but not limited to: Choose an authorization approach; define access permissions and privileges; design secure delegated access (e.g., oAuth, OpenID, etc.); recommend when and how to use API Keys.

* Choose an authorization approach

  * [Security best practices for Azure](https://azure.microsoft.com/mediahandler/files/resourcefiles/security-best-practices-for-azure-solutions/Azure%20Security%20Best%20Practices.pdf)
  * [Choose the right authentication method for your Azure Active Directory hybrid identity solution](https://docs.microsoft.com/en-us/azure/security/azure-ad-choose-authn )
  * [Azure security best practices and patterns](https://docs.microsoft.com/en-us/azure/security/security-best-practices-and-patterns)
  * [Role-based and resource-based authorization](https://docs.microsoft.com/en-us/azure/architecture/multitenant-identity/authorize )

* [Design secure delegated access (e.g., oAuth, OpenID, etc.)](https://docs.microsoft.com/en-us/azure/security/azure-security-threat-modeling-tool-authorization#principle-least-privilege)
* Recommend when and how to use API Keys
  * [What is API Management?](https://docs.microsoft.com/en-us/azure/api-management/api-management-key-concepts)
  * [How to secure back-end services using client certificate authentication in Azure API Management](https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-mutual-certificates )

## Design for Risk Prevention for Identity

May include but not limited to: Design a risk assessment strategy (e.g., access reviews, RBAC policies, physical access); evaluate agreements involving services or products from vendors and contractors; update solution design to address and mitigate changes to existing security policies, standards, guidelines and procedures.

* [Design a risk assessment strategy (e.g., access reviews, RBAC policies, physical access)](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/identity/)
* Evaluate agreements involving services or products from vendors and contractors
* Update solution design to address and mitigate changes to existing security policies, standards, guidelines and procedures

## Design a Monitoring Strategy for Identity and Security

May include but not limited to: Design for alert notifications; design an alert and metrics strategy; recommend authentication monitors.

* Design for alert notifications
  * [Stream Azure monitoring data to an event hub for consumption by an external tool](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/stream-monitoring-data-event-hubs)
* Design an alert and metrics strategy
  * [Sign-in activity reports in the Azure Active Directory portal](https://docs.microsoft.com/en-us/azure/active-directory/reports-monitoring/concept-sign-ins)
  * [Five steps to securing your identity infrastructure](https://docs.microsoft.com/en-us/azure/security/azure-ad-secure-steps)
  * [Audit activity reports in the Azure Active Directory portal](https://docs.microsoft.com/en-us/azure/active-directory/reports-monitoring/concept-audit-logs)
* Recommend authentication monitors
  * [Azure AD Password Protection monitoring and logging](https://docs.microsoft.com/en-us/azure/active-directory/authentication/howto-password-ban-bad-on-premises-monitor)
  * [Azure AD activity logs in Azure Monitor](https://docs.microsoft.com/en-us/azure/active-directory/reports-monitoring/concept-activity-logs-azure-monitor)
  * [Optimize your Active Directory environment with the Active Directory Health Check solution in Azure Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/insights/ad-assessment)

For this exam objective please complete the following:

* [Security, responsibility and trust in Azure](https://docs.microsoft.com/en-us/learn/modules/intro-to-security-in-azure/)
* [Design for security in Azure](https://docs.microsoft.com/en-us/learn/modules/design-for-security-in-azure/)
