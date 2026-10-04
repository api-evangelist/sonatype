---
name: sonatype-create-application
description: Create a new application and retrieve its details.
api: openapi/sonatype-applications-api-openapi.yml
operations:
- addApplication
- getApplication
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/sonatype-applications-api-openapi.yml ; every operationId checked against the contract
---

# sonatype-create-application

Create a new application and retrieve its details.

## Steps

1. 1. Call `addApplication` with the required request body fields for the new application.
2. 2. Call `getApplication` using the `applicationId` returned from `addApplication` to fetch the created application's details.

## Rules

- Auth header: use either BasicAuth or BearerAuth as defined by the API.
- Rate limit: maximum 3 attempts (`nexus.auth.ratelimit.max-attempts=3`).
