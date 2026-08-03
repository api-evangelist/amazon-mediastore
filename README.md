# Amazon MediaStore (amazon-mediastore)

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

AWS Elemental MediaStore is an AWS storage service optimized for media, providing the performance, consistency, and low latency required to deliver live streaming video content at scale.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-mediastore/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Broadcasting, Media Processing, Media

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon MediaStore API
AWS Elemental MediaStore is an AWS storage service optimized for media, providing the performance, consistency, and low latency required to deliver live streaming video content at scale.

**Human URL:** [https://aws.amazon.com/mediastore/](https://aws.amazon.com/mediastore/)

#### Tags:

 - Broadcasting, Media Processing, Media

#### Properties

- [Documentation](https://docs.aws.amazon.com/mediastore/)
- [OpenAPI](openapi/amazon-mediastore-openapi-original.yml)
- [GettingStarted](https://aws.amazon.com/mediastore/getting-started/)
- [Pricing](https://aws.amazon.com/mediastore/pricing/)
- [FAQ](https://aws.amazon.com/mediastore/faqs/)

## Common Properties

- [Portal](https://aws.amazon.com/mediastore/)
- [Documentation](https://docs.aws.amazon.com/mediastore/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/media/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/mediastore/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)

## Features

| Name | Description |
|------|-------------|
| High-Performance Media Storage | Optimized object storage for live video with consistent low-latency performance. |
| Container and Object Management | Organize media assets in containers with fine-grained access control policies. |
| CORS Support | Cross-origin resource sharing configuration for browser-based media players. |
| Lifecycle Policies | Automatically expire and delete media objects based on age or other criteria. |
| Access Logging | Detailed access logs for auditing and monitoring media storage activity. |

## Use Cases

| Name | Description |
|------|-------------|
| Live Video Origin Storage | Use as a high-performance origin for live video workflows. |
| Media Asset Management | Store and manage media files with low-latency access. |
| Streaming Video Delivery | Serve HLS and DASH segments with consistent performance for video streaming. |

## Integrations

| Name | Description |
|------|-------------|
| AWS Elemental MediaLive | Use MediaStore as an output destination for live encoded streams. |
| Amazon CloudFront | Serve MediaStore content via CloudFront for global distribution. |
| AWS IAM | Control access to MediaStore containers using IAM policies. |
| Amazon CloudWatch | Monitor MediaStore request metrics and latency. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon MediaStore OpenAPI](openapi/amazon-mediastore-openapi-original.yml)

### JSON Schema

- 81 schema files in [json-schema/](json-schema/)

### JSON Structure

- 81 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Amazon MediaStore API Context](json-ld/amazon-mediastore-mediastore-api-context.jsonld)

### Examples

- 81 example files in [examples/](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon MediaStore](capabilities/shared/mediastore.yaml) — 21 operations for media processing

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Amazon MediaStore Workflow](capabilities/amazon-mediastore-media-workflow.yaml) | Amazon MediaStore | 8 | Broadcast Engineer |

## Vocabulary

- [Amazon MediaStore Vocabulary](vocabulary/amazon-mediastore-vocabulary.yaml) — Unified taxonomy mapping resources, actions, workflows, and personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon MediaStore Spectral Rules](rules/amazon-mediastore-spectral-rules.yml) — 20 rules across 8 categories enforcing Amazon MediaStore API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
