# Bandwidth GraphQL Schema

## Overview

This document describes a conceptual GraphQL schema for the Bandwidth cloud communications platform. Bandwidth provides voice, messaging, phone number management, multi-factor authentication, emergency calling (E911), and toll-free verification APIs built on its own Tier 1 network.

The schema is derived from Bandwidth's REST APIs:
- Voice API: https://voice.bandwidth.com/api/v2
- Messaging API: https://messaging.bandwidth.com/api/v2
- Phone Numbers (Dashboard/Iris) API: https://dashboard.bandwidth.com/api
- MFA API: https://mfa.bandwidth.com/api/v1
- Emergency Calling API: https://dashboard.bandwidth.com/api

Source: https://dev.bandwidth.com/

## Schema File

See `bandwidth-schema.graphql` for the full type definitions.

## Domain Coverage

### Phone Number Management
Types covering telephone number (TN) inventory, ordering, porting, reservations, toll-free numbers, disconnect orders, and port-out reports. Modeled after the Bandwidth Iris/Dashboard API which uses a hierarchical Account > Site > SIP Peer structure.

Key types: `PhoneNumber`, `TN`, `TNReservation`, `Location`, `SIPPeer`, `Site`, `Order`, `OrderNote`, `ImportTNOrder`, `PortInOrder`, `TollFreeOrder`, `NewNumberOrder`, `DisconnectOrder`, `PortOutReport`

### Messaging
Types covering SMS and MMS message sending and receiving, group messaging, callbacks/webhooks, and application configuration for messaging.

Key types: `Message`, `MessageRequest`, `Callback`, `GroupMessage`, `MMS`, `Segment`, `ApplicationMessaging`, `WebhookNotification`

### Voice
Types covering outbound and inbound call management, call routing, BXML verb-based call control, conference management, recordings, and application configuration.

Key types: `Call`, `CallRoute`, `ApplicationVoice`, `BXML`, `BXMLVerb`, `Ring`, `Forward`, `Transfer`, `Redirect`, `Conference`, `ConferenceRecord`, `Gather`, `SpeakSentence`, `Record`, `Bridge`, `Hangup`, `Pause`, `PlayAudio`, `SendDTMF`, `StartStream`

### Emergency Services
Types covering E911 endpoint provisioning, emergency caller ID, and Dynamic Location Routing (DLR) for compliance with Kari's Law and RAY BAUM's Act.

Key types: `EmergencyCallerID`, `E911`, `E911Location`, `E911Endpoint`, `DLRSession`

### Account & Identity
Types covering dashboard users, account management, subscriptions, and webhook notification configuration.

Key types: `DashboardUser`, `DashboardAccount`, `Subscription`, `WebhookNotification`

### Multi-Factor Authentication
Types covering OTP code generation and verification via SMS or voice.

Key types: `MFARequest`, `MFAVerification`, `MFACode`

## Query Design

### Root Queries
- `phoneNumber(tnid: ID!)` — fetch a single TN by ID
- `phoneNumbers(accountId: ID!, filters: PhoneNumberFilter)` — list TNs with filtering
- `order(orderId: ID!)` — retrieve any order by ID
- `orders(accountId: ID!, type: OrderType, status: OrderStatus)` — list orders
- `message(messageId: ID!)` — retrieve a sent/received message
- `call(callId: ID!)` — retrieve a call resource
- `conference(conferenceId: ID!)` — retrieve a conference
- `site(siteId: ID!)` — retrieve a site
- `sipPeer(sipPeerId: ID!)` — retrieve a SIP peer
- `account(accountId: ID!)` — retrieve account details
- `e911Endpoint(endpointId: ID!)` — retrieve an E911 endpoint

### Root Mutations
- `createOrder(input: OrderInput!)` — place a new number order
- `sendMessage(input: MessageRequestInput!)` — send an SMS/MMS
- `createCall(input: CallInput!)` — initiate an outbound call
- `modifyCall(callId: ID!, input: CallModifyInput!)` — modify an in-progress call
- `createConference(input: ConferenceInput!)` — create a conference
- `provisionE911(input: E911Input!)` — provision an E911 endpoint
- `createMFARequest(input: MFARequestInput!)` — send an MFA code
- `verifyMFACode(input: MFAVerifyInput!)` — verify an MFA code

## Notes

- This schema is conceptual and not officially provided by Bandwidth.
- Bandwidth's production APIs are REST-based; this GraphQL schema is a design artifact representing equivalent capabilities.
- BXML verb types map to XML elements used in Bandwidth's Voice API for call flow control.
- The Iris/Dashboard API uses an XML-over-REST pattern; GraphQL types here represent the underlying data model.
