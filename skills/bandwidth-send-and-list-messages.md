---
name: bandwidth-send-and-list-messages
description: Send a new message and then retrieve the list of messages for the account.
api: openapi/bandwidth-messages-api-openapi.yml
operations:
- createMessage
- listMessages
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/bandwidth-messages-api-openapi.yml ; every operationId checked against the contract
---

# bandwidth-send-and-list-messages

Send a new message and then retrieve the list of messages for the account.

## Steps

1. 1. Use `createMessage` with path parameter `accountId` and request body fields such as `to`, `from`, `text` (as defined in the contract).
2. 2. Use `listMessages` with path parameter `accountId` to retrieve the messages collection.

## Rules

- Auth: Include a Basic Auth header as defined by the `basicAuth` scheme.
- Idempotency: `createMessage` is not idempotent; repeat calls will send duplicate messages.
