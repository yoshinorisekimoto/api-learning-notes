# API Learning Notes

## Overview
This repository contains my hands-on learning journey for API fundamentals and architecture concepts. The goal is not only to understand APIs, but to be able to explain system design concepts clearly.

This repository is also intended to demonstrate my ability to design and explain API-driven systems in platform and ecosystem environments.This repository demonstrates not only my technical understanding of APIs, but also my ability to connect API concepts to platform architecture and ecosystem design.

## What I Learned
- REST API fundamentals (GET, POST, PATCH, DELETE)
- JSON structure and data communication
- Authentication (API Key, Bearer Token, OAuth concept)
- API design and collections
- Error handling (400, 401, 500)
- Rate limiting
- Idempotency
- Webhook (push-based communication)

## Structure
Each topic is organized step by step:

- [Step 1 - API Basics](notes/Step1-api-basics.md)
- [Step 2 - CRUD with API](notes/Step2-crud-with-api.md)
- [Step 3 - API Parameters](notes/Step3-api-parameters.md)
- [Step 4 - JSON Structure](notes/Step4-json-structure.md)
- [Step 5 - API Authentication](notes/Step5-API-Authentication.md)
- [Step 6 - Collections and Environment Variables](notes/Step6-Collections-Environment-Variables.md)
- [Step 7 - Review and Articulation](notes/Step7-Review-Articulation.md)
- [Step 8 - Error Handling](notes/Step8–Error-Handling.md)
- [Step 9 - Rate Limiting](notes/Step9–Rate-Limiting.md)
- [Step 10 - Idempotency](notes/Step10–Idempotency.md)
- [Step 11 - Webhook(Push-based Communication)](notes/Step11–Webhook.md)
- [Step 12 - Design Thinking (Why API Design Matters)](notes/Step12-Design-Thinking.md)
- [Step 13 - AWS Overview](notes/Step13-AWS-Overview.md)
- [Step 14 - Region/Availability Zone](notes/Step14-Region-Availability-Zone.md)
- [Step 15 - VPC (Virtual Private Cloud)](notes/Step15-Virtual-Private-Cloud.md)
- [Step 16 - EC2 (Elastic Compute Cloud)](notes/Step16-Elastic-Compute-Cloud.md)
- [Step 17 - Lambda (Serverless)](notes/Step17-Lambda-Serverless.md)
- [Step 18 - S3 (Object Storage)](notes/Step18-S3-Object-Storage.md)
- [Step 19 - RDS (Relational Database Service)](notes/Step19-Relational-Database-Service.md)
- [Step 20 - IAM (Identity and Access Management)](notes/Step20-Identity-and-Access-Management.md)
- [Step 21 - API Gateway](notes/Step21-API-Gateway.md)
- [Step 22 - Event (Push-Based Architecture)](notes/Step22-Event.md)
- [Step 23 - Scaling](notes/Step23-Scaling.md)

## Related Learning
Extending API-level understanding to system-level architecture:
- AWS Architecture (Cloud / System Design)
👉 [AWS Learning Plan](notes/AWS-learning-plan.md)

## Scope
This repository focuses on understanding API concepts at an architectural level rather than implementation details.

## Key Takeaway
API is a standardized way for systems to communicate.
Understanding API concepts helps design scalable systems, especially in platform and ecosystem environments.

APIs are the foundation of modern platform ecosystems, enabling scalable integrations between systems.

## Why This Matters
APIs are the foundation of modern platform ecosystems.
Understanding API design, communication patterns, and system behavior is critical for:

- Designing scalable platform architectures
- Enabling partner integrations
- Building API-driven ecosystems

This repository reflects my effort to bridge business and technical perspectives.

<h2>Example API Request</h2>

<table>
  <tr>
    <td valign="top" width="50%">
      <b>POST</b>
      <pre><code>{
  "title": "test"
}</code></pre>
    </td>
    <td valign="top" width="50%">
      <b>Response</b>
      <pre><code>{
  "title": "test",
  "id": 101
}</code></pre>
    </td>
  </tr>
</table>
