# Step15: VPC (Virtual Private Cloud)

## What is VPC?
A VPC is an isolated network environment in AWS.
It allows you to securely deploy and manage resources within a private network.

---
## Core Components

### Subnet
A subnet divides a VPC into smaller segments.
- Public Subnet: allows access to the internet
- Private Subnet: restricts direct internet access

A subnet is considered public if it has a route to an Internet Gateway.

---
### Internet Gateway
An Internet Gateway enables communication between a VPC and the internet.

---
## Key Concept
- Public Subnet = exposed to the internet  
- Private Subnet = internal use only  

---
## Why VPC is Important
VPC improves security by separating resources:
- Public resources (e.g., web servers)
- Private resources (e.g., databases)

---
## Relationship to API Architecture
- VPC controls **network access (can you reach it?)**
- API defines **actions (GET, POST, etc.)**
- OAuth manages **permissions (what you are allowed to do)**

---
## Summary
A VPC provides a secure and controlled network environment, using public and private subnets and an Internet Gateway to manage connectivity.
