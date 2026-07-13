# Day 14: Port Address Translation (PAT) & Port Forwarding

> Understanding Port Address Translation (PAT), Port Forwarding, network ports, and how these technologies enable secure communication between private networks and the Internet.

---

# 🎯 Learning Objectives

- Understand PAT.
- Learn Port Numbers.
- Explore Port Forwarding.
- Understand Common Network Ports.
- Learn Cloud Networking Concepts.
- Prepare for networking interviews.

---

# 📖 Introduction

A single public IP address often serves many devices in a network.

PAT makes this possible by distinguishing network connections using port numbers.

Port Forwarding allows external users to access specific services hosted inside a private network.

---

# 🔢 What is a Port?

A Port is a logical communication endpoint used by applications.

Example:

```
IP Address

↓

Port Number

↓

Application
```

Example:

```
192.168.1.20:443
```

---

# Common Port Numbers

| Port | Protocol | Service |
|------|----------|----------|
| 20/21 | FTP | File Transfer |
| 22 | SSH | Secure Shell |
| 23 | Telnet | Remote Login |
| 25 | SMTP | Email |
| 53 | DNS | Domain Name System |
| 80 | HTTP | Web Traffic |
| 110 | POP3 | Email Retrieval |
| 143 | IMAP | Email Access |
| 443 | HTTPS | Secure Web |
| 3389 | RDP | Remote Desktop |

---

# What is PAT?

Port Address Translation (PAT) allows multiple private devices to share one Public IP address using different port numbers.

Example:

```
Laptop A

192.168.1.2

↓

Public IP

49.205.125.20:5001

----------------

Laptop B

192.168.1.3

↓

Public IP

49.205.125.20:5002
```

The router keeps track of each connection using port numbers.

---

# PAT Advantages

- Saves Public IP addresses.
- Supports many users.
- Automatically manages connections.
- Used in almost every home router.

---

# What is Port Forwarding?

Port Forwarding forwards traffic arriving on a specific public port to a private device inside the network.

Example:

```
Internet

↓

Public IP

↓

Port 80

↓

Web Server

192.168.1.100
```

---

# Why Port Forwarding?

Used to access:

- Web Servers
- CCTV Cameras
- Game Servers
- FTP Servers
- Remote Desktop

---

# PAT vs Port Forwarding

| PAT | Port Forwarding |
|------|----------------|
| Shares Public IP | Exposes Internal Service |
| Outbound Connections | Inbound Connections |
| Automatic | Manual Configuration |

---

# Security Risks

Incorrect Port Forwarding can expose:

- Servers
- Cameras
- Remote Desktop
- Databases

Attackers frequently scan open ports.

---

# Protection Methods

- Enable Firewalls.
- Close unused ports.
- Restrict source IP addresses.
- Use VPN.
- Enable MFA.
- Monitor network traffic.

---

# PAT in Cloud Computing

Cloud providers use Security Groups and Firewalls instead of traditional home router port forwarding.

Examples:

AWS

- Security Groups
- Network ACLs
- Elastic IP

Azure

- Network Security Groups

Google Cloud

- Firewall Rules

---

# 🌍 Real-Life Example

A company hosts a web server inside its office.

The router forwards incoming traffic on Port 443 to the internal server.

Users can securely access the website using HTTPS.

---

# 💡 Best Practices

- Open only necessary ports.
- Disable unused services.
- Monitor open ports.
- Use secure protocols such as SSH instead of Telnet.
- Regularly review firewall rules.

---

# 📌 Key Takeaways

- Ports identify network services.
- PAT allows multiple devices to share one Public IP.
- Port Forwarding provides external access to internal services.
- Open ports should be carefully managed.
- Cloud platforms use Security Groups instead of traditional port forwarding.

---

# ❓ Interview Questions

### 1. What is PAT?

PAT allows multiple devices to share one Public IP address using different port numbers.

---

### 2. What is Port Forwarding?

Port Forwarding redirects incoming traffic to a specific internal device.

---

### 3. Which port is used for HTTPS?

443.

---

### 4. Which port is used for SSH?

22.

---

### 5. Why should unnecessary ports remain closed?

To reduce the attack surface and improve network security.

---

# 📝 Summary

Today I learned about Port Address Translation (PAT), Port Forwarding, network ports, common protocols, and cloud networking security. PAT enables efficient use of public IP addresses, while Port Forwarding allows controlled access to internal services. Proper configuration of ports and firewall rules is essential for maintaining secure networks.
