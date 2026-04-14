# Step22: Event (Push-Based Architecture)

## What is an Event?
An event represents something that has happened in the system.

---
## Push vs Pull
- Push vs Pull
API is typically request-driven (pull-based), where clients request data.
Event-driven systems are push-based, where actions are triggered automatically when something happens.

---
## Webhook vs Event Services
Webhooks are simple push mechanisms implemented using HTTP APIs.
AWS extends this with event-driven services for better scalability and management.

---
## EventBridge
EventBridge routes events to different services based on rules.

---
## SNS (Simple Notification Service)
SNS distributes events to multiple subscribers.

---
## Key Concept
Event = push-based execution model, often implemented using APIs such as webhooks.
Event-driven architecture enables loosely coupled systems where components do not need to directly call each other.

---
## Difference from API
- API: request-driven
- Event: event-driven

---

## Summary

Event-driven architecture enables loosely coupled systems by reacting to events, improving scalability and flexibility.
