# BILL (bill)

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

BILL (formerly Bill.com) is a cloud-based financial operations platform for small and midsize businesses that automates accounts payable, accounts receivable, and spend & expense management. The BILL API Platform exposes these workflows through the BILL v3 REST API and embeddable BILL Elements UI components, enabling partners and ERPs to integrate bill capture, approvals, payments, and real-time event notifications via webhooks. The API uses session-based authentication with API keys and developer keys against production and sandbox gateways.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/bill/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/bill/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Accounts Payable
- Accounts Receivable
- Spend Management
- Expense Management
- Payments
- Bill Pay
- Financial Operations
- Fintech

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-30

## APIs

### BILL v3 API

REST API providing full-breadth access to BILL's Accounts Payable, Accounts Receivable, and Spend & Expense capabilities including bills, invoices, vendors, customers, payments, approvals, and webhook event notifications. Production calls are made to https://gateway.prod.bill.com/connect/v3 with sandbox at https://gateway.stage.bill.com/connect/v3.

- **Human URL:** [https://developer.bill.com/docs/bill-v3-api-get-started](https://developer.bill.com/docs/bill-v3-api-get-started)
- **Base URL:** `https://gateway.prod.bill.com/connect/v3`

#### Tags

- Accounts Payable
- Accounts Receivable
- Spend Management
- Payments
- Webhooks

#### Properties

- [Documentation](https://developer.bill.com/docs/home)
- [API Reference](https://developer.bill.com/reference)
- [Getting Started](https://developer.bill.com/docs/bill-v3-api-get-started)
- [Postman](https://www.postman.com/bill-api-platform/bill-api-platform-workspace/overview) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/bill/refs/heads/main/asyncapi/bill-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/bill.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bill.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### BILL Elements

Low-code, embeddable UI components that surface the BILL Accounts Payable workflow inside partner applications with minimal development effort.

- **Human URL:** [https://developer.bill.com/docs/home](https://developer.bill.com/docs/home)

#### Tags

- Embeddable UI
- Accounts Payable

#### Properties

- [Documentation](https://developer.bill.com/docs/home)
- [Postman Collection](collections/bill.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bill.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.bill.com)
- [Developer  Portal](https://developer.bill.com)
- [Documentation](https://developer.bill.com/docs/home)
- [API Reference](https://developer.bill.com/reference)
- [Pricing](https://www.bill.com/pricing)
- [Sign Up](https://app.bill.com/Signup)
- [Support](https://developersupport.bill.com)
- [LinkedIn](https://www.linkedin.com/company/bill-com)
- [L L Ms Txt](https://developer.bill.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
