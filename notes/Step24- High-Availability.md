# Step24: High Availability (HA)

## What is High Availability?
High availability means designing systems that continue to operate without interruption.

---
## Single Point of Failure
A single point of failure is a component that can bring down the entire system if it fails.

---
## Multi-AZ
Deploying resources across multiple Availability Zones improves reliability.
If one AZ fails, another AZ can continue serving traffic.

---
## Failover
Failover is the automatic switching to a backup system when a failure occurs.

---
## Key Concept
High availability = system continues running despite failures

---
## Relationship to Scaling
- Scaling: handles increased load
- Availability: handles failures

---
## Summary
High availability is achieved by distributing resources across multiple locations and enabling automatic failover to avoid downtime.
