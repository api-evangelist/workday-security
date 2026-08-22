# Workday Security (workday-security)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
