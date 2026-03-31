# Step 9 – Rate Limiting

## What I learned
- APIs often limit the number of requests a client can make within a certain time period
- This is known as rate limiting

## Key concepts
- Rate limiting controls how many requests are allowed
- It helps prevent excessive usage and protects the system

## Headers
- X-RateLimit-Limit = maximum number of requests
- X-RateLimit-Remaining = remaining requests
- X-RateLimit-Reset = time until reset

## Additional Learnings
- Some test APIs do not return rate limit headers
- Understanding the concept is more important than observing it in all APIs

## Why it matters
Rate limiting prevents system overload and ensures fair usage among clients.
It is essential for maintaining stable and secure APIs.

## Key Insight
Rate limiting is a mechanism to protect system stability and ensure fair access among multiple clients.
