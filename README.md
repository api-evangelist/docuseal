# DocuSeal (docuseal)

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
