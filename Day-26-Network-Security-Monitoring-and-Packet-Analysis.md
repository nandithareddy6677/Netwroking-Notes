# Day 26: Network Security Monitoring & Packet Analysis

> Understanding Network Security Monitoring (NSM), packet capture, traffic analysis, Wireshark, tcpdump, and network visibility for detecting and investigating cyber threats.

---

# 🎯 Learning Objectives

- Understand Network Security Monitoring (NSM).
- Learn Packet Analysis.
- Explore Wireshark and tcpdump.
- Understand Packet Capture (PCAP).
- Learn Network Traffic Analysis.
- Prepare for networking and cybersecurity interviews.

---

# 📖 Introduction

Modern organizations continuously monitor network traffic to detect suspicious activity.

Instead of waiting for an attack, security teams analyze network packets to identify threats in real time.

This process is called **Network Security Monitoring (NSM).**

---

# 🌐 What is Network Security Monitoring?

NSM is the continuous collection, analysis, and monitoring of network traffic to detect malicious activities.

Objectives:

- Detect Threats
- Monitor Traffic
- Investigate Incidents
- Improve Security

---

# Packet Capture (PCAP)

Packet Capture records network packets for analysis.

Captured packets contain:

- Source IP
- Destination IP
- Protocol
- Port Number
- Payload

---

# Wireshark

Wireshark is the world's most popular network protocol analyzer.

Features:

- Live Packet Capture
- Deep Packet Inspection
- Protocol Analysis
- Traffic Filtering

---

# tcpdump

tcpdump is a command-line packet capture tool for Linux and Unix systems.

Common uses:

- Capture traffic
- Troubleshooting
- Security investigations

---

# Packet Analysis

Analysts inspect packets to identify:

- Malware Communication
- DNS Requests
- Suspicious Connections
- Data Exfiltration

---

# Common Protocols Analyzed

- TCP
- UDP
- DNS
- HTTP
- HTTPS
- ICMP
- ARP

---

# Packet Filtering

Wireshark filters:

- ip.addr
- tcp.port
- dns
- http
- icmp

---

# Network Security Monitoring Process

Traffic

↓

Packet Capture

↓

Analysis

↓

Threat Detection

↓

Incident Response

---

# Real-World Example

A SOC analyst notices unusual outbound DNS requests.

Using Wireshark, the analyst discovers malware communicating with a malicious command-and-control server.

---

# 💡 Best Practices

- Capture traffic regularly.
- Monitor unusual connections.
- Secure packet captures.
- Correlate with SIEM logs.
- Investigate abnormal behavior.

---

# 📌 Key Takeaways

- NSM continuously monitors traffic.
- Wireshark analyzes packets graphically.
- tcpdump captures packets from the command line.
- Packet analysis helps detect cyber attacks.

---

# ❓ Interview Questions

### 1. What is Network Security Monitoring?

Continuous monitoring of network traffic for threats.

### 2. What is Wireshark?

A graphical packet analyzer.

### 3. What is tcpdump?

A command-line packet capture tool.

### 4. What is a PCAP file?

A file containing captured network packets.

### 5. Why is packet analysis important?

To investigate network activity and detect malicious behavior.

---

# 📝 Summary

Today I learned about Network Security Monitoring (NSM), packet capture, Wireshark, tcpdump, packet analysis, and how security teams investigate suspicious network activity using captured traffic.
