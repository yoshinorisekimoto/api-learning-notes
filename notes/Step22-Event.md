# Step22: Event (Push-Based Architecture)

## What is an Event?
An event represents something that has happened in the system.

---
## Push vs Pull
- API: pull-based (request/response)
- Event: push-based (triggered automatically)

---
## Webhook vs Event Services
Webhooks are simple push mechanisms.
AWS extends this with event-driven services for better scalability and management.

---
## EventBridge
EventBridge routes events to different services based on rules.

---
## SNS (Simple Notification Service)
SNS distributes events to multiple subscribers.

---
## Key Concept
Event = push-based execution model
Event-driven architecture enables loosely coupled systems where components do not need to directly call each other.

---
## Difference from API
- API: request-driven
- Event: event-driven

---

## Summary

Event-driven architecture enables loosely coupled systems by reacting to events, improving scalability and flexibility.
