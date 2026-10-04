---
name: bandwidth-manage-conferences
description: Manage existing conferences by listing them, retrieving details, updating conference settings or members, and listing recordings.
api: openapi/bandwidth-conferences-api-openapi.yml
operations:
- listConferences
- getConference
- updateConference
- updateConferenceMember
- getConferenceRecordings
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/bandwidth-conferences-api-openapi.yml ; every operationId checked against the contract
---

# bandwidth-manage-conferences

Manage existing conferences by listing them, retrieving details, updating conference settings or members, and listing recordings.

## Steps

1. 1. Call `listConferences` with the required path parameters `accountId`.
2. 2. Call `getConference` with `accountId` and `conferenceId` to retrieve conference information.
3. 3. Call `updateConference` with `accountId`, `conferenceId` and the body fields to modify conference settings.
4. 4. Call `updateConferenceMember` with `accountId`, `conferenceId`, `memberId` and the body fields to modify a member.
5. 5. Call `getConferenceRecordings` with `accountId` and `conferenceId` to list recordings.

## Rules

- Authentication: Use Basic Auth (http) as the auth scheme.
- Rate limiting: No rate limit is defined; on exhaustion the API returns no specific HTTP status.
