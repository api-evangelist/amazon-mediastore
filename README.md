# Amazon MediaStore (amazon-mediastore)
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
