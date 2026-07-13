# Day 16: Switching, VLANs & Inter-VLAN Routing

> Understanding Switching, Virtual LANs (VLANs), Layer 2 and Layer 3 switching, Inter-VLAN Routing, and network segmentation.

---

# 🎯 Learning Objectives

- Understand Network Switching.
- Learn Layer 2 and Layer 3 Switching.
- Understand VLANs.
- Learn Inter-VLAN Routing.
- Explore VLAN Benefits.
- Prepare for networking interviews.

---

# 📖 Introduction

Large organizations divide networks into smaller logical groups to improve security, performance, and management.

This is achieved using **Switches** and **Virtual LANs (VLANs)**.

---

# 🔀 What is a Switch?

A Switch is a Layer 2 networking device that connects devices within the same Local Area Network (LAN).

Functions:

- Forward Frames
- Learn MAC Addresses
- Reduce Network Collisions
- Improve Performance

---

# Layer 2 Switch

Uses:

- MAC Addresses

Operates at:

- Data Link Layer

Cannot perform routing.

---

# Layer 3 Switch

Uses:

- MAC Addresses
- IP Addresses

Can:

- Perform Routing
- Route between VLANs

---

# What is a VLAN?

A VLAN (Virtual Local Area Network) logically separates devices into different broadcast domains, even if they are connected to the same physical switch.

Example:

```
Switch

↓

VLAN 10 → HR

VLAN 20 → Finance

VLAN 30 → IT
```

Devices in different VLANs are isolated from each other unless routing is configured.

---

# Why VLANs?

Benefits:

- Improved Security
- Reduced Broadcast Traffic
- Better Network Organization
- Easier Management

---

# Access Port

An Access Port belongs to a single VLAN.

Used for:

- PCs
- Printers
- IP Phones

---

# Trunk Port

A Trunk Port carries traffic for multiple VLANs between switches.

Common protocol:

- IEEE 802.1Q

---

# Inter-VLAN Routing

Devices in different VLANs cannot communicate directly.

A Router or Layer 3 Switch is required.

Example:

```
VLAN 10

↓

Layer 3 Switch

↓

VLAN 20
```

---

# Broadcast Domain

A Broadcast Domain is the group of devices that receive broadcast traffic.

Each VLAN creates a separate broadcast domain.

---

# Collision Domain

Each switch port forms its own collision domain, reducing network congestion.

---

# VLAN Security

Best Practices:

- Disable unused ports.
- Use separate VLANs for departments.
- Restrict trunk ports.
- Apply Access Control Lists (ACLs).

---

# VLANs in Cloud Computing

Cloud platforms provide similar concepts.

AWS

- VPC
- Subnets
- Security Groups

Azure

- Virtual Networks (VNets)

Google Cloud

- VPC Networks

---

# 🌍 Real-Life Example

A company separates departments using VLANs.

- HR → VLAN 10
- Finance → VLAN 20
- IT → VLAN 30

Employees can only communicate within their own VLAN unless Inter-VLAN Routing is configured.

---

# 💡 Best Practices

- Use VLANs for network segmentation.
- Restrict unnecessary trunk ports.
- Monitor switch configurations.
- Secure Layer 2 protocols.
- Use Layer 3 switches for large networks.

---

# 📌 Key Takeaways

- Switches connect devices within a LAN.
- VLANs create logical network separation.
- Layer 2 switches use MAC addresses.
- Layer 3 switches support routing.
- Inter-VLAN Routing allows communication between VLANs.
- VLANs improve security and performance.

---

# ❓ Interview Questions

### 1. What is a VLAN?

A VLAN is a logical network that separates devices into different broadcast domains.

---

### 2. What is the difference between a Layer 2 and Layer 3 switch?

A Layer 2 switch forwards frames using MAC addresses, while a Layer 3 switch can also route packets using IP addresses.

---

### 3. What is an Access Port?

A switch port assigned to a single VLAN.

---

### 4. What is a Trunk Port?

A port that carries traffic for multiple VLANs between switches.

---

### 5. Why is Inter-VLAN Routing required?

To allow communication between devices located in different VLANs.

---

# 📝 Summary

Today I learned about Network Switching, Layer 2 and Layer 3 switches, VLANs, Access and Trunk Ports, Broadcast Domains, Collision Domains, and Inter-VLAN Routing. VLANs improve network security, performance, and scalability by logically segmenting networks, while Layer 3 devices enable communication between different VLANs.
