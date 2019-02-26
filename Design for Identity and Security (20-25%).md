# Design for Identity and Security (20-25%)

Start by completing the following course on openedx:
* [Designing for Identity and Security](https://aka.ms/openedx-AZ-301.1-about)

# Design Identity Management
May include but not limited to: Choose an identity management approach; design an identity delegation strategy, identity repository (including directory, application, systems, etc.); design self-service identity management and user and persona provisioning; define personas and roles; recommend appropriate access control strategy (e.g., attribute-based, discretionary access, history-based, identity-based, mandatory, organization-based, role-based, rule-based, responsibility-based).

**Note that the [Cloud Adoption Framework](https://docs.microsoft.com/en-us/azure/architecture/cloud-adoption/overview) and the [Azure security best practices and patterns](https://docs.microsoft.com/en-us/azure/security/security-best-practices-and-patterns) documentation are the key materials to review for this exam objective.**

* Choose an identity management approach
* Design an identity delegation strategy, identity repository (including directory, application, systems, etc.)
* Design self-service identity management and user and persona provisioning
* Define personas and roles
* Recommend appropriate access control strategy (e.g., attribute-based, discretionary access, history-based, identity-based, mandatory, organization-based, role-based, rule-based, responsibility-based)

	
## Design Authentication
May include but not limited to: Choose an authentication approach; design a single-sign on approach; design for IPSec, logon, multi-factor, network access, and remote authentication.
* [Choose an authentication approach](https://docs.microsoft.com/en-us/azure/architecture/multitenant-identity/authenticate)
* Design a single-sign on approach
    * (https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-sso) 
    * https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-sso-how-it-works 
    * https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-sso-user-privacy 
    * https://docs.microsoft.com/en-us/azure/active-directory/hybrid/how-to-connect-sso-quick-start 

* [Design for IPSec, logon, multi-factor, network access, and remote authentication]()

## Design Authorization
May include but not limited to: Choose an authorization approach; define access permissions and privileges; design secure delegated access (e.g., oAuth, OpenID, etc.); recommend when and how to use API Keys.

* Choose an authorization approach
    * (https://azure.microsoft.com/mediahandler/files/resourcefiles/security-best-practices-for-azure-solutions/Azure%20Security%20Best%20Practices.pdf
    * https://docs.microsoft.com/en-us/azure/security/azure-ad-choose-authn 
    * https://docs.microsoft.com/en-us/azure/security/security-best-practices-and-patterns 
    * https://docs.microsoft.com/en-us/azure/architecture/multitenant-identity/authorize 

* [Design secure delegated access (e.g., oAuth, OpenID, etc.)](https://docs.microsoft.com/en-us/azure/security/azure-security-threat-modeling-tool-authorization#principle-least-privilege)
* Recommend when and how to use API Keys
    * https://docs.microsoft.com/en-us/azure/api-management/api-management-key-concepts 
    * https://docs.microsoft.com/en-us/azure/api-management/api-management-howto-mutual-certificates 

## Design for Risk Prevention for Identity
May include but not limited to: Design a risk assessment strategy (e.g., access reviews, RBAC policies, physical access); evaluate agreements involving services or products from vendors and contractors; update solution design to address and mitigate changes to existing security policies, standards, guidelines and procedures.
* [Design a risk assessment strategy (e.g., access reviews, RBAC policies, physical access)](https://docs.microsoft.com/en-us/azure/architecture/reference-architectures/identity/)
* [Evaluate agreements involving services or products from vendors and contractors]()
* [Update solution design to address and mitigate changes to existing security policies, standards, guidelines and procedures]()

 
## Design a Monitoring Strategy for Identity and Security
May include but not limited to: Design for alert notifications; design an alert and metrics strategy; recommend authentication monitors.
 
* [Design for alert notifications]()
* [Design an alert and metrics strategy]()
* [Recommend authentication monitors]()
