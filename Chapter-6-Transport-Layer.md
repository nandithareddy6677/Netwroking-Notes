# Chapter 6: Transport Layer (TCP & UDP)

> Understanding the Transport Layer, Transmission Control Protocol (TCP), User Datagram Protocol (UDP), ports, reliable communication, and how data is delivered between applications.

---

# 🎯 Learning Objectives

- Understand the Transport Layer.
- Learn the responsibilities of the Transport Layer.
- Understand TCP and UDP.
- Learn Port Numbers.
- Understand the TCP Three-Way Handshake.
- Learn Flow Control and Error Detection.
- Compare TCP and UDP.
- Prepare for networking interviews.

---

# 📖 Introduction

The Transport Layer is the **4th layer of the OSI Model** and the **3rd layer of the TCP/IP Model**.

It is responsible for providing communication between applications running on different computers.

Unlike the Network Layer, which delivers packets between devices, the Transport Layer ensures that data reaches the correct application reliably and in the correct order.

---

# 🚚 What is the Transport Layer?

The Transport Layer provides **end-to-end communication** between applications.

Its responsibilities include:

- Data Segmentation
- Reliable Delivery
- Error Detection
- Flow Control
- Port Addressing
- Data Reassembly

---

# Responsibilities of the Transport Layer

## 1. Segmentation

Large messages are divided into smaller pieces called **segments**.

Example:

A 50 MB file is divided into thousands of smaller segments before transmission.

---

## 2. Reassembly

The receiving computer combines all received segments back into the original data.

---

## 3. Error Detection

The Transport Layer checks whether data has been corrupted during transmission.

If an error occurs, the missing or damaged data is retransmitted.

---

## 4. Flow Control

Flow Control prevents the sender from overwhelming the receiver with too much data.

This ensures smooth communication.

---

## 5. Port Addressing

Multiple applications use the network simultaneously.

Port numbers help identify which application should receive incoming data.

Example:

Web Browser

↓

Port 80

Email

↓

Port 25

HTTPS

↓

Port 443

---

# TCP (Transmission Control Protocol)

TCP is a **connection-oriented** protocol.

Before sending data, it establishes a connection between the sender and receiver.

Features:

- Reliable
- Ordered Delivery
- Error Detection
- Flow Control
- Congestion Control

TCP guarantees that no data is lost.

---

# How TCP Works

TCP follows these steps:

1. Establish Connection
2. Send Data
3. Receive Acknowledgement
4. Retransmit Lost Packets
5. Close Connection

---

# TCP Three-Way Handshake

Before communication begins, TCP establishes a connection using three steps.

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
```

Connection Established

---

## Step 1

Client sends:

```
SYN
```

Meaning:

"I want to connect."

---

## Step 2

Server replies:

```
SYN + ACK
```

Meaning:

"I received your request."

---

## Step 3

Client sends:

```
ACK
```

Meaning:

"Connection established."

Now data transmission begins.

---

# Advantages of TCP

- Reliable Communication
- Ordered Data Delivery
- Error Recovery
- Flow Control
- Congestion Control

---

# Disadvantages of TCP

- Slower
- Higher Overhead
- More Resource Usage

---

# UDP (User Datagram Protocol)

UDP is a **connectionless** protocol.

It sends data immediately without establishing a connection.

Features:

- Fast
- Lightweight
- No Error Recovery
- No Acknowledgements
- No Guaranteed Delivery

---

# Advantages of UDP

- Very Fast
- Low Latency
- Less Overhead
- Suitable for Real-Time Applications

---

# Disadvantages of UDP

- No Reliability
- No Error Recovery
- Packets May Be Lost
- Data May Arrive Out of Order

---

# TCP vs UDP

| TCP | UDP |
|------|------|
| Connection-Oriented | Connectionless |
| Reliable | Unreliable |
| Slower | Faster |
| Error Recovery | No Error Recovery |
| Ordered Delivery | No Guaranteed Order |
| Uses Acknowledgements | No Acknowledgements |

---

# Common TCP Applications

- Web Browsing (HTTP)
- Secure Websites (HTTPS)
- Email
- FTP
- SSH
- Database Connections

---

# Common UDP Applications

- Video Streaming
- Voice Calls (VoIP)
- Online Gaming
- Live Broadcasting
- DNS Queries

---

# Port Numbers

A Port Number identifies an application running on a computer.

Examples:

| Service | Port |
|----------|------|
| HTTP | 80 |
| HTTPS | 443 |
| FTP | 21 |
| SSH | 22 |
| SMTP | 25 |
| DNS | 53 |

---

# Well-Known Ports

| Range | Purpose |
|--------|----------|
| 0 – 1023 | Well-Known Ports |
| 1024 – 49151 | Registered Ports |
| 49152 – 65535 | Dynamic/Ephemeral Ports |

---

# Error Detection

TCP uses:

- Checksums
- Sequence Numbers
- Acknowledgements

These mechanisms ensure data reaches the destination accurately.

---

# Flow Control

Flow Control prevents a fast sender from overwhelming a slower receiver.

TCP automatically adjusts the transmission speed based on the receiver's capacity.

---

# 🌍 Real-Life Example

Suppose you are downloading a 5 GB operating system file.

TCP is used because:

- Every packet must arrive.
- Missing packets are retransmitted.
- Data must remain in the correct order.

Now imagine watching a live cricket match.

UDP is preferred because:

- Speed is more important than perfect accuracy.
- Losing a few packets has little impact on the viewing experience.

---

# 💡 Best Practices

- Use TCP when reliability is important.
- Use UDP for real-time applications.
- Learn common port numbers.
- Understand the TCP Three-Way Handshake.
- Know the differences between TCP and UDP for interviews.

---

# 📌 Key Takeaways

- The Transport Layer provides end-to-end communication.
- TCP provides reliable communication.
- UDP provides faster communication.
- TCP uses the Three-Way Handshake.
- Port numbers identify applications.
- TCP performs error detection and flow control.
- UDP is commonly used for streaming and gaming.

---

# ❓ Interview Questions

### 1. What is the Transport Layer?

The Transport Layer provides end-to-end communication between applications running on different devices.

---

### 2. What is the difference between TCP and UDP?

TCP is connection-oriented and reliable, while UDP is connectionless and faster but does not guarantee delivery.

---

### 3. What is the TCP Three-Way Handshake?

It is the process TCP uses to establish a connection using SYN, SYN-ACK, and ACK messages.

---

### 4. Why is TCP considered reliable?

Because it uses acknowledgements, retransmissions, sequence numbers, and error detection.

---

### 5. Which protocol is used for video streaming?

UDP.

---

### 6. Which protocol is used for web browsing?

TCP.

---

### 7. What is a Port Number?

A Port Number identifies a specific application or service running on a device.

---

### 8. Which protocol uses Port 22?

SSH.

---

# 📝 Summary

Today I learned about the Transport Layer and its role in providing reliable communication between applications. I studied the differences between TCP and UDP, learned how the TCP Three-Way Handshake establishes connections, understood port numbers, flow control, error detection, and explored real-world use cases where each protocol is preferred. The Transport Layer is a fundamental networking concept used in cloud computing, cybersecurity, Linux administration, and DevOps.
