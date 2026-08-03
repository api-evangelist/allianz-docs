# Allianz (allianz-docs)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Allianz is one of the world's largest insurance and financial services companies, serving over 86 million customers worldwide. Allianz offers developer APIs across multiple product lines including insurance quoting, policy management, claims, and trade credit services, enabling partners and distributors to integrate Allianz insurance products directly into their platforms.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/allianz-docs/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Financial Services, Insurance, Asset Management

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Allianz API Connect
Allianz API Connect provides APIs for Australian insurance products including home and contents, landlord, and comprehensive car insurance. APIs support price estimation, quoting, lead referral, and certificate of currency retrieval for partner integrations.

**Human URL:** [https://www.allianz.com.au/about-us/work-with-us/partners/api-connect.html](https://www.allianz.com.au/about-us/work-with-us/partners/api-connect.html)

#### Tags:

 - Insurance, Quoting, Policy, Australia

#### Properties

- [Documentation](https://www.allianz.com.au/about-us/work-with-us/partners/api-connect.html)
- [APIReference](https://www.allianz.com.au/about-us/work-with-us/partners/api-connect/our-apis.html)
- [OpenAPI](openapi/allianz-api-connect.yaml)
- [JSONSchema](json-schema/api-connect-price-estimate-response-schema.json)
- [JSONSchema](json-schema/api-connect-policy-details-response-schema.json)
- [JSONSchema](json-schema/api-connect-certificate-of-currency-schema.json)
- [JSONStructure](json-structure/api-connect-price-estimate-response-structure.json)
- [JSONStructure](json-structure/api-connect-policy-details-response-structure.json)
- [JSONStructure](json-structure/api-connect-certificate-of-currency-structure.json)
- [JSONLD](json-ld/allianz-api-connect-context.jsonld)
- [Example](examples/api-connect-price-estimate-response-example.json)
- [Example](examples/api-connect-certificate-of-currency-example.json)

### Allianz Partners API
The Allianz Partners API Management portal provides insurance and assistance product APIs covering the full customer journey. APIs support policy purchase, change, and cancellation operations in XML and JSON formats. Access requires contractual partnership agreement with Allianz.

**Human URL:** [https://developer.allianz-assistance.ca/](https://developer.allianz-assistance.ca/)

#### Tags:

 - Insurance, Assistance, Policy Management

#### Properties

- [Portal](https://developer.allianz-assistance.ca/)
- [GettingStarted](https://developer.allianz-assistance.ca/get-started)

### Allianz Global API
The Allianz Global API Portal provides enterprise insurance APIs for registered business partners. The portal uses Apigee Edge for API key management and OAuth2 for authentication. Most API documentation is restricted to contractual partners.

**Human URL:** [https://global.apis.allianz.com/api-catalog](https://global.apis.allianz.com/api-catalog)

#### Tags:

 - Insurance, Global, Enterprise

#### Properties

- [Portal](https://global.apis.allianz.com/api-catalog)
- [Contact](https://global.apis.allianz.com/contact)

## Common Properties

- [Website](https://www.allianz.com/)
- [GitHubOrganization](https://github.com/allianz)
- [Support](https://global.apis.allianz.com/contact)
- [SpectralRules](rules/allianz-docs-spectral-rules.yml)
- [Vocabulary](vocabulary/allianz-vocabulary.yaml)
- [NaftikoCapability](capabilities/insurance-partner-integration.yaml)

## Features

| Name | Description |
|------|-------------|
| Insurance Quoting | APIs for generating price estimates and quotes for home, auto, and other insurance products enabling partner-embedded quoting flows. |
| Policy Management | Purchase, change, and cancel insurance policies programmatically through REST and SOAP-compatible API interfaces. |
| Claims Integration | Retrieve and manage insurance claims data, enabling ERP and enterprise system integration for claims tracking. |
| Partner Distribution | Enable distributors, brokers, and financial institutions to embed Allianz insurance products into their customer journeys. |
| OAuth2 Authentication | Secure API authentication using OAuth2 client credentials flow for programmatic access to partner APIs. |
| Multi-Format Support | APIs support both XML and JSON formats with content negotiation for flexible enterprise integration. |

## Use Cases

| Name | Description |
|------|-------------|
| Embedded Insurance | Financial institutions and retailers embedding Allianz insurance offers at the point of sale within their own customer journey. |
| ERP Integration | Enterprise companies integrating Allianz trade credit and policy management directly into their ERP systems for automation. |
| Broker Portals | Insurance brokers building digital platforms that access Allianz products to offer customers real-time quotes and policy management. |
| Claims Automation | Automating claims reporting, status tracking, and management through API integration with enterprise workflow systems. |

## Integrations

| Name | Description |
|------|-------------|
| Postman | Allianz Trade APIs support Postman collection import for API exploration and testing. |
| Apigee Edge | Allianz Global API platform uses Apigee Edge for API key and credential management. |
| Azure API Management | Allianz Partners portal is built on Azure API Management platform. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Allianz API Connect](openapi/allianz-api-connect.yaml)

### JSON Schema

- [api-connect-price-estimate-assisted-request-schema.json](json-schema/api-connect-price-estimate-assisted-request-schema.json)
- [api-connect-price-estimate-email-request-schema.json](json-schema/api-connect-price-estimate-email-request-schema.json)
- [api-connect-price-estimate-self-service-request-schema.json](json-schema/api-connect-price-estimate-self-service-request-schema.json)
- [api-connect-price-estimate-response-schema.json](json-schema/api-connect-price-estimate-response-schema.json)
- [api-connect-self-service-estimate-response-schema.json](json-schema/api-connect-self-service-estimate-response-schema.json)
- [api-connect-price-estimate-summary-schema.json](json-schema/api-connect-price-estimate-summary-schema.json)
- [api-connect-rating-factors-response-schema.json](json-schema/api-connect-rating-factors-response-schema.json)
- [api-connect-rating-factor-schema.json](json-schema/api-connect-rating-factor-schema.json)
- [api-connect-lead-referral-request-schema.json](json-schema/api-connect-lead-referral-request-schema.json)
- [api-connect-lead-referral-response-schema.json](json-schema/api-connect-lead-referral-response-schema.json)
- [api-connect-policy-details-assisted-request-schema.json](json-schema/api-connect-policy-details-assisted-request-schema.json)
- [api-connect-policy-details-self-service-request-schema.json](json-schema/api-connect-policy-details-self-service-request-schema.json)
- [api-connect-policy-details-response-schema.json](json-schema/api-connect-policy-details-response-schema.json)
- [api-connect-self-service-session-response-schema.json](json-schema/api-connect-self-service-session-response-schema.json)
- [api-connect-certificate-of-currency-schema.json](json-schema/api-connect-certificate-of-currency-schema.json)
- [api-connect-address-schema.json](json-schema/api-connect-address-schema.json)
- [api-connect-vehicle-schema.json](json-schema/api-connect-vehicle-schema.json)
- [api-connect-email-sent-response-schema.json](json-schema/api-connect-email-sent-response-schema.json)

### JSON Structure

- [api-connect-price-estimate-response-structure.json](json-structure/api-connect-price-estimate-response-structure.json)
- [api-connect-policy-details-response-structure.json](json-structure/api-connect-policy-details-response-structure.json)
- [api-connect-certificate-of-currency-structure.json](json-structure/api-connect-certificate-of-currency-structure.json)

### JSON-LD

- [allianz-api-connect-context.jsonld](json-ld/allianz-api-connect-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Allianz API Connect](capabilities/shared/api-connect.yaml) — 9 operations for partner insurance distribution

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Allianz Insurance Partner Integration](capabilities/insurance-partner-integration.yaml) | Allianz API Connect | 9 | Partner Developer, Financial Institution Integration Team |

## Vocabulary

- [Allianz Vocabulary](vocabulary/allianz-vocabulary.yaml) — Unified taxonomy mapping 4 resources, 3 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Allianz API Connect Spectral Rules](rules/allianz-docs-spectral-rules.yml) — 22 rules across 9 categories enforcing Allianz API Connect API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
