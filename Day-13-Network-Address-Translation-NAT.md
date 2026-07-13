# Day 13: Network Address Translation (NAT)

> Understanding Network Address Translation (NAT), why it is used, different NAT types, advantages, disadvantages, and its role in enterprise and cloud networking.

---

# 🎯 Learning Objectives

- Understand NAT.
- Learn why NAT is required.
- Explore different NAT types.
- Understand Private and Public IP addresses.
- Learn NAT in Cloud Computing.
- Prepare for networking interviews.

---

# 📖 Introduction

Every device connected to the Internet requires a unique Public IP address.

Since Public IPv4 addresses are limited, organizations use Private IP addresses internally.

Network Address Translation (NAT) allows multiple private devices to share one or more public IP addresses.

---

# 🌐 What is NAT?

Network Address Translation (NAT) is a networking technique that translates private IP addresses into public IP addresses before traffic reaches the Internet.

Example:

```
192.168.1.10

↓

NAT Router

↓

49.205.125.20
```

---

# Why NAT?

Without NAT:

- Every device would require a public IP.
- IPv4 addresses would be exhausted quickly.

With NAT:

- Multiple devices share one public IP.
- Better security.
- Lower ISP costs.

---

# Private IP Address Ranges

| Class | Range |
|--------|----------------|
| A | 10.0.0.0 – 10.255.255.255 |
| B | 172.16.0.0 – 172.31.255.255 |
| C | 192.168.0.0 – 192.168.255.255 |

These addresses cannot be accessed directly from the Internet.

---

# Public IP Address

A Public IP address is globally unique and assigned by an ISP.

Example:

```
49.205.125.20
```

---

# Types of NAT

## Static NAT

One Private IP maps to one Public IP.

Example:

```
192.168.1.10

↓

49.205.125.20
```

Used for servers.

---

## Dynamic NAT

Private IP addresses are mapped dynamically from a pool of Public IP addresses.

---

## PAT (NAT Overload)

Multiple private devices share a single Public IP using different port numbers.

Most home routers use PAT.

---

# NAT Translation Process

```
Laptop

↓

192.168.1.5

↓

Router (NAT)

↓

49.205.125.20

↓

Internet
```

---

# Advantages

- Conserves Public IP addresses.
- Improves security.
- Supports private networks.
- Easy Internet access.

---

# Disadvantages

- Adds processing overhead.
- Can complicate troubleshooting.
- Some applications require additional configuration.

---

# NAT in Cloud Computing

AWS

- NAT Gateway
- NAT Instance

Azure

- NAT Gateway

Google Cloud

- Cloud NAT

These services allow private virtual machines to access the Internet securely.

---

# 🌍 Real-Life Example

An office has 200 computers.

All computers use private IP addresses.

The office router translates all outgoing traffic to one public IP before connecting to the Internet.

---

# 💡 Best Practices

- Use NAT Gateways in cloud environments.
- Restrict inbound traffic.
- Monitor NAT logs.
- Keep firewall rules updated.

---

# 📌 Key Takeaways

- NAT translates private IPs into public IPs.
- NAT conserves IPv4 addresses.
- Static NAT is one-to-one.
- Dynamic NAT uses a public IP pool.
- PAT allows many devices to share one public IP.

---

# ❓ Interview Questions

### 1. What is NAT?

NAT translates private IP addresses into public IP addresses.

---

### 2. Why is NAT required?

To conserve public IPv4 addresses and allow Internet access.

---

### 3. Name three NAT types.

- Static NAT
- Dynamic NAT
- PAT

---

### 4. Which NAT type is commonly used in homes?

PAT.

---

### 5. Which AWS service provides NAT functionality?

AWS NAT Gateway.

---

# 📝 Summary

Today I learned about Network Address Translation (NAT), its purpose, different NAT types, private and public IP addresses, and how NAT is implemented in cloud environments. NAT is a core networking concept that enables efficient Internet connectivity while conserving IPv4 addresses.
