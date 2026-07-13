# Day 19: Load Balancing & High Availability

> Understanding Load Balancing, High Availability, Failover, Scalability, and how cloud providers distribute traffic across multiple servers.

---

# 🎯 Learning Objectives

- Understand Load Balancing.
- Learn High Availability.
- Explore Scalability.
- Understand Failover.
- Learn Cloud Load Balancers.
- Prepare for networking and cloud interviews.

---

# 📖 Introduction

Large websites receive millions of users every day.

A single server cannot handle all requests.

Load Balancers distribute incoming traffic across multiple servers to improve performance and availability.

---

# ⚖️ What is Load Balancing?

Load Balancing distributes incoming traffic across multiple servers.

Benefits:

- Better Performance
- Higher Availability
- Improved Reliability
- Fault Tolerance

---

# Types of Load Balancers

- Hardware Load Balancer
- Software Load Balancer
- Cloud Load Balancer

---

# Load Balancing Algorithms

- Round Robin
- Least Connections
- Least Response Time
- Weighted Round Robin
- IP Hash

---

# High Availability (HA)

High Availability ensures services remain available even if one server fails.

Techniques:

- Redundant Servers
- Multiple Data Centers
- Automatic Failover

---

# Failover

If one server becomes unavailable:

```
Server A (Failed)

↓

Load Balancer

↓

Server B (Active)
```

Users continue accessing the application without interruption.

---

# Scalability

## Vertical Scaling

Increase CPU, RAM, or storage of an existing server.

---

## Horizontal Scaling

Add more servers behind a Load Balancer.

Preferred in cloud computing.

---

# Cloud Load Balancers

AWS

- Application Load Balancer (ALB)
- Network Load Balancer (NLB)
- Gateway Load Balancer (GWLB)

Azure

- Azure Load Balancer
- Azure Application Gateway

Google Cloud

- Cloud Load Balancing

---

# Real-World Example

An e-commerce website experiences heavy traffic during a sale.

The Load Balancer distributes customer requests across multiple web servers, ensuring fast response times and preventing server overload.

---

# 💡 Best Practices

- Use Health Checks.
- Enable Auto Scaling.
- Deploy servers across multiple Availability Zones.
- Monitor Load Balancer metrics.
- Remove unhealthy instances automatically.

---

# 📌 Key Takeaways

- Load Balancing distributes traffic.
- High Availability minimizes downtime.
- Horizontal Scaling is preferred in cloud environments.
- Failover improves reliability.
- Cloud providers offer managed Load Balancers.

---

# ❓ Interview Questions

### 1. What is Load Balancing?

Distributing incoming network traffic across multiple servers.

### 2. What is High Availability?

Ensuring services remain operational even during failures.

### 3. Difference between Vertical and Horizontal Scaling?

Vertical scaling upgrades one server, while horizontal scaling adds more servers.

### 4. Name two AWS Load Balancers.

- Application Load Balancer (ALB)
- Network Load Balancer (NLB)

### 5. Why are Health Checks important?

They ensure traffic is sent only to healthy servers.

---

# 📝 Summary

Today I learned about Load Balancing, High Availability, Failover, Scalability, and cloud load balancing services. These concepts help organizations build reliable, scalable, and fault-tolerant applications capable of serving millions of users efficiently.
