# Method Financial (method-fi)

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
