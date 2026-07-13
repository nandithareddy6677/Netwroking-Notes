# Day 12: Dynamic Host Configuration Protocol (DHCP)

> Understanding DHCP, automatic IP address assignment, DHCP architecture, lease management, and how devices obtain network configuration automatically.

---

# 🎯 Learning Objectives

- Understand DHCP.
- Learn DHCP Components.
- Explore DHCP Lease Process.
- Understand DHCP Messages.
- Learn DHCP Security.
- Prepare for networking interviews.

---

# 📖 Introduction

Every device connected to a network requires:

- IP Address
- Subnet Mask
- Default Gateway
- DNS Server

Assigning these manually is difficult.

DHCP automatically assigns these settings to devices.

---

# 📡 What is DHCP?

DHCP (Dynamic Host Configuration Protocol) automatically assigns network configuration to devices.

Without DHCP, administrators would manually configure every device.

---

# Why DHCP?

Benefits:

- Automatic IP Assignment
- Reduced Errors
- Centralized Management
- Faster Device Setup

---

# DHCP Components

- DHCP Client
- DHCP Server
- IP Address Pool
- Lease Database

---

# DHCP Lease

An IP address is assigned for a limited period called a lease.

When the lease expires, the client requests renewal.

---

# DHCP DORA Process

```
Client

↓

Discover

↓

Offer

↓

Request

↓

Acknowledgement
```

---

# Discover

The client broadcasts a request asking for an IP address.

---

# Offer

The DHCP server offers an available IP address.

---

# Request

The client requests the offered address.

---

# Acknowledgement (ACK)

The server confirms the lease.

The client can now use the assigned IP.

---

# Information Provided by DHCP

- IP Address
- Subnet Mask
- Default Gateway
- DNS Server
- Lease Time

---

# DHCP Advantages

- Automatic Configuration
- Easy Administration
- Efficient IP Management
- Reduces Configuration Errors

---

# DHCP Disadvantages

- Single Point of Failure
- Rogue DHCP Servers
- Lease Exhaustion Attacks

---

# DHCP Security

Protection methods:

- DHCP Snooping
- Port Security
- Trusted Switch Ports
- Network Monitoring

---

# DHCP in Cloud Computing

Cloud platforms automatically assign private IP addresses.

Examples:

AWS EC2

Azure Virtual Machines

Google Compute Engine

---

# 🌍 Real-Life Example

You connect your laptop to a Wi-Fi network.

The router's DHCP server automatically assigns:

- IP Address
- Gateway
- DNS Server

You can immediately access the Internet without manual configuration.

---

# 💡 Best Practices

- Use DHCP Reservations for important servers.
- Enable DHCP Snooping.
- Monitor DHCP logs.
- Secure DHCP servers.
- Backup DHCP configurations.

---

# 📌 Key Takeaways

- DHCP automatically assigns IP addresses.
- DORA is the DHCP communication process.
- DHCP reduces manual configuration.
- Lease time determines how long an IP is assigned.
- DHCP is widely used in enterprise and cloud networks.

---

# ❓ Interview Questions

### 1. What is DHCP?

DHCP automatically assigns IP addresses and network settings.

---

### 2. What does DORA stand for?

Discover, Offer, Request, Acknowledgement.

---

### 3. What information does DHCP provide?

- IP Address
- Subnet Mask
- Gateway
- DNS Server

---

### 4. What is DHCP Lease?

The period during which a client can use an assigned IP address.

---

### 5. What is DHCP Snooping?

A security feature that prevents unauthorized DHCP servers from assigning IP addresses.

---

# 📝 Summary

Today I learned about DHCP and how it automatically assigns IP addresses and other network settings. I explored the DORA process, DHCP leases, DHCP security, and how cloud platforms use DHCP to configure virtual machines automatically. DHCP simplifies network administration and is a fundamental protocol in enterprise and cloud networking.
