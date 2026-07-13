# Day 23: Software Defined Networking (SDN)

> Understanding Software Defined Networking (SDN), SDN architecture, controllers, data plane, control plane, network automation, and cloud networking.

---

# 🎯 Learning Objectives

- Understand SDN.
- Learn SDN Architecture.
- Explore Control Plane and Data Plane.
- Understand SDN Controllers.
- Learn SDN Benefits.
- Prepare for cloud and networking interviews.

---

# 📖 Introduction

Traditional networking requires configuring each router and switch individually.

As networks grow larger, manual configuration becomes difficult.

Software Defined Networking (SDN) solves this problem by separating network intelligence from forwarding devices.

---

# 🌐 What is SDN?

Software Defined Networking (SDN) is a networking architecture that separates the Control Plane from the Data Plane.

This allows centralized management of network devices.

---

# Traditional Network

```
Router

↓

Control Plane

+

Data Plane
```

Each device makes its own decisions.

---

# SDN Architecture

```
Applications

↓

SDN Controller

↓

Network Devices

↓

Traffic Forwarding
```

---

# Control Plane

Responsible for:

- Routing Decisions
- Network Intelligence
- Policy Management

---

# Data Plane

Responsible for:

- Packet Forwarding
- Traffic Handling

---

# SDN Controller

Acts as the brain of the network.

Examples:

- OpenDaylight
- Cisco ACI
- VMware NSX

---

# Advantages of SDN

- Centralized Management
- Network Automation
- Faster Deployment
- Better Scalability
- Improved Security

---

# SDN in Cloud Computing

Cloud providers use SDN extensively.

Examples:

- AWS Networking
- Azure Virtual Networks
- Google Cloud Networking

---

# Real-World Example

A company has hundreds of switches.

Instead of configuring each switch individually, the administrator updates one SDN controller, which automatically distributes the configuration.

---

# 📌 Key Takeaways

- SDN separates the Control Plane and Data Plane.
- SDN simplifies network management.
- SDN enables automation.
- Cloud providers rely heavily on SDN.

---

# ❓ Interview Questions

### 1. What is SDN?

A networking architecture that separates the Control Plane from the Data Plane.

### 2. What is the role of an SDN Controller?

It centrally manages network devices and policies.

### 3. Why is SDN important?

It improves scalability, automation, and centralized management.

---

# 📝 Summary

Today I learned about Software Defined Networking (SDN), its architecture, Control Plane, Data Plane, SDN Controllers, and how cloud providers use SDN to automate and simplify modern networking.
