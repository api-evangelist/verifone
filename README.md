# Verifone

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

Verifone is a global payment technology company providing REST APIs for POS terminal management, online payment processing, commerce platform integration, and omnichannel payment acceptance. Their developer platform covers in-person payments, eCommerce, hosted checkout, 3D Secure authentication, customer management, device management via VHQ, hardware ordering, and financial reporting across EMEA, Americas, and Asia-Pacific regions.

## APIs

| API | Description | Docs |
|-----|-------------|------|
| Checkout API | Accept cards, wallets, and local payments via hosted pages or iFrames | [Docs](https://docs.verifone.com/api-reference/open-api-references/checkout) |
| eCommerce API | Global payments, recurring billing, tokenization | [Docs](https://docs.verifone.com/api-reference/open-api-references/ecommerce) |
| 3D Secure API | SCA-compliant cardholder authentication | [Docs](https://docs.verifone.com/api-reference/open-api-references/3d-secure) |
| Customer API | Store and manage shopper details | [Docs](https://docs.verifone.com/api-reference/open-api-references/customer) |
| Reporting API | Settlement, transaction, and financial reports | [Docs](https://docs.verifone.com/api-reference/open-api-references/reporting) |
| Order Service API | Hardware orders, provisioning, merchant boarding | [Docs](https://docs.verifone.com/api-reference/open-api-references/order-service) |
| PayPal eCom API | PayPal and alternative payment processing | [Docs](https://docs.verifone.com/api-reference/open-api-references/paypal-ecom) |
| VHQ Device Management API | Remote POS terminal management and monitoring | [Docs](https://docs.verifone.com/vhq) |

## Authentication

All online payment APIs support both **HTTP Basic Authentication** and **Bearer (JWT) Authentication**. Separate API keys are required for sandbox and production environments. Keys are provisioned through the Verifone dashboard.

## Environments

| Environment | Global | US | NZ |
|-------------|--------|----|----|
| Sandbox | `cst.test-gsc.vfims.com` | `uscst-gb.gsc.vficloud.net` | - |
| Production | `emea.gsc.verifone.cloud` | `us.gsc.verifone.cloud` | `nz.gsc.verifone.cloud` |

## Pricing

Transaction-based pricing with no monthly fees:

- **2Sell**: 3.5% + $0.35/sale
- **2Subscribe**: 4.5% + $0.45/sale
- **2Monetize**: 6.0% + $0.60/sale
- **Enterprise**: Custom pricing

## Developer Resources

- **Portal**: https://docs.verifone.com
- **API Reference**: https://docs.verifone.com/api-reference
- **Getting Started**: https://docs.verifone.com/online-payments/getting-started
- **Blog / Release Notes**: https://verifone.cloud/blog
