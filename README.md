# Verifone

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
