# Step 11: Webhook (Push-based Communication)

## What is Webhook

Webhook is a mechanism where one system automatically sends data to another system via HTTP POST when an event occurs.

Unlike REST APIs where the client requests data (pull), Webhooks push data without being requested.

## What I did

I simulated a webhook by sending a POST request using Postman.

{
  "event": "order.created",
  "order_id": "12345",
  "amount": 5000
}

## Result

The server returned:

{
  "event": "order.created",
  "order_id": "12345",
  "amount": 5000,
  "id": 101
}

This means the server received and processed the event.

## Key Learnings

- Webhook is push-based communication
- It is triggered by events, not by client requests
- Data is sent automatically via POST
- The receiving system must be ready to handle incoming requests

## Real-world Examples

- Payment systems: payment completed → webhook sent
- Messaging systems: new message → event notification
- ATS: application submitted → webhook triggered

## Important Consideration

Webhook events may be sent multiple times.

Therefore, idempotency is important to prevent duplicate processing.

## Additional Insight

Webhook requires a publicly accessible endpoint to receive requests.
