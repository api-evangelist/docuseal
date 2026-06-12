# DocuSeal (docuseal)

DocuSeal is an open-source document signing platform that provides a REST API for building electronic signature workflows into applications. It supports creating and managing document templates, sending signature requests, tracking submission status, and receiving real-time webhook events for document lifecycle management. DocuSeal is available as a cloud-hosted service with US and EU data residency options, or as a self-hosted on-premises deployment under an AGPL-3.0 open-source license.

APIs.json: https://raw.githubusercontent.com/api-evangelist/docuseal/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=docuseal-api-evangelist&utm_content=repo

## Tags

- Document Signing
- eSignature
- Electronic Signature
- Document Management
- PDF
- Templates
- Open Source
- Webhooks
- Embedding

## APIs

### DocuSeal REST API

REST API for creating document signing workflows, managing templates, sending signature requests, tracking submission status, and receiving webhook events for document lifecycle management.

- **Documentation:** https://www.docuseal.com/docs/api
- **Base URL (US):** https://api.docuseal.com
- **Base URL (EU):** https://api.docuseal.eu
- **Authentication:** API key via `X-Auth-Token` header

**Endpoints:**

- Submissions: Create, list, retrieve, and archive signature requests from templates, PDFs, DOCX, and HTML
- Submitters: List, retrieve, and update signer information and status
- Templates: Create, list, and update document templates

**Webhooks:** `form.viewed`, `form.started`, `form.completed`

## Plans / Rate Limits / FinOps

| Resource | Path |
|---|---|
| Plans & Pricing | [plans/docuseal-plans-pricing.yml](plans/docuseal-plans-pricing.yml) |
| Rate Limits | [rate-limits/docuseal-rate-limits.yml](rate-limits/docuseal-rate-limits.yml) |
| FinOps | [finops/docuseal-finops.yml](finops/docuseal-finops.yml) |

### Pricing Summary

| Plan | Price | API Access |
|---|---|---|
| Basic (Cloud) | Free | No |
| Pro (Cloud) | $20/user/month + $0.20/completion | Yes |
| Open Source (On-Premises) | Free | No |
| Pro (On-Premises) | $20/user/month | Yes |
| Sandbox | Free | Yes (testing only) |

### Rate Limits

DocuSeal does not publicly document specific numeric rate limits. Pagination is cursor-based with a default of 10 items per request and a maximum of 100. HTTP 429 is returned when limits are exceeded.

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common Properties

| Type | URL |
|---|---|
| Website | https://www.docuseal.com/ |
| Documentation | https://www.docuseal.com/docs |
| Getting Started | https://www.docuseal.com/resources/quick-start |
| API Reference | https://www.docuseal.com/docs/api |
| Developers | https://www.docuseal.com/developers |
| Guides | https://www.docuseal.com/guides |
| GitHub Organization | https://github.com/docusealco |
| LinkedIn | https://www.linkedin.com/company/docuseal |
| Blog | https://www.docuseal.com/blog |
| Changelog | https://www.docuseal.com/changelog |
| Pricing | https://www.docuseal.com/pricing |
| Status Page | https://status.docuseal.net/ |
| Webhooks | https://www.docuseal.com/resources/use-webhooks |
| On-Premises | https://www.docuseal.com/on-premises |
| Signing API | https://www.docuseal.com/signing-api |
| Postman Collection | https://www.postman.com/docuseal/docuseal/documentation/baauu23/docuseal-api |

## Maintainers

- **Kin Lane** — kin@apievangelist.com
