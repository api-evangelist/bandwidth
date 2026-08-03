# Bandwidth (bandwidth)

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

Bandwidth is a leading cloud-based communications platform providing voice, messaging, emergency calling, phone number management, multi-factor authentication, and toll-free verification APIs. Built on Bandwidth's own Tier 1 network, the platform delivers enterprise-grade reliability for CPaaS applications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/bandwidth/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/bandwidth/refs/heads/main/apis.yml)

## Tags

- Communications
- CPaaS
- Voice
- Messaging
- Telephony
- SMS
- MFA

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Bandwidth Voice API

The Bandwidth Voice API enables developers to programmatically make and receive phone calls, manage call recordings, and create multi-party conferences. It supports advanced call control features including call transfers, bridging, DTMF detection, and text-to-speech. The API uses BXML (Bandwidth XML) verbs for call flow control and provides webhooks for real-time event notifications on call state changes.

- **Human URL:** [https://dev.bandwidth.com/docs/voice/](https://dev.bandwidth.com/docs/voice/)
- **Base URL:** `https://voice.bandwidth.com/api/v2`

#### Tags

- Calls
- Conferences
- CPaaS
- Recordings
- Telephony
- Voice

#### Properties

- [Documentation](https://dev.bandwidth.com/docs/voice/)
- [OpenAPI](openapi/bandwidth-voice-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bandwidth-voice-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bandwidth-voice-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/bandwidth-voice-events-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### Bandwidth Messaging API

The Bandwidth Messaging API allows developers to send and receive SMS and MMS messages programmatically. It supports both toll-free and local number messaging, group messaging, and application-to-person (A2P) messaging workflows. The API provides delivery receipts via webhooks, message status tracking, and media management for MMS attachments. Bandwidth operates its own tier-1 network, providing direct carrier connectivity for reliable message delivery.

- **Human URL:** [https://dev.bandwidth.com/docs/messaging/](https://dev.bandwidth.com/docs/messaging/)
- **Base URL:** `https://messaging.bandwidth.com/api/v2`

#### Tags

- CPaaS
- Messaging
- MMS
- SMS
- Text Messaging

#### Properties

- [Documentation](https://dev.bandwidth.com/docs/messaging/)
- [OpenAPI](openapi/bandwidth-messaging-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bandwidth-messaging-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bandwidth-messaging-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/bandwidth-messaging-events-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### Bandwidth Phone Numbers API

The Bandwidth Phone Numbers API provides programmatic access to search, order, and manage phone numbers across the United States and Canada. Developers can search for available local, toll-free, and short code numbers, initiate number porting requests, and configure number features such as CNAM, directory listings, and line features. The API also supports managing sites, SIP peers, and number assignments for organizing telephony resources within an account.

- **Human URL:** [https://dev.bandwidth.com/docs/numbers/](https://dev.bandwidth.com/docs/numbers/)
- **Base URL:** `https://dashboard.bandwidth.com/api`

#### Tags

- Number Management
- Phone Numbers
- Porting
- Telecom
- Telephone Numbers

#### Properties

- [Documentation](https://dev.bandwidth.com/docs/numbers/)
- [OpenAPI](openapi/bandwidth-phone-numbers-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bandwidth-phone-numbers-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bandwidth-phone-numbers-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bandwidth Multi-Factor Authentication API

The Bandwidth Multi-Factor Authentication API allows developers to generate and verify secure MFA codes delivered via voice calls or SMS messages. It leverages Bandwidth's Voice and Messaging APIs under the hood, handling token generation and management automatically. Developers can customize the code length, expiration time, and delivery message template. The API supports both one-time passcode delivery and verification in a simple two-step workflow.

- **Human URL:** [https://dev.bandwidth.com/docs/mfa/](https://dev.bandwidth.com/docs/mfa/)
- **Base URL:** `https://mfa.bandwidth.com/api/v1`

#### Tags

- Authentication
- MFA
- Security
- Two-Factor Authentication
- Verification

#### Properties

- [Documentation](https://dev.bandwidth.com/docs/mfa/)
- [OpenAPI](openapi/bandwidth-mfa-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bandwidth-mfa-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bandwidth-mfa-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bandwidth Emergency Calling API

The Bandwidth Emergency Calling API provides programmatic access to provision and manage 911 endpoints and locations for emergency services routing. It supports Dynamic Location Routing (DLR) for real-time address validation and location updates, ensuring compliance with Kari's Law and RAY BAUM's Act requirements.

- **Human URL:** [https://dev.bandwidth.com/docs/emergency/emergencyCallingApi/](https://dev.bandwidth.com/docs/emergency/emergencyCallingApi/)
- **Base URL:** `https://dashboard.bandwidth.com/api`

#### Tags

- Compliance
- E911
- Emergency Services
- Public Safety

#### Properties

- [Documentation](https://dev.bandwidth.com/docs/emergency/emergencyCallingApi/)
- [OpenAPI](openapi/bandwidth-emergency-calling-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bandwidth-emergency-calling-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bandwidth-emergency-calling-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bandwidth Toll-Free Verification API

The Bandwidth Toll-Free Verification API enables developers to programmatically submit and manage toll-free number verification requests for A2P messaging compliance. It automates the verification submission process, allowing developers to view and update the verification status of their toll-free numbers.

- **Human URL:** [https://dev.bandwidth.com/apis/messaging-apis/toll-free-verification/](https://dev.bandwidth.com/apis/messaging-apis/toll-free-verification/)
- **Base URL:** `https://dashboard.bandwidth.com/api`

#### Tags

- A2P
- Messaging Compliance
- Toll-Free
- Verification

#### Properties

- [Documentation](https://dev.bandwidth.com/apis/messaging-apis/toll-free-verification/)
- [OpenAPI](openapi/bandwidth-toll-free-verification-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bandwidth-toll-free-verification-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bandwidth-toll-free-verification-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/Bandwidth)
- [LinkedIn](https://www.linkedin.com/company/bandwidth-inc)
- [Website](https://www.bandwidth.com/)
- [Documentation](https://dev.bandwidth.com/)
- [Sign Up](https://app.bandwidth.com/signup)
- [Blog](https://www.bandwidth.com/blog/)
- [Terms of Service](https://www.bandwidth.com/legal/)
- [Privacy Policy](https://www.bandwidth.com/legal/privacy-policy/)
- [Status Page](https://status.bandwidth.com/)
- [Support](https://support.bandwidth.com/)
- [SDK](https://dev.bandwidth.com/sdks/)
- [Spectral Rules](rules/bandwidth-spectral-rules.yml)
- [Vocabulary](vocabulary/bandwidth-vocabulary.yaml)
- [JSON Schema](json-schema/bandwidth-call-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/bandwidth-message-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/bandwidth-phone-number-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/bandwidth-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Integrations](https://www.bandwidth.com/integrations/)
- [L L Ms Txt](https://dev.bandwidth.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
