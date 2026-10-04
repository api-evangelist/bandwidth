---
name: bandwidth-manage-e911-endpoint
description: Create a new E911 endpoint, retrieve its details, optionally update it, and finally delete it.
api: openapi/bandwidth-endpoints-api-openapi.yml
operations:
- createEndpoint
- getEndpoint
- updateEndpoint
- deleteEndpoint
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/bandwidth-endpoints-api-openapi.yml ; every operationId checked against the contract
---

# bandwidth-manage-e911-endpoint

Create a new E911 endpoint, retrieve its details, optionally update it, and finally delete it.

## Steps

1. 1. `createEndpoint` – requires `accountId` path parameter and request body fields `name`, `address`, `city`, `state`, `zip`, etc.
2. 2. `getEndpoint` – requires `accountId` and `endpointId` path parameters.
3. 3. `updateEndpoint` – requires `accountId` and `endpointId` path parameters and request body fields for the fields to modify.
4. 4. `deleteEndpoint` – requires `accountId` and `endpointId` path parameters.

## Rules

- Authentication: use Basic Auth header as defined by the `basicAuth` scheme.
- Idempotency: `createEndpoint` and `updateEndpoint` are not idempotent; repeat calls may create duplicate resources.
- No pagination is required for these endpoints.
