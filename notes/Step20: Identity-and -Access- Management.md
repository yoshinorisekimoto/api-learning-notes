# Step20: IAM (Identity and Access Management)

## What is IAM?
IAM is a service that manages access control in AWS.
It defines who can access resources and what actions they can perform.

---
## Authentication vs Authorization
- Authentication: verifies identity (who you are)
- Authorization: defines permissions (what you can do)

---
## Core Components
### Role
A role defines an identity that can be assumed by services or users.

---
### Policy
A policy defines permissions, specifying allowed or denied actions.

---
## Relationship to API
- API Key → Authentication (who)
- OAuth Scope → Authorization (what)

---
## Key Concept
IAM = control of identity and permissions

---
## Summary
IAM provides a secure way to manage access by separating identity (authentication) and permissions (authorization) using roles and policies.
