# Step21: API Gateway

## What is API Gateway?
API Gateway is a service that acts as the entry point for APIs in AWS. It receives requests and routes them to backend services such as Lambda or EC2.

---
## Core Functions
### Endpoint Management
API Gateway defines and manages API endpoints.

---
### Routing
API Gateway routes requests to backend services such as Lambda or EC2.

---
### Rate Limiting
API Gateway controls traffic by limiting requests.
Rate limiting protects APIs from excessive traffic and ensures stable performance.

---
## Role in Architecture
User → API Gateway → Compute (Lambda / EC2) → Storage (RDS / S3)

---
## Key Concept
API Gateway = API entry point and traffic control layer

---
## Summary
API Gateway provides a centralized way to manage API endpoints, control traffic, and route requests to backend services.
