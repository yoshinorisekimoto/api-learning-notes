# Step14: Region/Availability Zone

## What is Region and AZ?
AWS infrastructure is divided into:

- Region: geographic area (e.g., Tokyo)
- Availability Zone (AZ): isolated data centers within a region

A Region consists of multiple Availability Zones.

---
## Problem: Single Point of Failure
If all systems are deployed in one location, a failure (e.g., power outage) can bring down the entire system.

---
## Solution: Redundancy
By distributing resources across multiple AZs, systems can continue running even if one AZ fails.

---
## Key Concept
- Single Point of Failure = one failure stops everything
- Redundancy = multiple instances ensure availability

---
## Summary
Using multiple Availability Zones improves system reliability and ensures high availability.
