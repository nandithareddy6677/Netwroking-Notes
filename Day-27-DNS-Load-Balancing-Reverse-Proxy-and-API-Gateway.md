# Day 27: DNS Load Balancing, Reverse Proxy & API Gateway

> Understanding DNS Load Balancing, Reverse Proxies, API Gateways, and their role in scalable, secure cloud applications.

---

# 🎯 Learning Objectives

- Understand DNS Load Balancing.
- Learn Reverse Proxy.
- Explore API Gateway.
- Understand cloud traffic routing.
- Prepare for cloud interviews.

---

# 📖 Introduction

Modern cloud applications serve users worldwide.

Instead of sending all traffic to a single server, cloud providers intelligently distribute requests using DNS, Reverse Proxies, and API Gateways.

---

# DNS Load Balancing

DNS Load Balancing directs users to different servers based on:

- Geography
- Server Health
- Latency
- Traffic Distribution

Example:

```
User

↓

DNS

↓

Server A

or

Server B
```

---

# Reverse Proxy

A Reverse Proxy receives client requests before forwarding them to backend servers.

Benefits:

- Security
- Load Balancing
- SSL Termination
- Caching

Examples:

- Nginx
- HAProxy
- Apache

---

# API Gateway

An API Gateway manages incoming API requests.

Functions:

- Authentication
- Rate Limiting
- Request Routing
- Logging
- Monitoring

---

# API Gateway in Cloud

AWS

- Amazon API Gateway

Azure

- Azure API Management

Google Cloud

- API Gateway

---

# Benefits

- Improved Performance
- Better Security
- Centralized API Management
- Scalable Applications

---

# Real-World Example

A mobile banking app sends API requests.

The API Gateway authenticates the user, forwards the request to backend services, and logs every transaction.

---

# 💡 Best Practices

- Use HTTPS.
- Enable API authentication.
- Apply rate limiting.
- Monitor API usage.
- Deploy reverse proxies for web applications.

---

# 📌 Key Takeaways

- DNS Load Balancing improves availability.
- Reverse Proxies protect backend servers.
- API Gateways manage APIs securely.
- These technologies are essential in cloud architectures.

---

# ❓ Interview Questions

### 1. What is a Reverse Proxy?

A server that forwards client requests to backend servers.

### 2. What is an API Gateway?

A service that manages API traffic.

### 3. Name one Reverse Proxy software.

Nginx.

### 4. Which AWS service provides API management?

Amazon API Gateway.

### 5. Why use DNS Load Balancing?

To improve performance and availability.

---

# 📝 Summary

Today I learned about DNS Load Balancing, Reverse Proxies, API Gateways, and how they improve scalability, security, and performance in cloud applications.
