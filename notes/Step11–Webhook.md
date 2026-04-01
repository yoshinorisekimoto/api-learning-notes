# Step 11 – Webhook (Push-based Communication)

## What I learned
- APIs can communicate in two ways: Pull and Push
- Webhooks represent a Push-based communication model

## Key concepts
- Pull: Client requests data (e.g., GET request)
- Push: Server sends data automatically (e.g., Webhook via POST)
- Webhooks are event-driven

## Hands-on understanding
- Simulated a webhook by sending a POST request
- Instead of creating data, the POST represents an event notification

## Example
- Payment completed → payment service sends POST to your system
- GitHub push → webhook notification sent to your API

## Why it matters
- Eliminates the need for constant polling
- Enables real-time communication
- Improves system efficiency

## Important consideration
- Webhooks may be delivered multiple times
- Idempotency is required to safely handle duplicate events

## Summary
Webhooks enable push-based communication, where systems send event-driven data automatically. This requires idempotent handling to ensure safe processing.
