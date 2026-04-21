# Bandwidth (bandwidth)
Bandwidth is a leading cloud-based communications platform providing voice, messaging, emergency calling, phone number management, multi-factor authentication, and toll-free verification APIs. Built on Bandwidth's own Tier 1 network, the platform delivers enterprise-grade reliability for CPaaS applications.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/bandwidth/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Communications, CPaaS, Voice, Messaging, Telephony, SMS, MFA

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### Bandwidth Voice API
The Bandwidth Voice API enables developers to programmatically make and receive phone calls, manage call recordings, and create multi-party conferences.

**Human URL:** [https://dev.bandwidth.com/docs/voice/](https://dev.bandwidth.com/docs/voice/)

#### Tags:

 - Calls, Conferences, CPaaS, Recordings, Telephony, Voice

#### Properties

- [Documentation](https://dev.bandwidth.com/docs/voice/)
- [OpenAPI](openapi/bandwidth-voice-api-openapi.yml)

### Bandwidth Messaging API
The Bandwidth Messaging API allows developers to send and receive SMS and MMS messages programmatically with direct carrier connectivity.

**Human URL:** [https://dev.bandwidth.com/docs/messaging/](https://dev.bandwidth.com/docs/messaging/)

#### Tags:

 - CPaaS, Messaging, MMS, SMS, Text Messaging

#### Properties

- [Documentation](https://dev.bandwidth.com/docs/messaging/)
- [OpenAPI](openapi/bandwidth-messaging-api-openapi.yml)

### Bandwidth Phone Numbers API
The Bandwidth Phone Numbers API provides programmatic access to search, order, and manage phone numbers across the United States and Canada.

**Human URL:** [https://dev.bandwidth.com/docs/numbers/](https://dev.bandwidth.com/docs/numbers/)

#### Tags:

 - Number Management, Phone Numbers, Porting, Telecom, Telephone Numbers

#### Properties

- [Documentation](https://dev.bandwidth.com/docs/numbers/)
- [OpenAPI](openapi/bandwidth-phone-numbers-api-openapi.yml)

### Bandwidth Multi-Factor Authentication API
The Bandwidth MFA API generates and verifies secure OTP codes delivered via voice or SMS for two-factor authentication workflows.

**Human URL:** [https://dev.bandwidth.com/docs/mfa/](https://dev.bandwidth.com/docs/mfa/)

#### Tags:

 - Authentication, MFA, Security, Two-Factor Authentication, Verification

#### Properties

- [Documentation](https://dev.bandwidth.com/docs/mfa/)
- [OpenAPI](openapi/bandwidth-mfa-api-openapi.yml)

### Bandwidth Emergency Calling API
The Bandwidth Emergency Calling API provisions and manages 911 endpoints and locations for compliant emergency services routing.

**Human URL:** [https://dev.bandwidth.com/docs/emergency/emergencyCallingApi/](https://dev.bandwidth.com/docs/emergency/emergencyCallingApi/)

#### Tags:

 - Compliance, E911, Emergency Services, Public Safety

#### Properties

- [Documentation](https://dev.bandwidth.com/docs/emergency/emergencyCallingApi/)
- [OpenAPI](openapi/bandwidth-emergency-calling-api-openapi.yml)

### Bandwidth Toll-Free Verification API
The Bandwidth Toll-Free Verification API submits and manages A2P toll-free number verification requests for messaging compliance.

**Human URL:** [https://dev.bandwidth.com/apis/messaging-apis/toll-free-verification/](https://dev.bandwidth.com/apis/messaging-apis/toll-free-verification/)

#### Tags:

 - A2P, Messaging Compliance, Toll-Free, Verification

#### Properties

- [Documentation](https://dev.bandwidth.com/apis/messaging-apis/toll-free-verification/)
- [OpenAPI](openapi/bandwidth-toll-free-verification-api-openapi.yml)

## Common Properties

- [Website](https://www.bandwidth.com/)
- [Documentation](https://dev.bandwidth.com/)
- [SignUp](https://app.bandwidth.com/signup)
- [Blog](https://www.bandwidth.com/blog/)
- [TermsOfService](https://www.bandwidth.com/legal/)
- [PrivacyPolicy](https://www.bandwidth.com/legal/privacy-policy/)
- [Status](https://status.bandwidth.com/)
- [Support](https://support.bandwidth.com/)
- [SDK](https://dev.bandwidth.com/sdks/)

## Features

| Name | Description |
|------|-------------|
| Voice Calls | Programmable outbound and inbound voice call management with BXML call control. |
| SMS Messaging | Send and receive SMS messages on local and toll-free numbers. |
| MMS Messaging | Send and receive multimedia messages with images, video, and audio. |
| Multi-Factor Authentication | OTP code delivery and verification via voice or SMS. |
| Phone Number Management | Search, order, port, and configure US and Canadian phone numbers. |
| Emergency Calling (E911) | Dynamic location routing for compliant emergency call handling. |
| Toll-Free Verification | Submit and track A2P toll-free number verification requests. |
| Call Recording | Record and retrieve voice call audio for compliance and analytics. |
| Conferences | Create multi-party voice conferences with participant management. |
| Webhooks | Real-time event notifications for call state changes and message delivery. |
| Tier 1 Network | Direct carrier connectivity on Bandwidth's own nationwide network. |

## Use Cases

| Name | Description |
|------|-------------|
| Click-to-Call | Embed outbound calling in web and mobile applications. |
| IVR Systems | Build interactive voice response menus with DTMF input and TTS. |
| A2P Messaging | Send application-to-person SMS campaigns at scale. |
| 2FA / OTP | Add SMS or voice-based multi-factor authentication to applications. |
| Number Provisioning | Automate phone number procurement and assignment for customers. |
| E911 Compliance | Meet Kari's Law and RAY BAUM's Act requirements for enterprise voice. |
| Call Center | Build inbound/outbound contact center applications with recording. |
| Number Porting | Migrate existing phone numbers to Bandwidth programmatically. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Bandwidth Voice API](openapi/bandwidth-voice-api-openapi.yml)
- [Bandwidth Messaging API](openapi/bandwidth-messaging-api-openapi.yml)
- [Bandwidth Phone Numbers API](openapi/bandwidth-phone-numbers-api-openapi.yml)
- [Bandwidth Multi-Factor Authentication API](openapi/bandwidth-mfa-api-openapi.yml)
- [Bandwidth Emergency Calling API](openapi/bandwidth-emergency-calling-api-openapi.yml)
- [Bandwidth Toll-Free Verification API](openapi/bandwidth-toll-free-verification-api-openapi.yml)

### JSON Schema

- [bandwidth-call-schema.json](json-schema/bandwidth-call-schema.json)
- [bandwidth-message-schema.json](json-schema/bandwidth-message-schema.json)
- [bandwidth-phone-number-schema.json](json-schema/bandwidth-phone-number-schema.json)

### JSON-LD

- [Bandwidth JSON-LD Context](json-ld/bandwidth-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Voice API](capabilities/shared/voice-api.yaml) — 15 operations for call management and recording
- [Messaging API](capabilities/shared/messaging-api.yaml) — 6 operations for SMS/MMS
- [MFA API](capabilities/shared/mfa-api.yaml) — 3 operations for OTP delivery and verification
- [Phone Numbers API](capabilities/shared/phone-numbers-api.yaml) — 22 operations for number management
- [Emergency Calling API](capabilities/shared/emergency-api.yaml) — 12 operations for E911 management
- [Toll-Free Verification API](capabilities/shared/toll-free-api.yaml) — 4 operations for verification

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Communications Platform](capabilities/communications-platform.yaml) | Voice, Messaging, MFA, Phone Numbers, E911, Toll-Free | 12 | Application Developer, Communications Engineer, Platform Administrator |

## Vocabulary

- [Bandwidth Vocabulary](vocabulary/bandwidth-vocabulary.yaml) — Unified taxonomy mapping 6 resources, 7 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Bandwidth Spectral Rules](rules/bandwidth-spectral-rules.yml) — 16 rules across 6 categories enforcing Bandwidth API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
