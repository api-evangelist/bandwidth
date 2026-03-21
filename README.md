# Bandwidth (bandwidth)
Bandwidth is a communications platform as a service (CPaaS) provider that operates its own nationwide tier-1 network in the United States. Their developer platform offers APIs for voice calling, messaging, phone number management, multi-factor authentication, emergency calling, and toll-free verification, enabling enterprises to embed communications directly into their applications.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/bandwidth/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - CPaaS, Voice, Messaging, SMS, Telephony, Phone Numbers, Communications

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-03-20

## APIs

### Bandwidth Voice API
The Bandwidth Voice API enables developers to programmatically make and receive phone calls, manage call recordings, and create multi-party conferences. It supports advanced call control features including call transfers, bridging, DTMF detection, and text-to-speech. The API uses BXML (Bandwidth XML) verbs for call flow control and provides webhooks for real-time event notifications on call state changes.

**Human URL:** [https://dev.bandwidth.com/docs/voice/](https://dev.bandwidth.com/docs/voice/)


#### Tags:

 - Voice, Telephony, CPaaS, Calls, Recordings, Conferences

#### Properties

- [Documentation](https://dev.bandwidth.com/docs/voice/)
- [OpenAPI](openapi/bandwidth-voice-api-openapi.yml)
- [AsyncAPI](asyncapi/bandwidth-voice-events-asyncapi.yml)

### Bandwidth Messaging API
The Bandwidth Messaging API allows developers to send and receive SMS and MMS messages programmatically. It supports both toll-free and local number messaging, group messaging, and application-to-person (A2P) messaging workflows. The API provides delivery receipts via webhooks, message status tracking, and media management for MMS attachments. Bandwidth operates its own tier-1 network, providing direct carrier connectivity for reliable message delivery.

**Human URL:** [https://dev.bandwidth.com/docs/messaging/](https://dev.bandwidth.com/docs/messaging/)


#### Tags:

 - Messaging, SMS, MMS, CPaaS, Text Messaging

#### Properties

- [Documentation](https://dev.bandwidth.com/docs/messaging/)
- [OpenAPI](openapi/bandwidth-messaging-api-openapi.yml)
- [AsyncAPI](asyncapi/bandwidth-messaging-events-asyncapi.yml)

### Bandwidth Phone Numbers API
The Bandwidth Phone Numbers API provides programmatic access to search, order, and manage phone numbers across the United States and Canada. Developers can search for available local, toll-free, and short code numbers, initiate number porting requests, and configure number features such as CNAM, directory listings, and line features. The API also supports managing sites, SIP peers, and number assignments for organizing telephony resources within an account.

**Human URL:** [https://dev.bandwidth.com/docs/numbers/](https://dev.bandwidth.com/docs/numbers/)


#### Tags:

 - Phone Numbers, Telephone Numbers, Porting, Number Management, Telecom

#### Properties

- [Documentation](https://dev.bandwidth.com/docs/numbers/)
- [OpenAPI](openapi/bandwidth-phone-numbers-api-openapi.yml)

### Bandwidth Multi-Factor Authentication API
The Bandwidth Multi-Factor Authentication API allows developers to generate and verify secure MFA codes delivered via voice calls or SMS messages. It leverages Bandwidth's Voice and Messaging APIs under the hood, handling token generation and management automatically. Developers can customize the code length, expiration time, and delivery message template. The API supports both one-time passcode delivery and verification in a simple two-step workflow.

**Human URL:** [https://dev.bandwidth.com/docs/mfa/](https://dev.bandwidth.com/docs/mfa/)


#### Tags:

 - Authentication, MFA, Two-Factor Authentication, Security, Verification

#### Properties

- [Documentation](https://dev.bandwidth.com/docs/mfa/)
- [OpenAPI](openapi/bandwidth-mfa-api-openapi.yml)

### Bandwidth Emergency Calling API
The Bandwidth Emergency Calling API provides programmatic access to provision and manage 911 endpoints and locations for emergency services routing. It supports Dynamic Location Routing (DLR) for real-time address validation and location updates, ensuring compliance with Kari's Law and RAY BAUM's Act requirements. Bandwidth is the only CPaaS provider that also operates its own emergency services network, providing direct connectivity to public safety answering points (PSAPs) across the United States and Canada.

**Human URL:** [https://dev.bandwidth.com/docs/emergency/emergencyCallingApi/](https://dev.bandwidth.com/docs/emergency/emergencyCallingApi/)


#### Tags:

 - Emergency Services, E911, 911, Public Safety, Compliance

#### Properties

- [Documentation](https://dev.bandwidth.com/docs/emergency/emergencyCallingApi/)
- [OpenAPI](openapi/bandwidth-emergency-calling-api-openapi.yml)

### Bandwidth Toll-Free Verification API
The Bandwidth Toll-Free Verification API enables developers to programmatically submit and manage toll-free number verification requests for A2P messaging compliance. It automates the verification submission process, allowing developers to view and update the verification status of their toll-free numbers. This API helps ensure that toll-free messaging traffic complies with carrier requirements and regulations including the Telephone Consumer Protection Act (TCPA).

**Human URL:** [https://dev.bandwidth.com/apis/messaging-apis/toll-free-verification/](https://dev.bandwidth.com/apis/messaging-apis/toll-free-verification/)


#### Tags:

 - Toll-Free, Verification, Messaging Compliance, A2P

#### Properties

- [Documentation](https://dev.bandwidth.com/apis/messaging-apis/toll-free-verification/)
- [OpenAPI](openapi/bandwidth-toll-free-verification-api-openapi.yml)

## Common Properties

- [Portal](https://dev.bandwidth.com/)
- [Documentation](https://dev.bandwidth.com/docs/)
- [Website](https://www.bandwidth.com/)
- [PrivacyPolicy](https://www.bandwidth.com/privacy-policy/)
- [TermsOfService](https://www.bandwidth.com/terms-of-use/)
- [Support](https://support.bandwidth.com/)
- [Blog](https://www.bandwidth.com/blog/)
- [Login](https://app.bandwidth.com/)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
