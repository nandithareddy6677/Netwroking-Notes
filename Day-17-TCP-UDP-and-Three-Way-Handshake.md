# Day 17: TCP, UDP & Three-Way Handshake

> Understanding Transmission Control Protocol (TCP), User Datagram Protocol (UDP), TCP Three-Way Handshake, connection management, and transport layer communication.

---

# 🎯 Learning Objectives

- Understand the Transport Layer.
- Learn TCP.
- Learn UDP.
- Understand the TCP Three-Way Handshake.
- Compare TCP and UDP.
- Prepare for networking interviews.

---

# 📖 Introduction

The Transport Layer (Layer 4) is responsible for delivering data between applications running on different devices.

The two primary protocols are:

- TCP (Transmission Control Protocol)
- UDP (User Datagram Protocol)

---

# 🚚 What is TCP?

TCP is a connection-oriented protocol that ensures reliable data delivery.

Features:

- Reliable
- Ordered Delivery
- Error Checking
- Flow Control
- Congestion Control

Examples:

- HTTP/HTTPS
- SSH
- FTP
- SMTP

---

# 📡 What is UDP?

UDP is a connectionless protocol that sends data without establishing a connection.

Features:

- Fast
- Low Overhead
- No Error Recovery
- No Guaranteed Delivery

Examples:

- DNS
- VoIP
- Video Streaming
- Online Gaming

---

# TCP Three-Way Handshake

Before communication begins:

```
Client

↓

SYN

↓

Server

↓

SYN + ACK

↓

Client

↓

ACK

↓

Connection Established
```

---

# TCP Connection Termination

TCP closes connections using a Four-Way Handshake.

```
FIN

↓

ACK

↓

FIN

↓

ACK
```

---

# TCP vs UDP

| TCP | UDP |
|------|------|
| Connection-Oriented | Connectionless |
| Reliable | Faster |
| Error Recovery | No Recovery |
| Ordered Delivery | No Ordering |
| Larger Overhead | Smaller Overhead |

---

# TCP Applications

- Banking
- Email
- Web Browsing
- File Transfer

---

# UDP Applications

- Video Calls
- Gaming
- DNS
- Live Streaming

---

# TCP Flags

- SYN
- ACK
- FIN
- RST
- PSH
- URG

---

# 🌍 Real-Life Example

When you open a banking website, TCP establishes a reliable connection using the Three-Way Handshake before transmitting sensitive information.

---

# 💡 Best Practices

- Use TCP for reliable communication.
- Use UDP for low-latency applications.
- Monitor TCP connections.
- Secure TCP services with TLS.

---

# 📌 Key Takeaways

- TCP is reliable.
- UDP is fast.
- TCP uses a Three-Way Handshake.
- TCP provides ordered delivery.
- UDP is widely used for streaming.

---

# ❓ Interview Questions

### 1. What is TCP?

A reliable connection-oriented transport protocol.

### 2. What is UDP?

A connectionless protocol designed for speed.

### 3. What are the steps in TCP Three-Way Handshake?

SYN → SYN-ACK → ACK

### 4. Which protocol is used by HTTPS?

TCP

### 5. Which protocol does DNS primarily use?

UDP

---

# 📝 Summary

Today I learned about TCP, UDP, the TCP Three-Way Handshake, TCP flags, and their real-world applications. TCP ensures reliable communication, while UDP prioritizes speed for latency-sensitive applications.
