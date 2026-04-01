# Step 12: Design Thinking (Why API Design Matters)

## Why REST → Standardization & scalability
REST is used because it provides a simple, standardized, and scalable way for systems to communicate.
It uses HTTP methods like GET, POST, PATCH, and DELETE, which are widely understood and easy to adopt.
Because REST is stateless, each request is independent, which makes systems more scalable and easier to maintain.
It is especially suitable for distributed systems and platform ecosystems where many different clients interact with the same API.
This section explains "why" behind API design decisions.

## Why Rate Limiting → System protection & fairness
Rate limiting is used to protect the system and ensure fair usage.
Without rate limiting, a single client could overload the system, causing performance issues or downtime.
It also prevents abuse, such as excessive requests or malicious attacks.
From a platform perspective, rate limiting ensures stability and reliability for all users.

## Why Oauth → Secure delegated access
OAuth is used to securely delegate access without sharing user credentials.
Instead of giving a password, a system can issue a limited-scope access token.
This improves security and allows fine-grained control over permissions.
It is essential for integrations where third-party systems need controlled access to resources.

## Summary
REST provides a standardized and scalable way for systems to communicate.
Rate limiting protects the system and ensures fair and stable usage.
OAuth enables secure and controlled access without exposing credentials.
Together, these design choices support scalable, secure, and reliable platform architectures.
