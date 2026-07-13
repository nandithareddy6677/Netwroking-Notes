# Day 21: CDN & Edge Computing

> Understanding Content Delivery Networks (CDNs), Edge Computing, caching, global content delivery, and performance optimization.

---

# 🎯 Learning Objectives

- Understand CDN.
- Learn Edge Computing.
- Explore Caching.
- Understand Global Content Delivery.
- Prepare for cloud interviews.

---

# 📖 Introduction

Millions of users access websites from different parts of the world.

Serving content from one server increases latency.

CDNs solve this problem by distributing content across multiple locations.

---

# 🌍 What is a CDN?

A CDN (Content Delivery Network) is a network of geographically distributed servers that deliver content closer to users.

Benefits:

- Faster Loading
- Reduced Latency
- Better User Experience
- Lower Server Load

---

# CDN Workflow

```
User

↓

Nearest CDN Edge Server

↓

Origin Server (if needed)

↓

Content Delivered
```

---

# What is Edge Computing?

Edge Computing processes data closer to where it is generated instead of sending everything to centralized cloud servers.

Examples:

- IoT Devices
- Smart Cameras
- Autonomous Vehicles

---

# Benefits of Edge Computing

- Low Latency
- Faster Processing
- Reduced Bandwidth Usage
- Better Real-Time Performance

---

# CDN in Cloud Platforms

AWS

- CloudFront

Azure

- Azure CDN

Google Cloud

- Cloud CDN

---

# Caching

CDNs store frequently accessed content in cache.

Examples:

- Images
- Videos
- CSS Files
- JavaScript

---

# Real-World Example

A user in India accesses a website hosted in the USA.

CloudFront serves cached content from the nearest edge location in India, reducing loading time.

---

# 💡 Best Practices

- Cache static content.
- Enable HTTPS.
- Monitor CDN performance.
- Use cache invalidation when updating content.

---

# 📌 Key Takeaways

- CDN improves website speed.
- Edge Computing reduces latency.
- Cloud providers offer managed CDN services.
- Caching improves performance.

---

# ❓ Interview Questions

### 1. What is a CDN?

A distributed network that delivers content from servers closest to users.

### 2. What is Edge Computing?

Processing data closer to users instead of centralized servers.

### 3. Which AWS service provides CDN?

Amazon CloudFront.

### 4. Why is caching important?

It reduces latency and server load.

### 5. What is an Edge Server?

A server located close to end users that delivers cached content.

---

# 📝 Summary

Today I learned about CDNs, Edge Computing, caching, and global content delivery. These technologies improve website performance, reduce latency, and enhance the user experience.
