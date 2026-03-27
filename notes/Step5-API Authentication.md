# Step 5 – API Authentication

## What I learned
- APIs require authentication to control access
- API Key is a simple method to identify the client
- OAuth uses tokens for more secure and scalable access

## Key concepts
- API Key (simple authentication)
- Authorization header
- Bearer Token (used in OAuth)

## Example
API Key:x-api-key: abc123
OAuth (Bearer Token):
Authorization: Bearer token123

## Additional note
In Postman, setting a Bearer token in the Authorization tab automatically adds it to the request header.

## Why it matters
Authentication is essential to protect APIs from unauthorized access.
In real-world systems, OAuth is widely used to securely manage user access and enable scalable integrations.

OAuth is widely used in real-world systems where user-based authentication is required.

## Summary
Authentication is implemented through headers, where tokens (like Bearer tokens) are used to verify access.
