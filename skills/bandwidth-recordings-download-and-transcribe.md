---
name: bandwidth-recordings-download-and-transcribe
description: Download a call recording and obtain its transcription.
api: openapi/bandwidth-recordings-api-openapi.yml
operations:
- listAccountRecordings
- getCallRecording
- getCallRecordingMedia
- createRecordingTranscription
- getRecordingTranscription
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/bandwidth-recordings-api-openapi.yml ; every operationId checked against the contract
---

# bandwidth-recordings-download-and-transcribe

Download a call recording and obtain its transcription.

## Steps

1. 1. `listAccountRecordings` – query parameters: `accountId` (path), optional pagination parameters as defined by the contract.
2. 2. `getCallRecording` – path parameters: `accountId`, `callId`, `recordingId`.
3. 3. `getCallRecordingMedia` – path parameters: `accountId`, `callId`, `recordingId`; returns the media file.
4. 4. `createRecordingTranscription` – path parameters: `accountId`, `callId`, `recordingId`; request body may include transcription options.
5. 5. `getRecordingTranscription` – path parameters: `accountId`, `callId`, `recordingId`; retrieves the transcription result.

## Rules

- Authentication: include a Basic Auth header as defined by the `basicAuth` scheme.
- All endpoints use standard HTTP status codes; no special idempotency keys are required.
