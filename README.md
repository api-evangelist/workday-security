# Workday Security (workday-security)

Collection of Workday Security APIs for managing authentication, authorization, and security configurations including identity management, security groups, audit logging, privacy, and user activity monitoring.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/workday-security/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/workday-security/refs/heads/main/apis.yml)

## Tags

- Access Control
- Audit
- Authentication
- Compliance
- Enterprise
- Identity Management
- Privacy
- SAML
- Security
- SSO

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Workday Authentication API

Manage authentication methods, SSO configuration, and session management. Supports WS-Security authentication with Integration System Users and OAuth 2.0 token-based authentication for REST API access.

- **Human URL:** [https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Authentication.html](https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Authentication.html)
- **Base URL:** `https://wd2-impl-services1.workday.com/ccx/service/`

#### Tags

- Authentication
- OAuth
- SAML
- Security
- SSO

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Authentication.html)
- [OpenAPI](https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Authentication_OpenAPI.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [W S D L](https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Authentication.wsdl)
- [Authentication](https://doc.workday.com/admin-guide/en-us/workday-rest-api/workday-rest-api-authentication.html)
- [Postman Collection](collections/workday-security-audit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-security-audit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-security-authentication.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-security-authentication.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-security-identity-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-security-identity-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-security-security-groups.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-security-security-groups.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workday Identity Management API

Manage user identities, roles, and access permissions within Workday. Provides operations for tracking Workday account signons and identifying unauthorized authentication attempts, including Get_Workday_Account_Signons and Get_Unidentified_Signons operations.

- **Human URL:** [https://community.workday.com/sites/default/files/file-hosting/productionapi/Identity_Management/v45.2/Identity_Management.html](https://community.workday.com/sites/default/files/file-hosting/productionapi/Identity_Management/v45.2/Identity_Management.html)
- **Base URL:** `https://wd2-impl-services1.workday.com/ccx/service/`

#### Tags

- Access Management
- Identity
- Security
- Signons

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Identity_Management.html)
- [OpenAPI](https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Identity_Management_OpenAPI.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [W S D L](https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Identity_Management.wsdl)
- [Reference](https://community.workday.com/sites/default/files/file-hosting/productionapi/Identity_Management/v45.2/Identity_Management.html)
- [Postman Collection](collections/workday-security-audit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-security-audit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-security-authentication.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-security-authentication.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-security-identity-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-security-identity-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-security-security-groups.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-security-security-groups.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workday Security Groups API

Manage security groups, domain security policies, and security group memberships. Controls access to securable items within Workday domains and business processes through Integration System Security Groups and role-based permission assignments.

- **Human URL:** [https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Security_Groups.html](https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Security_Groups.html)
- **Base URL:** `https://wd2-impl-services1.workday.com/ccx/service/`

#### Tags

- Domain Security
- Groups
- Permissions
- Security

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Security_Groups.html)
- [OpenAPI](https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Security_Groups_OpenAPI.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [W S D L](https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Security_Groups.wsdl)
- [Postman Collection](collections/workday-security-audit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-security-audit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-security-authentication.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-security-authentication.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-security-identity-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-security-identity-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-security-security-groups.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-security-security-groups.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workday Audit and Compliance API

Access audit logs, security reports, and compliance data. Provides programmatic access to audit trail information for security monitoring, regulatory compliance, and governance reporting within Workday.

- **Human URL:** [https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Audit.html](https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Audit.html)
- **Base URL:** `https://wd2-impl-services1.workday.com/ccx/service/`

#### Tags

- Audit
- Compliance
- Logging
- Security

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Audit.html)
- [OpenAPI](https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Audit_OpenAPI.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [W S D L](https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Audit.wsdl)
- [Postman Collection](collections/workday-security-audit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-security-audit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-security-authentication.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-security-authentication.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-security-identity-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-security-identity-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-security-security-groups.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-security-security-groups.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workday Privacy API

Manage data privacy settings, consent, and data subject requests. Supports GDPR and other data protection regulation compliance through programmatic access to privacy controls and data governance workflows.

- **Human URL:** [https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Privacy.html](https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Privacy.html)
- **Base URL:** `https://wd2-impl-services1.workday.com/ccx/service/`

#### Tags

- Data Protection
- GDPR
- Privacy
- Security

#### Properties

- [Documentation](https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Privacy.html)
- [OpenAPI](https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Privacy_OpenAPI.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [W S D L](https://community.workday.com/sites/default/files/file-hosting/productionapi/Security/v44.0/Privacy.wsdl)
- [Postman Collection](collections/workday-security-audit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-security-audit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-security-authentication.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-security-authentication.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-security-identity-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-security-identity-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-security-security-groups.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-security-security-groups.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Workday User Activity Logging API

REST API for retrieving user activity logs and signon data from a Workday tenant. Returns detailed JSON records of user actions including task information, timestamps, IP addresses, activity actions, system accounts, and session identifiers. Used by SIEM platforms for security monitoring.

- **Human URL:** [https://doc.workday.com/admin-guide/en-us/integrations/workday-rest-api/rest-api-guides/user-activity-logging-rest-api/mhr1626995534900.html](https://doc.workday.com/admin-guide/en-us/integrations/workday-rest-api/rest-api-guides/user-activity-logging-rest-api/mhr1626995534900.html)
- **Base URL:** `https://wd2-impl-services1.workday.com/ccx/api/privacy/v1/`

#### Tags

- Activity Logging
- Audit
- Security
- SIEM
- Signons

#### Properties

- [Documentation](https://doc.workday.com/admin-guide/en-us/integrations/workday-rest-api/rest-api-guides/user-activity-logging-rest-api/mhr1626995534900.html)
- [Authentication](https://doc.workday.com/admin-guide/en-us/workday-rest-api/workday-rest-api-authentication.html)
- [Postman Collection](collections/workday-security-audit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-security-audit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-security-authentication.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-security-authentication.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-security-identity-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-security-identity-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/workday-security-security-groups.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/workday-security-security-groups.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://community.workday.com)
- [Getting Started](https://community.workday.com/articles/1317963)
- [Authentication  Guide](https://community.workday.com/articles/1311418)
- [Authentication](https://doc.workday.com/admin-guide/en-us/workday-rest-api/workday-rest-api-authentication.html)
- [Best  Practices](https://community.workday.com/articles/security-best-practices)
- [Documentation](https://community.workday.com/api)
- [Reference](https://community.workday.com/sites/default/files/file-hosting/productionapi/index.html)
- [Rate Limits](https://community.workday.com/articles/api-rate-limits)
- [Status Page](https://status.workday.com)
- [Support](https://www.workday.com/en-us/customer-experience/support.html)
- [Website](https://www.workday.com)
- [Terms of Service](https://www.workday.com/en-us/legal.html)
- [Privacy Policy](https://www.workday.com/en-us/privacy.html)
- [Security](https://www.workday.com/en-us/why-workday/trust/security.html)
- [Compliance](https://www.workday.com/en-us/why-workday/trust/compliance.html)
- [Blog](https://blog.workday.com/en-us/application-development.html)
- [GitHub Organization](https://github.com/workday)
- [Sign Up](https://resourcecenter.workday.com/)
- [Login](https://www.myworkday.com)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
