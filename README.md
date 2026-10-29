# Bandwidth

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Bandwidth is a leading cloud-based communications platform providing voice, messaging, emergency calling, phone number management, multi-factor authentication, and toll-free verification APIs. Built on Bandwidth's own Tier 1 network, the platform delivers enterprise-grade reliability for CPaaS applications.

**Areas:** Communications · CPaaS · Voice · Messaging · Telephony · SMS · MFA · Telecommunications

## Bandwidth on APIs.io

Everything profiled for Bandwidth is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/bandwidth/](https://apis.io/providers/bandwidth/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [Bandwidth Calls API](https://apis.io/apis/bandwidth/bandwidth-calls-api/) — Create, retrieve, and manage phone calls. Supports outbound call creation, call state queries, and in-progress call modifications using BXML or redirect URLs.
- [Bandwidth Conferences API](https://apis.io/apis/bandwidth/bandwidth-conferences-api/) — Create and manage multi-party conference calls. Supports adding and removing members, muting, holding, and playing audio to conferences.
- [Bandwidth Emergency Notification Recipients API](https://apis.io/apis/bandwidth/bandwidth-emergency-notification-recipients-api/) — Configure notification recipients who receive alerts when 911 calls are made from your endpoints.
- [Bandwidth Endpoints API](https://apis.io/apis/bandwidth/bandwidth-endpoints-api/) — Manage 911 endpoints that represent end users of your service. Endpoints are identified by Alternate End User IDs (AEUIs) and are associated with locations…
- [Bandwidth Locations API](https://apis.io/apis/bandwidth/bandwidth-locations-api/) — Provision and manage physical locations (addresses) for 911 emergency services routing. Locations are validated against the Master Street Address Guide…
- [Bandwidth Media API](https://apis.io/apis/bandwidth/bandwidth-media-api/) — Upload, retrieve, and manage media files for use in MMS messages. Supports files up to 3.75 MB with 48-hour retention.
- [Bandwidth Messages API](https://apis.io/apis/bandwidth/bandwidth-messages-api/) — Send and retrieve SMS and MMS messages. Supports single and group messaging, delivery receipts, and message history queries.
- [Bandwidth Recordings API](https://apis.io/apis/bandwidth/bandwidth-recordings-api/) — Manage call recordings including retrieval of recording metadata, audio files, and transcription of recorded audio content.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (3)

Event-driven and webhook contracts.

- [Bandwidth Messaging Events](https://apis.io/asyncapis/bandwidth/bandwidth-messaging-events-asyncapi/)
- [Bandwidth Voice Events](https://apis.io/asyncapis/bandwidth/bandwidth-voice-events-asyncapi/)
- [Bandwidth Webhooks](https://apis.io/asyncapis/bandwidth/bandwidth-webhooks/)

#### Event channels (15)

Individual events and webhooks the provider emits.

- [/messaging/inbound](https://apis.io/channels/bandwidth/messaging-inbound/)
- [/messaging/status](https://apis.io/channels/bandwidth/messaging-status/)
- [/voice/answer](https://apis.io/channels/bandwidth/voice-answer/)
- [/voice/conferenceCompleted](https://apis.io/channels/bandwidth/voice-conferencecompleted/)
- [/voice/conferenceCreated](https://apis.io/channels/bandwidth/voice-conferencecreated/)
- [/voice/conferenceMemberExit](https://apis.io/channels/bandwidth/voice-conferencememberexit/)
- [/voice/conferenceMemberJoin](https://apis.io/channels/bandwidth/voice-conferencememberjoin/)
- [/voice/disconnect](https://apis.io/channels/bandwidth/voice-disconnect/)
- [/voice/gather](https://apis.io/channels/bandwidth/voice-gather/)
- [/voice/initiate](https://apis.io/channels/bandwidth/voice-initiate/)
- [/voice/recordingComplete](https://apis.io/channels/bandwidth/voice-recordingcomplete/)
- [/voice/redirect](https://apis.io/channels/bandwidth/voice-redirect/)
- [/voice/transcriptionAvailable](https://apis.io/channels/bandwidth/voice-transcriptionavailable/)
- [/voice/transferAnswer](https://apis.io/channels/bandwidth/voice-transferanswer/)
- [/voice/transferDisconnect](https://apis.io/channels/bandwidth/voice-transferdisconnect/)

#### GraphQL (1)

GraphQL schemas.

- [Moved to /providers/bandwidth/](https://apis.io/graphqls/bandwidth/bandwidth-graphql/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [bandwidth-mcp.yml](https://apis.io/servers/bandwidth/bandwidth-mcp-yml/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Bandwidth Agentic Access](https://apis.io/agentic-access/bandwidth/bandwidth-agentic-access/)

#### JSON Schema (71)

The data models the API reads and writes.

- [Bandwidth Call](https://apis.io/schemas/bandwidth/bandwidth-call/)
- [Conference](https://apis.io/schemas/bandwidth/bandwidth-conference/)
- [CreateCallRequest](https://apis.io/schemas/bandwidth/bandwidth-create-call-request/)
- [CreateMessageRequest](https://apis.io/schemas/bandwidth/bandwidth-create-message-request/)
- [Endpoint](https://apis.io/schemas/bandwidth/bandwidth-endpoint/)
- [EndpointListResponse](https://apis.io/schemas/bandwidth/bandwidth-endpoint-list-response/)
- [Location](https://apis.io/schemas/bandwidth/bandwidth-location/)
- [LocationListResponse](https://apis.io/schemas/bandwidth/bandwidth-location-list-response/)
- [Media](https://apis.io/schemas/bandwidth/bandwidth-media/)
- [Bandwidth Message](https://apis.io/schemas/bandwidth/bandwidth-message/)
- [MessageList](https://apis.io/schemas/bandwidth/bandwidth-message-list/)
- [NotificationRecipient](https://apis.io/schemas/bandwidth/bandwidth-notification-recipient/)
- [NotificationRecipientListResponse](https://apis.io/schemas/bandwidth/bandwidth-notification-recipient-list-response/)
- [Bandwidth Phone Number](https://apis.io/schemas/bandwidth/bandwidth-phone-number/)
- [Recording](https://apis.io/schemas/bandwidth/bandwidth-recording/)
- [Transcription](https://apis.io/schemas/bandwidth/bandwidth-transcription/)
- [TranscriptionRequest](https://apis.io/schemas/bandwidth/bandwidth-transcription-request/)
- [UpdateCallRequest](https://apis.io/schemas/bandwidth/bandwidth-update-call-request/)
- [UpdateConferenceMemberRequest](https://apis.io/schemas/bandwidth/bandwidth-update-conference-member-request/)
- [UpdateConferenceRequest](https://apis.io/schemas/bandwidth/bandwidth-update-conference-request/)
- [Endpoint](https://apis.io/schemas/bandwidth/emergency-calling-endpoint/)
- [EndpointListResponse](https://apis.io/schemas/bandwidth/emergency-calling-endpoint-list-response/)
- [Location](https://apis.io/schemas/bandwidth/emergency-calling-location/)
- [LocationListResponse](https://apis.io/schemas/bandwidth/emergency-calling-location-list-response/)
- [NotificationRecipient](https://apis.io/schemas/bandwidth/emergency-calling-notification-recipient/)
- …and 46 more published on APIs.io

#### JSON Structure (54)

Data models expressed in JSON Structure.

- [Bandwidth Call Structure](https://apis.io/json-structure/bandwidth/bandwidth-call-structure/)
- [Bandwidth Message Structure](https://apis.io/json-structure/bandwidth/bandwidth-message-structure/)
- [Bandwidth Phone Number Structure](https://apis.io/json-structure/bandwidth/bandwidth-phone-number-structure/)
- [Emergency Calling Endpoint List Response Structure](https://apis.io/json-structure/bandwidth/emergency-calling-endpoint-list-response-structure/)
- [Emergency Calling Endpoint Structure](https://apis.io/json-structure/bandwidth/emergency-calling-endpoint-structure/)
- [Emergency Calling Location List Response Structure](https://apis.io/json-structure/bandwidth/emergency-calling-location-list-response-structure/)
- [Emergency Calling Location Structure](https://apis.io/json-structure/bandwidth/emergency-calling-location-structure/)
- [Emergency Calling Notification Recipient List Response Structure](https://apis.io/json-structure/bandwidth/emergency-calling-notification-recipient-list-response-structure/)
- [Emergency Calling Notification Recipient Structure](https://apis.io/json-structure/bandwidth/emergency-calling-notification-recipient-structure/)
- [Messaging Create Message Request Structure](https://apis.io/json-structure/bandwidth/messaging-create-message-request-structure/)
- [Messaging Error Structure](https://apis.io/json-structure/bandwidth/messaging-error-structure/)
- [Messaging Media Structure](https://apis.io/json-structure/bandwidth/messaging-media-structure/)
- [Messaging Message List Structure](https://apis.io/json-structure/bandwidth/messaging-message-list-structure/)
- [Messaging Message Structure](https://apis.io/json-structure/bandwidth/messaging-message-structure/)
- [Mfa Error Structure](https://apis.io/json-structure/bandwidth/mfa-error-structure/)
- [Mfa Mfa Messaging Request Structure](https://apis.io/json-structure/bandwidth/mfa-mfa-messaging-request-structure/)
- [Mfa Mfa Messaging Response Structure](https://apis.io/json-structure/bandwidth/mfa-mfa-messaging-response-structure/)
- [Mfa Mfa Verify Request Structure](https://apis.io/json-structure/bandwidth/mfa-mfa-verify-request-structure/)
- [Mfa Mfa Verify Response Structure](https://apis.io/json-structure/bandwidth/mfa-mfa-verify-response-structure/)
- [Mfa Mfa Voice Request Structure](https://apis.io/json-structure/bandwidth/mfa-mfa-voice-request-structure/)
- [Mfa Mfa Voice Response Structure](https://apis.io/json-structure/bandwidth/mfa-mfa-voice-response-structure/)
- [Phone Numbers Address Structure](https://apis.io/json-structure/bandwidth/phone-numbers-address-structure/)
- [Phone Numbers Available Number Structure](https://apis.io/json-structure/bandwidth/phone-numbers-available-number-structure/)
- [Phone Numbers Available Numbers Response Structure](https://apis.io/json-structure/bandwidth/phone-numbers-available-numbers-response-structure/)
- [Phone Numbers Disconnect Request Structure](https://apis.io/json-structure/bandwidth/phone-numbers-disconnect-request-structure/)
- …and 29 more published on APIs.io

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Bandwidth Context](https://apis.io/jsonld/bandwidth/bandwidth-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Bandwidth Vocabulary](https://apis.io/vocabularies/bandwidth/bandwidth-vocabulary/)

#### Examples (54)

Example requests and responses.

- [Bandwidth Call Example](https://apis.io/examples/bandwidth/bandwidth-call-example/)
- [Bandwidth Message Example](https://apis.io/examples/bandwidth/bandwidth-message-example/)
- [Bandwidth Phone Number Example](https://apis.io/examples/bandwidth/bandwidth-phone-number-example/)
- [Emergency Calling Endpoint Example](https://apis.io/examples/bandwidth/emergency-calling-endpoint-example/)
- [Emergency Calling Endpoint List Response Example](https://apis.io/examples/bandwidth/emergency-calling-endpoint-list-response-example/)
- [Emergency Calling Location Example](https://apis.io/examples/bandwidth/emergency-calling-location-example/)
- [Emergency Calling Location List Response Example](https://apis.io/examples/bandwidth/emergency-calling-location-list-response-example/)
- [Emergency Calling Notification Recipient Example](https://apis.io/examples/bandwidth/emergency-calling-notification-recipient-example/)
- [Emergency Calling Notification Recipient List Response Example](https://apis.io/examples/bandwidth/emergency-calling-notification-recipient-list-response-example/)
- [Messaging Create Message Request Example](https://apis.io/examples/bandwidth/messaging-create-message-request-example/)
- [Messaging Error Example](https://apis.io/examples/bandwidth/messaging-error-example/)
- [Messaging Media Example](https://apis.io/examples/bandwidth/messaging-media-example/)
- [Messaging Message Example](https://apis.io/examples/bandwidth/messaging-message-example/)
- [Messaging Message List Example](https://apis.io/examples/bandwidth/messaging-message-list-example/)
- [Mfa Error Example](https://apis.io/examples/bandwidth/mfa-error-example/)
- [Mfa Mfa Messaging Request Example](https://apis.io/examples/bandwidth/mfa-mfa-messaging-request-example/)
- [Mfa Mfa Messaging Response Example](https://apis.io/examples/bandwidth/mfa-mfa-messaging-response-example/)
- [Mfa Mfa Verify Request Example](https://apis.io/examples/bandwidth/mfa-mfa-verify-request-example/)
- [Mfa Mfa Verify Response Example](https://apis.io/examples/bandwidth/mfa-mfa-verify-response-example/)
- [Mfa Mfa Voice Request Example](https://apis.io/examples/bandwidth/mfa-mfa-voice-request-example/)
- [Mfa Mfa Voice Response Example](https://apis.io/examples/bandwidth/mfa-mfa-voice-response-example/)
- [Phone Numbers Address Example](https://apis.io/examples/bandwidth/phone-numbers-address-example/)
- [Phone Numbers Available Number Example](https://apis.io/examples/bandwidth/phone-numbers-available-number-example/)
- [Phone Numbers Available Numbers Response Example](https://apis.io/examples/bandwidth/phone-numbers-available-numbers-response-example/)
- [Phone Numbers Disconnect Request Example](https://apis.io/examples/bandwidth/phone-numbers-disconnect-request-example/)
- …and 29 more published on APIs.io

#### Collections (39)

Postman and Open Collection request collections.

- [Bandwidth Emergency Calling Available Numbers API](https://apis.io/collections/bandwidth/open-bandwidth-available-numbers-api/)
- [Bandwidth Emergency Calling Available Numbers Calls API](https://apis.io/collections/bandwidth/open-bandwidth-calls-api/)
- [Bandwidth Emergency Calling Available Numbers Conferences API](https://apis.io/collections/bandwidth/open-bandwidth-conferences-api/)
- [Bandwidth Emergency Calling Available Numbers Disconnects API](https://apis.io/collections/bandwidth/open-bandwidth-disconnects-api/)
- [Bandwidth Emergency Calling API](https://apis.io/collections/bandwidth/open-bandwidth-emergency-calling-api/)
- [Bandwidth Emergency Calling Available Numbers Emergency Notification Recipients API](https://apis.io/collections/bandwidth/open-bandwidth-emergency-notification-recipients-api/)
- [Bandwidth Emergency Calling Available Numbers Endpoints API](https://apis.io/collections/bandwidth/open-bandwidth-endpoints-api/)
- [Bandwidth Emergency Calling Available Numbers Locations API](https://apis.io/collections/bandwidth/open-bandwidth-locations-api/)
- [Bandwidth Emergency Calling Available Numbers Media API](https://apis.io/collections/bandwidth/open-bandwidth-media-api/)
- [Bandwidth Emergency Calling Available Numbers Messages API](https://apis.io/collections/bandwidth/open-bandwidth-messages-api/)
- [Bandwidth Messaging API](https://apis.io/collections/bandwidth/open-bandwidth-messaging-api/)
- [Bandwidth Emergency Calling Available Numbers MFA API](https://apis.io/collections/bandwidth/open-bandwidth-mfa-api/)
- [Bandwidth Emergency Calling Available Numbers Number Features API](https://apis.io/collections/bandwidth/open-bandwidth-number-features-api/)
- [Bandwidth Emergency Calling Available Numbers Orders API](https://apis.io/collections/bandwidth/open-bandwidth-orders-api/)
- [Bandwidth Emergency Calling Available Numbers Phone Numbers API](https://apis.io/collections/bandwidth/open-bandwidth-phone-numbers-api/)
- [Bandwidth Emergency Calling Available Numbers Port-Ins API](https://apis.io/collections/bandwidth/open-bandwidth-port-ins-api/)
- [Bandwidth Emergency Calling Available Numbers Recordings API](https://apis.io/collections/bandwidth/open-bandwidth-recordings-api/)
- [Bandwidth Emergency Calling Available Numbers SIP Peers API](https://apis.io/collections/bandwidth/open-bandwidth-sip-peers-api/)
- [Bandwidth Emergency Calling Available Numbers Sites API](https://apis.io/collections/bandwidth/open-bandwidth-sites-api/)
- [Bandwidth Emergency Calling Available Numbers Toll-Free Verification API](https://apis.io/collections/bandwidth/open-bandwidth-toll-free-verification-api/)
- [Bandwidth Voice API](https://apis.io/collections/bandwidth/open-bandwidth-voice-api/)
- [Bandwidth Emergency Calling Available Numbers API](https://apis.io/collections/bandwidth/postman-bandwidth-available-numbers-api/)
- [Bandwidth Emergency Calling Available Numbers Calls API](https://apis.io/collections/bandwidth/postman-bandwidth-calls-api/)
- [Bandwidth Emergency Calling Available Numbers Conferences API](https://apis.io/collections/bandwidth/postman-bandwidth-conferences-api/)
- [Bandwidth Emergency Calling Available Numbers Disconnects API](https://apis.io/collections/bandwidth/postman-bandwidth-disconnects-api/)
- …and 14 more published on APIs.io

#### Governance rules (4)

Spectral rulesets for the provider's contracts.

- [Bandwidth — asyncapi rules](https://apis.io/rules/bandwidth/bandwidth-asyncapi-spectral-rules/)
- [Bandwidth — jsonschema rules](https://apis.io/rules/bandwidth/bandwidth-jsonschema-spectral-rules/)
- [Bandwidth API Rules](https://apis.io/rules/bandwidth/bandwidth-rules/)
- [Bandwidth API Rules](https://apis.io/rules/bandwidth/bandwidth-spectral-rules/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Bandwidth Authentication](https://apis.io/security/bandwidth/bandwidth-authentication/)
- [Bandwidth Domain Security](https://apis.io/security/bandwidth/bandwidth-domain-security/)
- [Bandwidth Trust Center](https://apis.io/security/bandwidth/bandwidth-trust-center/)
- [Bandwidth Vulnerability Disclosure](https://apis.io/security/bandwidth/bandwidth-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Bandwidth Plans Pricing](https://apis.io/plans/bandwidth/bandwidth-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Bandwidth Rate Limits](https://apis.io/rate-limits/bandwidth/bandwidth-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Bandwidth Finops](https://apis.io/finops/bandwidth/bandwidth-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.bandwidth.com/)
- [Documentation](https://dev.bandwidth.com/)
- [Getting started](https://dev.bandwidth.com/docs/voice/programmable-voice/build-free-trial)
- [Pricing](https://www.bandwidth.com/pricing/)
- [Support](https://support.bandwidth.com/)
- [Changelog](https://www.bandwidth.com/release-notes/)
- [Blog](https://www.bandwidth.com/blog/)
- [Security](https://www.bandwidth.com/security/)
- [Compliance](https://www.bandwidth.com/security/)
- [Terms of service](https://www.bandwidth.com/legal/)
- [Privacy policy](https://www.bandwidth.com/legal/privacy-policy/)
- [GitHub](https://github.com/Bandwidth)
- [Status](https://status.bandwidth.com/)

## API Evangelist rating

**Kin Score 61.0** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 82.1 |
| Contract quality | 72.4 |
| Contract governance | 31.8 |
| Operational transparency | 60.5 |
| Developer ergonomics | 45.8 |
| Access clarity | 65.8 |

**Agent readiness 34.8** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | yes |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | documented (partial credit) |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 30.0** — Telecommunications

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/bandwidth/](https://apis.io/providers/bandwidth/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Bandwidth: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/bandwidth/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
