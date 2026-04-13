# Step26: System Design (Integration)

## Goal
Understand how API concepts map to cloud architecture.

---
## End-to-End Architecture
User → API Gateway → Compute (Lambda / EC2) → Storage (RDS / S3)
Additional components:
- IAM: security (authentication and authorization)
- Scaling: handles traffic variation
- Multi-AZ: ensures high availability
- EventBridge: enables event-driven architecture

---
## Key Concept
Cloud architecture is an extension of API design.

---
## Summary
A complete system consists of:
- Entry point: API Gateway
- Processing: Lambda / EC2
- Data storage: RDS / S3
- Security: IAM
- Scalability: Auto Scaling / Lambda
- Availability: Multi-AZ / Failover
- Event handling: EventBridge

All components work together to build scalable, secure, and reliable systems.
