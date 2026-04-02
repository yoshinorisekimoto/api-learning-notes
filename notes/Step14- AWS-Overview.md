# STEP14: AWS Overview

## Objective
Understand AWS as a high-level architecture and explain how it relates to API design.

---

## What is AWS?

AWS is a cloud platform that provides infrastructure (compute, storage, networking) as services.

In simple terms:  
**AWS = Infrastructure exposed via APIs**

---

## Core Architecture (4 Layers)

AWS can be understood in the following four layers:

### 1. Global Infrastructure
- Region (e.g., Tokyo, US)
- Availability Zone (AZ)

Purpose:
- High availability
- Fault tolerance

---

### 2. Network (VPC)
- Virtual Private Cloud (VPC)
- Public / Private Subnet

Purpose:
- Isolated network environment
- Control inbound/outbound traffic

---

### 3. Compute
- EC2 (Virtual Machine)
- Lambda (Serverless)

Purpose:
- Execute business logic

---

### 4. Storage / Database
- S3 (Object Storage)
- RDS (Relational Database)

Purpose:
- Store data

---

## Mapping to API Architecture

| API Concept       | AWS Service              |
|------------------|--------------------------|
| Endpoint         | API Gateway              |
| Business Logic   | Lambda / EC2             |
| Database         | RDS / DynamoDB           |
| File Storage     | S3                       |
| Authentication   | IAM / Cognito            |
| Rate Limiting    | API Gateway / WAF        |
| Webhook / Event  | EventBridge / SNS        |

Key Insight:  
**AWS is an extension of API design into infrastructure**

---

## Key Concept

System structure can be simplified as:

- API = Entry point  
- Business Logic = Processing  
- Data = Storage (DB / File)  

---

## Summary (30-second explanation)

AWS provides infrastructure as modular services across networking, compute, and storage.

From an API perspective:
- API Gateway handles requests
- Lambda or EC2 processes logic
- RDS and S3 store data

This allows systems to scale and operate reliably by design.

---

## Key Takeaways

- AWS = Infrastructure as a service  
- Everything is modular and API-driven  
- Designed for scalability and reliability  
- Closely aligned with API architecture concepts  

