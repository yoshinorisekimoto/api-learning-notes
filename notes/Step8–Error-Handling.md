# Step 8 – Error Handling

## What I learned
- API failures are categorized using HTTP status codes
- Different error codes indicate different causes of failure

## Key concepts
- 400 Bad Request = invalid request from the client
- 401 Unauthorized = authentication is missing or invalid
- 500 Internal Server Error = failure on the server side

## Additional Learnings
- Test APIs may not always return realistic error responses
- JSONPlaceholder is useful for practice, but it does not strictly validate all bad requests
- Understanding the meaning of error codes is more important than reproducing every error in a mock API

## Why it matters
Error codes help identify whether a problem comes from the request, authentication, or the server.
This is essential for debugging and understanding API behavior in real-world systems.
