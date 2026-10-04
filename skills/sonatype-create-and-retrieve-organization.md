---
name: sonatype-create-and-retrieve-organization
description: Create a new organization and then retrieve its details.
api: openapi/sonatype-iq-openapi.yml
operations:
- addOrganization
- getOrganization
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/sonatype-iq-openapi.yml ; every operationId checked against the contract
---

# sonatype-create-and-retrieve-organization

Create a new organization and then retrieve its details.

## Steps

1. 1. Call `addOrganization` with the required request body fields for the new organization.
2. 2. Call `getOrganization` with the `organizationId` returned from the previous step, using the path parameter `organizationId`.

## Rules

- Auth header: use either BasicAuth or BearerAuth as defined by the API.
- Rate limit: maximum 3 attempts per period; on exhaustion the response has no HTTP status code defined.
