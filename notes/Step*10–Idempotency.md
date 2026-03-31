# Step 10 – Idempotency

## What I learned
- Idempotency means that making the same request multiple times results in the same effect on the server
- It is an important concept for building reliable and predictable APIs

## Key concepts
- Idempotency is evaluated based on the server state, not just the response
- GET, PUT, and DELETE are typically idempotent
- POST is generally non-idempotent because it creates new resources

## Hands-on observation
- Sent multiple POST requests with the same request body
- Received a response containing an `id` field
- In this mock API (JSONPlaceholder), the returned `id` remained the same (e.g., 101)

## Additional insights
- The returned `id` represents the created resource, not a user or account ID
- In real-world APIs, repeated POST requests typically create different resources (different IDs)
- JSONPlaceholder is a mock API and does not persist data, so the behavior is simulated

## Why it matters
- Idempotency allows safe retries when network failures occur
- Without idempotency, duplicate requests may create unintended side effects (e.g., duplicate records)
- It is essential for designing resilient distributed systems

## Summary
Idempotency ensures that repeating the same request does not change the server state.  
POST is not idempotent because it creates new resources, while PUT is idempotent because it maintains the same result even when repeated.
