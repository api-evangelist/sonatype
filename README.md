# Sonatype (sonatype)

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

Sonatype provides software supply chain management solutions including Sonatype Lifecycle (IQ Server), Sonatype Repository Firewall, SBOM Manager, and Nexus Repository. The Lifecycle Public REST API provides 188 endpoints for application portfolio management, policy enforcement, vulnerability reporting, component analysis, SBOM generation, source control integration, and software composition analysis across the SDLC.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sonatype/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sonatype/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Software Supply Chain
- Security
- Vulnerability Management
- SBOM
- Software Composition Analysis
- DevSecOps

## Timestamps

- **Created:** 2025-02-12
- **Modified:** 2026-05-19

## APIs

### Sonatype Lifecycle API

The Sonatype Lifecycle Public REST API (v1.201.0) provides 188 endpoints for managing applications, organizations, policies, policy violations, waivers, vulnerability analysis, SBOM generation (SPDX, CycloneDX), scan management, component search, reports, source control integration, users, roles, and user tokens. Used by DevSecOps teams to automate software supply chain security and compliance workflows.

- **Human URL:** [https://help.sonatype.com/en/iq-api-reference.html](https://help.sonatype.com/en/iq-api-reference.html)
- **Base URL:** `https://{iq-server-host}/`

#### Tags

- Software Supply Chain
- Security
- Policy
- Vulnerability Management
- SBOM
- Software Composition Analysis
- Applications
- Organizations

#### Properties

- [Documentation](https://help.sonatype.com/en/iq-api-reference.html)
- [Reference](https://help.sonatype.com/en/rest-apis.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/sonatype/refs/heads/main/openapi/sonatype-lifecycle-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/sonatype/refs/heads/main/json-schema/sonatype-application-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/sonatype/refs/heads/main/json-schema/sonatype-policy-violation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Postman Collection](collections/sonatype-lifecycle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sonatype-lifecycle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/sonatype)
- [Portal](https://www.sonatype.com/)
- [Documentation](https://help.sonatype.com/)
- [Website](https://www.sonatype.com/)
- [Git Hub](https://github.com/sonatype-nexus-community)
- [Blog](https://www.sonatype.com/blog)
- [Changelog](https://help.sonatype.com/en/sonatype-iq-server-2025-release-notes.html)
- [Support](https://support.sonatype.com/)
- [Pricing](https://www.sonatype.com/products/pricing)
- [Integrations](https://www.sonatype.com/products/integrations)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
