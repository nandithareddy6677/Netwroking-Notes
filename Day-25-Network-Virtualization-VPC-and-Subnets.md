# Day 25: Network Virtualization, VPC & Subnets

> Understanding Network Virtualization, Virtual Private Clouds (VPCs), Virtual Networks, Subnets, Route Tables, and modern cloud networking architecture.

---

# 🎯 Learning Objectives

- Understand Network Virtualization.
- Learn Virtual Private Cloud (VPC).
- Explore Subnets.
- Understand Route Tables.
- Learn Cloud Networking.
- Prepare for cloud interviews.

---

# 📖 Introduction

Cloud providers allow organizations to create isolated virtual networks without purchasing physical networking hardware.

This concept is called Network Virtualization.

---

# 🌐 What is Network Virtualization?

Network Virtualization creates logical networks using software instead of physical hardware.

Benefits:

- Flexibility
- Scalability
- Isolation
- Easy Management

---

# What is a VPC?

A Virtual Private Cloud (VPC) is a logically isolated virtual network within a public cloud.

It allows organizations to securely deploy cloud resources.

---

# Components of a VPC

- Subnets
- Route Tables
- Internet Gateway
- NAT Gateway
- Security Groups
- Network ACLs

---

# Public Subnet

Resources inside a Public Subnet can communicate with the Internet.

Examples:

- Web Servers
- Load Balancers

---

# Private Subnet

Resources inside a Private Subnet cannot be accessed directly from the Internet.

Examples:

- Databases
- Internal Applications

---

# Route Tables

Route Tables determine where network traffic should be forwarded.

Example:

```
Destination

↓

Next Hop

↓

Internet Gateway
```

---

# Internet Gateway

Allows resources in a Public Subnet to access the Internet.

---

# NAT Gateway

Allows Private Subnet resources to access the Internet without exposing them to inbound traffic.

---

# Cloud Networking

AWS

- VPC
- Subnets
- Route Tables

Azure

- Virtual Network (VNet)

Google Cloud

- VPC Network

---

# Real-World Example

A company hosts:

- Web Server → Public Subnet
- Database → Private Subnet

Users can access the website, but the database remains protected from direct Internet access.

---

# 💡 Best Practices

- Place databases in Private Subnets.
- Restrict Internet access.
- Use Security Groups.
- Use NAT Gateways.
- Review Route Tables regularly.

---

# 📌 Key Takeaways

- Network Virtualization creates logical networks.
- VPC provides isolated cloud networking.
- Public and Private Subnets improve security.
- Route Tables control network traffic.
- NAT Gateways protect private resources.

---

# ❓ Interview Questions

### 1. What is a VPC?

A logically isolated virtual network within a cloud environment.

### 2. Difference between Public and Private Subnets?

Public Subnets have Internet access, while Private Subnets do not allow direct inbound Internet access.

### 3. What is a NAT Gateway?

A service that enables outbound Internet access for resources in private subnets without exposing them to direct inbound connections.

---

# 📝 Summary

Today I learned about Network Virtualization, Virtual Private Clouds (VPCs), Public and Private Subnets, Route Tables, Internet Gateways, and NAT Gateways. These are core cloud networking concepts used by AWS, Azure, and Google Cloud to build secure, scalable, and isolated cloud environments.
