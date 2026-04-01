# Step 11: Webhook (Push-based Communication)

## What is Webhook

Webhook is a mechanism where one system automatically sends data to another system via HTTP POST when an event occurs.

Unlike REST APIs where the client requests data (pull), Webhooks push data without being requested.

## What I did

I simulated a webhook by sending a POST request using Postman with the following JSON:

{
  "event": "order.created",
  "order_id": "12345",
  "amount": 5000
}

## Result

The server returned a response with an ID:

{
  "event": "order.created",
  "order_id": "12345",
  "amount": 5000,
  "id": 101
}

This indicates that the server received and processed the event.

## Key Learnings

- Webhook is push-based communication
- It is triggered by events, not by requests
- Data is sent automatically via POST
- The receiver must be ready to handle incoming requests

## Real-world Examples

- Payment systems (e.g., payment completed → notify system)
- Messaging platforms (new message → trigger notification)
- ATS integrations (application submitted → send event)

## Important Consideration

Webhook events can be sent multiple times, so idempotency is important to prevent duplicate processing.

Webhook requires a publicly accessible endpoint to receive the request.
