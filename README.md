# Method Financial (method-fi)

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

Method Financial provides an embedded liability connectivity and payments API that lets developers identify, retrieve, and pay down a consumer's debts (credit cards, student loans, auto loans, mortgages, personal loans) across a network of 15,000+ financial institutions. The REST API exposes entities, accounts, payments, merchants, connect (liability discovery), transactions, and webhooks, authenticated with a Bearer API key.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/method-fi/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/method-fi/refs/heads/main/apis.yml)

## Tags

- FinTech
- Payments
- Liabilities
- Debt
- Embedded Finance

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Method Entities API

Create and manage Entities - the individuals and corporations that own accounts - along with their identities, credit scores, attributes, products, and KYC/KBA/SMS verification sessions.

- **Human URL:** [https://docs.methodfi.com/api/core/entities/object](https://docs.methodfi.com/api/core/entities/object)
- **Base URL:** `https://production.methodfi.com`

#### Tags

- Entities
- KYC
- Identity

#### Properties

- [Documentation](https://docs.methodfi.com/api/core/entities/object)
- [API Reference](https://docs.methodfi.com/reference/entities/create)
- [OpenAPI](openapi/method-fi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/method-fi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/method-fi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Method Accounts API

Create and retrieve Accounts - the liability and asset accounts linked to an entity - with real-time balances, payoffs, transactions, attributes, and account verification sessions.

- **Human URL:** [https://docs.methodfi.com/api/core/accounts/object](https://docs.methodfi.com/api/core/accounts/object)
- **Base URL:** `https://production.methodfi.com`

#### Tags

- Accounts
- Liabilities
- Balances

#### Properties

- [Documentation](https://docs.methodfi.com/api/core/accounts/object)
- [API Reference](https://docs.methodfi.com/reference/accounts/create)
- [OpenAPI](openapi/method-fi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/method-fi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/method-fi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Method Payments API

Move funds electronically by pulling from a source account and sending to a destination liability or asset account, with payment reversals for balancing unsuccessful payments. Settlement occurs in 1-3 business days.

- **Human URL:** [https://docs.methodfi.com/api/core/payments/object](https://docs.methodfi.com/api/core/payments/object)
- **Base URL:** `https://production.methodfi.com`

#### Tags

- Payments
- ACH
- Debt Payoff

#### Properties

- [Documentation](https://docs.methodfi.com/api/core/payments/object)
- [API Reference](https://docs.methodfi.com/reference/payments/create)
- [OpenAPI](openapi/method-fi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/method-fi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/method-fi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Method Merchants API

List and retrieve Merchants - the financial institutions (credit card issuers, student loan servicers, mortgage and auto lenders) that accept payments for a liability - with presentable names, logos, and account types.

- **Human URL:** [https://docs.methodfi.com/api/core/merchants/object](https://docs.methodfi.com/api/core/merchants/object)
- **Base URL:** `https://production.methodfi.com`

#### Tags

- Merchants
- Lenders
- Directory

#### Properties

- [Documentation](https://docs.methodfi.com/api/core/merchants/object)
- [API Reference](https://docs.methodfi.com/reference/merchants/list)
- [OpenAPI](openapi/method-fi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/method-fi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/method-fi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Method Connect API

Discover and connect all of an entity's liability accounts (credit cards, mortgages, auto loans, student loans) across Method's network of financial institutions from identity data alone.

- **Human URL:** [https://docs.methodfi.com/api/core/connect/object](https://docs.methodfi.com/api/core/connect/object)
- **Base URL:** `https://production.methodfi.com`

#### Tags

- Connect
- Liability Discovery
- Account Matching

#### Properties

- [Documentation](https://docs.methodfi.com/api/core/connect/object)
- [API Reference](https://docs.methodfi.com/reference/entities/connect/retrieve)
- [OpenAPI](openapi/method-fi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/method-fi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/method-fi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Method Transactions API

List and retrieve transaction history for an account, surfacing the posted activity Method has on file for a connected liability or asset account.

- **Human URL:** [https://docs.methodfi.com/api/core/transactions/object](https://docs.methodfi.com/api/core/transactions/object)
- **Base URL:** `https://production.methodfi.com`

#### Tags

- Transactions
- History
- Statements

#### Properties

- [Documentation](https://docs.methodfi.com/api/core/transactions/object)
- [API Reference](https://docs.methodfi.com/reference/accounts/transactions/list)
- [OpenAPI](openapi/method-fi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/method-fi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/method-fi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Method Webhooks API

Create and manage Webhooks that deliver asynchronous events - entity, account, payment, verification, and attribute updates - to your endpoints over HTTPS as resources change.

- **Human URL:** [https://docs.methodfi.com/api/core/webhooks/object](https://docs.methodfi.com/api/core/webhooks/object)
- **Base URL:** `https://production.methodfi.com`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs.methodfi.com/api/core/webhooks/object)
- [API Reference](https://docs.methodfi.com/reference/webhooks/create)
- [OpenAPI](openapi/method-fi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/method-fi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/method-fi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/MethodFi)
- [LinkedIn](https://www.linkedin.com/company/methodfi)
- [Website](https://methodfi.com)
- [Documentation](https://docs.methodfi.com)
- [Plans](plans/method-fi-plans-pricing.yml)
- [Rate Limits](rate-limits/method-fi-rate-limits.yml)
- [Fin Ops](finops/method-fi-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
