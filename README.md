# Amazon MediaTailor (amazon-mediatailor)

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

AWS Elemental MediaTailor is a channel assembly and personalized ad-insertion service that enables you to monetize your video content with server-side targeted advertising while maintaining broadcast-quality.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-mediatailor/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Broadcasting, Media Processing, Media

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon MediaTailor API
AWS Elemental MediaTailor is a channel assembly and personalized ad-insertion service that enables you to monetize your video content with server-side targeted advertising while maintaining broadcast-quality.

**Human URL:** [https://aws.amazon.com/mediatailor/](https://aws.amazon.com/mediatailor/)

#### Tags:

 - Broadcasting, Media Processing, Media

#### Properties

- [Documentation](https://docs.aws.amazon.com/mediatailor/)
- [OpenAPI](openapi/amazon-mediatailor-openapi-original.yml)
- [GettingStarted](https://aws.amazon.com/mediatailor/getting-started/)
- [Pricing](https://aws.amazon.com/mediatailor/pricing/)
- [FAQ](https://aws.amazon.com/mediatailor/faqs/)

## Common Properties

- [Portal](https://aws.amazon.com/mediatailor/)
- [Documentation](https://docs.aws.amazon.com/mediatailor/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/media/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/mediatailor/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)

## Features

| Name | Description |
|------|-------------|
| Server-Side Ad Insertion | Seamless ad replacement at the server side for consistent viewer experience across devices. |
| Personalized Ad Targeting | Insert targeted ads based on viewer demographics, geography, and behavioral data. |
| Channel Assembly | Create linear channels from VOD assets and live streams with automated ad scheduling. |
| Ad Decision Server Integration | Connect to any VAST/VPAID-compliant ad decision server for programmatic advertising. |
| Playback Configuration | Configure ad insertion parameters, slate, and CDN settings per playback session. |

## Use Cases

| Name | Description |
|------|-------------|
| VOD Monetization | Insert targeted ads into video-on-demand content for revenue generation. |
| Live Stream Advertising | Replace live ad markers with personalized ads during live events. |
| FAST Channel Creation | Build free ad-supported streaming TV channels from VOD libraries. |
| Addressable Advertising | Deliver personalized ad experiences to individual viewers at scale. |

## Integrations

| Name | Description |
|------|-------------|
| AWS Elemental MediaPackage | Ingest packaged live streams for ad insertion. |
| Amazon CloudFront | Deliver ad-inserted content via CloudFront with low latency. |
| Amazon S3 | Store VOD source content and slate media assets in S3. |
| Amazon CloudWatch | Monitor ad insertion metrics and playback session data. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon MediaTailor OpenAPI](openapi/amazon-mediatailor-openapi-original.yml)

### JSON Schema

- 152 schema files in [json-schema/](json-schema/)

### JSON Structure

- 152 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Amazon MediaTailor API Context](json-ld/amazon-mediatailor-mediatailor-api-context.jsonld)

### Examples

- 152 example files in [examples/](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon MediaTailor](capabilities/shared/mediatailor.yaml) — 44 operations for media processing

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Amazon MediaTailor Workflow](capabilities/amazon-mediatailor-media-workflow.yaml) | Amazon MediaTailor | 8 | Broadcast Engineer |

## Vocabulary

- [Amazon MediaTailor Vocabulary](vocabulary/amazon-mediatailor-vocabulary.yaml) — Unified taxonomy mapping resources, actions, workflows, and personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon MediaTailor Spectral Rules](rules/amazon-mediatailor-spectral-rules.yml) — 20 rules across 8 categories enforcing Amazon MediaTailor API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
