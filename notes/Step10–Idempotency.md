# Step 10 – Idempotency

## What I learned
- Idempotency means that making the same request multiple times results in the same outcome
- API operations can be idempotent or non-idempotent depending on their behavior

## Key concepts
- POST is non-idempotent because it creates new resources
- PUT is idempotent because it updates or replaces the same resource
- Idempotency is evaluated based on the outcome, not the input

## Hands-on observation
- Sent POST requests multiple times with the same request body
- Received a response with an `id` field each time
- In this mock API (JSONPlaceholder), the returned `id` remained the same (e.g., 101)

## Additional insights
- The returned `id` represents the created resource, not a user or account ID
- In real-world APIs, repeated POST requests typically create different resources (e.g., different IDs)
- In this mock API, the behavior is simulated and does not persist data

## Why it matters
- Idempotency is important for handling retries, network failures, and duplicate requests
- Without idempotency, repeated requests may cause unintended side effects (e.g., duplicate records)
- It is a key concept in designing reliable and resilient APIs

## Summary
POST requests are not idempotent because they create new resources, while PUT requests are idempotent because they ensure the same result even when repeated.
