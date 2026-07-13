# Day 15: Routing & Routing Protocols

> Understanding Routing, Routers, Static and Dynamic Routing, Routing Protocols (RIP, OSPF, BGP), and their importance in enterprise and cloud networking.

---

# 🎯 Learning Objectives

- Understand Routing.
- Learn how Routers work.
- Explore Static and Dynamic Routing.
- Learn Routing Protocols.
- Understand RIP, OSPF, and BGP.
- Prepare for networking and cloud interviews.

---

# 📖 Introduction

Modern networks consist of multiple interconnected devices and networks.

When data travels from one network to another, routers determine the best path for forwarding packets.

This process is known as **Routing**.

---

# 🌐 What is Routing?

Routing is the process of selecting the best path for data packets to travel from a source network to a destination network.

Example:

```
Computer

↓

Router

↓

Internet

↓

Destination Server
```

---

# What is a Router?

A Router is a Layer 3 networking device that connects different networks and forwards packets using IP addresses.

Functions:

- Connect Networks
- Forward Packets
- Maintain Routing Tables
- Select Best Path

---

# Routing Table

A Routing Table stores information about:

- Destination Network
- Next Hop
- Interface
- Route Metric

Routers use this table to decide where packets should go.

---

# Types of Routing

## Static Routing

Routes are manually configured.

Advantages:

- Simple
- Secure
- Predictable

Disadvantages:

- Not scalable
- Requires manual updates

---

## Dynamic Routing

Routers automatically learn routes using routing protocols.

Advantages:

- Automatic updates
- Scalable
- Faster adaptation

Disadvantages:

- More complex
- Uses additional resources

---

# Routing Protocols

Common routing protocols:

- RIP
- OSPF
- EIGRP
- BGP

---

# RIP (Routing Information Protocol)

Characteristics:

- Distance Vector Protocol
- Uses Hop Count
- Maximum 15 Hops
- Easy to configure

Suitable for:

- Small Networks

---

# OSPF (Open Shortest Path First)

Characteristics:

- Link-State Protocol
- Uses Cost Metric
- Fast Convergence
- Highly Scalable

Suitable for:

- Enterprise Networks

---

# BGP (Border Gateway Protocol)

Characteristics:

- Exterior Gateway Protocol
- Connects different Autonomous Systems (AS)
- Used by Internet Service Providers

Suitable for:

- Internet Routing
- Large Organizations
- Cloud Providers

---

# Interior vs Exterior Routing

Interior Routing:

- Within one organization

Examples:

- RIP
- OSPF
- EIGRP

Exterior Routing:

- Between organizations

Example:

- BGP

---

# Routing Metrics

Routing protocols use metrics to select the best path.

Examples:

- Hop Count
- Cost
- Bandwidth
- Delay

---

# Routing in Cloud Computing

Cloud providers use routing extensively.

Examples:

AWS

- Route Tables
- Transit Gateway
- Virtual Private Gateway

Azure

- User Defined Routes (UDR)

Google Cloud

- Cloud Router

---

# 🌍 Real-Life Example

A company has offices in Hyderabad, Bengaluru, and Mumbai.

Routers exchange routing information using OSPF.

Traffic automatically follows the fastest available path between offices.

---

# 💡 Best Practices

- Use Static Routing for small networks.
- Use OSPF for enterprise networks.
- Use BGP for Internet routing.
- Regularly monitor routing tables.
- Secure routing protocols.

---

# 📌 Key Takeaways

- Routing forwards packets between networks.
- Routers operate at Layer 3.
- Static routing is manually configured.
- Dynamic routing uses routing protocols.
- BGP powers Internet routing.
- OSPF is common in enterprises.

---

# ❓ Interview Questions

### 1. What is Routing?

Routing is the process of selecting the best path for network traffic.

---

### 2. What is the difference between Static and Dynamic Routing?

Static Routing is manually configured, while Dynamic Routing automatically learns routes using routing protocols.

---

### 3. Which protocol uses Hop Count?

RIP.

---

### 4. Which routing protocol is used on the Internet?

BGP.

---

### 5. Which routing protocol is commonly used in enterprise networks?

OSPF.

---

# 📝 Summary

Today I learned about Routing, Routers, Static and Dynamic Routing, Routing Tables, and major routing protocols including RIP, OSPF, and BGP. Routing is a fundamental networking concept that enables efficient communication between different networks and forms the backbone of cloud and Internet infrastructure.
