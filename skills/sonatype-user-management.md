---
name: sonatype-user-management
description: Create a new user, retrieve it, update its details, and then delete it.
api: openapi/sonatype-iq-openapi.yml
operations:
- add
- get_1
- update
- delete_1
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/sonatype-iq-openapi.yml ; every operationId checked against the contract
---

# sonatype-user-management

Create a new user, retrieve it, update its details, and then delete it.

## Steps

1. 1. `add` – send a POST request to /api/v2/users with the required user fields in the request body.
2. 2. `get_1` – send a GET request to /api/v2/users/{username} using the username returned or supplied in step 1.
3. 3. `update` – send a PUT request to /api/v2/users/{username} with the fields to modify in the request body.
4. 4. `delete_1` – send a DELETE request to /api/v2/users/{username} to remove the user.

## Rules

- Include an Authorization header using either BasicAuth or BearerAuth as defined by the API.
- Rate limiting: a maximum of 3 attempts are allowed before exhaustion; no specific HTTP status code is defined for exhaustion.
