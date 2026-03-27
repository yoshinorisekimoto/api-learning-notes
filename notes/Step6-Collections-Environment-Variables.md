# Step 6 – Collections and Environment Variables

## What I learned
- A collection is a group of related API requests
- Environment variables allow reusable values such as base URLs and tokens
- Collections help organize APIs at a service or feature level

## Key concepts
- Collection = logical grouping of API requests
- Environment = reusable configuration for execution context
- Variables make requests easier to manage and reuse

## Example
Base URL as an environment variable:

{{baseUrl}}/posts
{{baseUrl}}/posts/1
{{baseUrl}}/posts?userId=1

## Additional Learnings
- Environment variables must be selected to resolve placeholders like `{{baseUrl}}`
- Using variables makes it easier to switch between environments without changing each request manually

## Why it matters
Collections and environment variables improve API organization, reusability, and maintainability.
They also reflect how APIs are grouped and managed in real-world systems.
