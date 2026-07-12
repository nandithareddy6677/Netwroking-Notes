# Chapter 7: Routing and Switching

> Understanding how routers and switches forward data across networks, make forwarding decisions, and enable communication between devices.

---

# 🎯 Learning Objectives

- Understand Routing.
- Understand Switching.
- Learn the difference between Routers and Switches.
- Understand Routing Tables.
- Learn Static and Dynamic Routing.
- Understand MAC Addresses.
- Learn Broadcast and Collision Domains.
- Learn VLAN Basics.
- Prepare for networking interviews.

---

# 📖 Introduction

Whenever we access websites, send emails, stream videos, or communicate over the Internet, data must travel from one device to another.

To make this communication possible, networks use two important technologies:

- Switching
- Routing

Switching enables communication inside a Local Area Network (LAN), while Routing allows communication between different networks.

Together, routers and switches form the backbone of modern computer networks.

---

# 🔀 What is Switching?

Switching is the process of forwarding data between devices within the same Local Area Network (LAN).

A Switch receives data and forwards it only to the intended destination device using its MAC Address.

Switches operate at:

**Layer 2 (Data Link Layer)**

of the OSI Model.

---

# What is a Switch?

A Switch is a networking device that connects multiple devices within the same network.

Examples:

- Computers
- Printers
- Servers
- Access Points

Unlike a Hub, a Switch sends data only to the intended device instead of broadcasting it to all devices.

---

# MAC Address

A MAC (Media Access Control) Address is a unique physical address assigned to every Network Interface Card (NIC).

Example:

```
00:1A:2B:3C:4D:5E
```

Characteristics:

- Unique for every network device.
- Assigned by the manufacturer.
- Used for communication within the same LAN.

---

# MAC Address Table

A Switch maintains a MAC Address Table.

The table stores:

- MAC Address
- Port Number

Example:

| MAC Address | Port |
|-------------|------|
| 00:11:22:33:44:55 | Port 1 |
| AA:BB:CC:DD:EE:FF | Port 2 |

This allows the Switch to forward data efficiently.

---

# What is Routing?

Routing is the process of forwarding data between different networks.

Routers examine the destination IP Address and determine the best path for the packet.

Routers operate at:

**Layer 3 (Network Layer)**

of the OSI Model.

---

# What is a Router?

A Router is a networking device that connects multiple networks.

Responsibilities:

- Forward packets
- Select best path
- Connect LAN to Internet
- Route traffic efficiently

Example:

Your home Wi-Fi router connects your local network to your Internet Service Provider (ISP).

---

# IP Address vs MAC Address

| IP Address | MAC Address |
|------------|-------------|
| Logical Address | Physical Address |
| Layer 3 | Layer 2 |
| Used by Routers | Used by Switches |
| Can Change | Usually Permanent |

---

# Routing Table

A Routing Table contains information that helps routers decide where to forward packets.

A Routing Table includes:

- Destination Network
- Next Hop
- Interface
- Metric

The router checks this table before forwarding each packet.

---

# Static Routing

Static Routing means routes are manually configured by the network administrator.

Advantages:

- Simple
- Predictable
- Secure

Disadvantages:

- Manual updates required
- Not suitable for large networks

Example:

```text
Network A → Router → Network B
```

The administrator manually defines the route.

---

# Dynamic Routing

Dynamic Routing automatically learns and updates routes.

Advantages:

- Automatic updates
- Better scalability
- Handles network changes

Common Dynamic Routing Protocols:

- RIP
- OSPF
- EIGRP
- BGP

---

# Broadcast Domain

A Broadcast Domain is a group of devices that receive broadcast messages.

Routers separate Broadcast Domains.

Each router interface creates a new Broadcast Domain.

---

# Collision Domain

A Collision Domain is a network segment where data collisions can occur.

Modern switches create a separate Collision Domain for each port, greatly reducing collisions.

---

# VLAN (Virtual Local Area Network)

A VLAN logically divides one physical network into multiple separate networks.

Benefits:

- Improved Security
- Better Performance
- Easier Network Management
- Reduced Broadcast Traffic

Example:

One office switch can have:

- VLAN 10 → HR
- VLAN 20 → Finance
- VLAN 30 → IT

Even though all devices are connected to the same switch, they behave as if they are on separate networks.

---

# Router vs Switch

| Router | Switch |
|---------|---------|
| Layer 3 Device | Layer 2 Device |
| Uses IP Address | Uses MAC Address |
| Connects Different Networks | Connects Devices in Same Network |
| Maintains Routing Table | Maintains MAC Address Table |

---

# 🌍 Real-Life Example

A company has three departments:

- HR
- Finance
- IT

Each department is assigned a separate VLAN.

Employees communicate within their own VLAN using switches.

When data needs to travel between departments or to the Internet, routers forward the packets to the correct destination.

This improves both performance and security.

---

# 💡 Best Practices

- Use switches for Local Area Networks.
- Use routers to connect different networks.
- Configure VLANs to improve security.
- Keep routing tables updated.
- Use Dynamic Routing for large organizations.
- Monitor network traffic regularly.

---

# 📌 Key Takeaways

- Switching connects devices within the same network.
- Routing connects different networks.
- Switches use MAC Addresses.
- Routers use IP Addresses.
- VLANs improve security and reduce broadcast traffic.
- Static Routing is manually configured.
- Dynamic Routing automatically updates routes.

---

# ❓ Interview Questions

### 1. What is Routing?

Routing is the process of forwarding data between different networks using IP addresses.

---

### 2. What is Switching?

Switching is the process of forwarding data between devices within the same network using MAC addresses.

---

### 3. Which OSI Layer does a Router operate on?

Layer 3 (Network Layer).

---

### 4. Which OSI Layer does a Switch operate on?

Layer 2 (Data Link Layer).

---

### 5. What is a Routing Table?

A Routing Table stores information that helps routers determine the best path for forwarding packets.

---

### 6. What is the difference between Static and Dynamic Routing?

Static Routing is configured manually, while Dynamic Routing automatically learns and updates routes using routing protocols.

---

### 7. What is a VLAN?

A VLAN (Virtual Local Area Network) logically divides a physical network into multiple isolated networks to improve security and performance.

---

### 8. What is the difference between an IP Address and a MAC Address?

An IP Address is a logical address used for routing between networks, while a MAC Address is a physical address used for communication within the same local network.

---

# 📝 Summary

Today I learned about Routing and Switching, two fundamental networking technologies. I explored how switches use MAC addresses to forward data within a Local Area Network and how routers use IP addresses to connect different networks. I also learned about routing tables, static and dynamic routing, broadcast domains, collision domains, and VLANs, all of which are essential concepts in networking, cloud computing, and cybersecurity.
