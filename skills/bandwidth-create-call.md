---
name: bandwidth-create-call
description: Create a new call, retrieve its details, and then update the call as needed.
api: openapi/bandwidth-calls-api-openapi.yml
operations:
- createCall
- getCall
- updateCall
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/bandwidth-calls-api-openapi.yml ; every operationId checked against the contract
---

# bandwidth-create-call

Create a new call, retrieve its details, and then update the call as needed.

## Steps

1. 1. `createCall` – requires the `Authorization` header (basicAuth) and the request body fields defined for creating a call.
2. 2. `getCall` – requires the `Authorization` header (basicAuth) and the path parameters `accountId` and `callId`.
3. 3. `updateCall` – requires the `Authorization` header (basicAuth), the path parameters `accountId` and `callId`, and the request body fields defined for updating a call.

## Rules

- Authentication: Include a Basic Auth `Authorization` header on every request.
- Idempotency: Not specified for these endpoints.
- Pagination: Not applicable.
- Error handling: Follow standard HTTP error responses as defined by the API.
