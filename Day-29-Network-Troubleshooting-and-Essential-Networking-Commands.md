# Day 29: Network Troubleshooting & Essential Networking Commands

> Understanding network troubleshooting methodologies, diagnostic tools, and essential networking commands used by system administrators, network engineers, cloud engineers, and cybersecurity professionals.

---

# 🎯 Learning Objectives

- Understand Network Troubleshooting.
- Learn OSI Troubleshooting.
- Explore Networking Commands.
- Understand Connectivity Testing.
- Prepare for networking interviews.

---

# 📖 Introduction

Even well-designed networks experience problems.

A structured troubleshooting approach helps engineers identify and resolve issues efficiently.

---

# What is Network Troubleshooting?

Network Troubleshooting is the systematic process of identifying, diagnosing, and resolving network issues.

---

# Common Network Problems

- No Internet Connection
- Slow Network
- DNS Failure
- Packet Loss
- High Latency
- Routing Issues
- Firewall Blocking

---

# Troubleshooting Methodology

```
Identify Problem

↓

Collect Information

↓

Analyze

↓

Test Solution

↓

Verify

↓

Document
```

---

# OSI Layer Troubleshooting

Layer 1

- Cable
- Power
- Hardware

Layer 2

- MAC Address
- Switch
- VLAN

Layer 3

- IP Address
- Routing
- Gateway

Layer 4

- TCP
- UDP
- Ports

Layer 7

- DNS
- HTTP
- Applications

---

# Essential Networking Commands

## ping

Tests connectivity.

```
ping google.com
```

---

## traceroute / tracert

Displays the network path.

---

## ipconfig (Windows)

Displays IP configuration.

---

## ifconfig (Linux)

Displays network interfaces.

---

## ip addr (Linux)

Shows IP address configuration.

---

## nslookup

Queries DNS records.

---

## dig

Advanced DNS lookup.

---

## netstat

Displays network connections.

---

## ss

Modern replacement for netstat in Linux.

---

## arp

Displays ARP table.

---

## route

Displays routing table.

---

## hostname

Displays computer hostname.

---

## curl

Tests web servers and APIs.

---

# Packet Loss

Occurs when packets fail to reach their destination.

Causes:

- Congestion
- Hardware Failure
- Bad Links

---

# Latency

Time required for data to travel between devices.

Lower latency means better performance.

---

# Troubleshooting Best Practices

- Check physical connections.
- Verify IP settings.
- Test DNS.
- Review firewall rules.
- Analyze routing.
- Monitor logs.

---

# 🌍 Real-World Example

A user cannot access a website.

The engineer:

- Uses ping.
- Runs traceroute.
- Checks DNS using nslookup.
- Reviews firewall rules.

The issue is resolved by correcting DNS settings.

---

# 📌 Key Takeaways

- Troubleshooting follows a structured process.
- OSI layers simplify diagnosis.
- Networking commands identify problems quickly.
- Documentation is important.

---

# ❓ Interview Questions

### 1. What command checks connectivity?

ping

### 2. What command displays routing paths?

traceroute

### 3. What command checks DNS?

nslookup

### 4. Which command displays IP configuration on Windows?

ipconfig

### 5. Why document troubleshooting?

To improve future incident resolution.

---

# 📝 Summary

Today I learned about Network Troubleshooting methodologies, OSI-based troubleshooting, packet loss, latency, and essential networking commands such as ping, traceroute, nslookup, ipconfig, ifconfig, netstat, and curl.
