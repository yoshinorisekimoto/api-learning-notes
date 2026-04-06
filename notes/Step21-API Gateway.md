# Step21: API Gateway

## What is API Gateway?
API Gateway is a service that acts as the entry point for APIs in AWS. It receives requests and routes them to backend services such as Lambda or EC2.

---
## Core Functions
### Endpoint Management
API Gateway defines and manages API endpoints such as:
- GET /users
- POST /orders

---
### Rate Limiting
API Gateway controls traffic by limiting the number of requests.
This helps protect the system from overload.

---
## Role in Architecture
User → API Gateway → Compute (Lambda / EC2) → Storage (RDS / S3)

---
## Key Concept
API Gateway = API entry point and traffic control layer

---
## Summary
API Gateway provides a centralized way to manage API endpoints, control traffic, and route requests to backend services.
