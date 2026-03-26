# API Learning Notes

This repository contains my learning notes and hands-on exercises on APIs, including REST, authentication, and integration patterns.

## Key Topics
- REST API fundamentals
- Request/Response structure (JSON)
- Authentication (API Key, OAuth basics)
- Integration concepts

## Purpose
To deepen my understanding of API-driven ecosystems and platform integrations, which are core to my work in partnerships and ecosystem development.

# Step 1 - API Basics

## What I did
- Executed GET requests using Postman
- Retrieved JSON data from a public API
- Compared different endpoint structures

## Key Learnings
- API enables structured communication between systems via request-response model
- JSON provides a lightweight and standardized data format
- Path parameters identify specific resources
- Query parameters allow flexible data filtering

## Why it matters
Understanding API communication is fundamental for designing scalable and standardized integrations between systems.

## What is API
API is a standardized interface that enables communication between systems through request-response interactions, where data is exchanged in structured formats such as JSON.

## What is REST API
REST API is an architectural style that uses standard HTTP methods to operate on resources in a stateless and structured way.

## Why we use REST API
REST APIs are widely used because they are simple, scalable, and standardized.
- They use standard HTTP methods such as GET, POST, PUT, and DELETE
- They follow a resource-based structure, making them easy to understand and extend

- # Step 2 - CRUD with API

## What I did
- Sent POST request to create data
- Sent PUT request to update data
- Sent DELETE request to remove data

## Key Learnings
- POST creates new resources
- PUT replaces existing resources
- DELETE removes resources
- These operations correspond to CRUD (Create, Read, Update, Delete)

## Why it matters
CRUD operations are fundamental to how systems manage and manipulate data through APIs.

## Additional Learnings
- PUT replaces the entire resource, while PATCH updates only specific fields
- Understanding the difference is important to avoid unintended data overwrites
