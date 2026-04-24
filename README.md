# Hi 👋, I'm Meet Sinojia

* 🚀 **Software Engineer @ UBS | Building Scalable Backend Systems & Distributed Architectures**
* 💡 Building scalable systems, APIs & data pipelines
* 🏆 LeetCode Knight (Top 5%) | CodeChef 3⭐

---

## 🌐 Connect with me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Meet%20Sinojia-blue?style=for-the-badge\&logo=linkedin)](https://linkedin.com/in/meet-sinojia-453595203)
[![GitHub](https://img.shields.io/badge/GitHub-MeetSinojia-red?style=for-the-badge\&logo=github)](https://github.com/MeetSinojia)
[![LeetCode](https://img.shields.io/badge/LeetCode-Meet%20Sinojia-orange?style=for-the-badge\&logo=leetcode)](https://leetcode.com/Meet%20Sinojia)

---

## 🚀 About Me

* 🔭 Software Engineer at **UBS**, building **backend services & data pipelines at scale**
* 🧠 Strong in **DSA (LeetCode Knight), System Design & Distributed Systems**
* 🚀 Experience with **Kafka (event-driven systems), Redis (rate limiting), AWS (RDS, S3)**
* 📱 Built & shipped **GarageWala** — a **production app on Play Store**
* 🔐 Designed secure systems using **OAuth2, JWT & role-based access control**

---

## 🚀 What I Build

* Scalable backend systems (sharding, caching, async processing)
* High-performance APIs (low latency, rate-limited)
* Distributed systems with real-world trade-offs
* Production-ready architectures

---

## 🛠️ Tech Stack

### 💻 Languages

![C++](https://img.shields.io/badge/C++-blue?style=flat\&logo=cplusplus)
![Python](https://img.shields.io/badge/Python-yellow?style=flat\&logo=python)
![Golang](https://img.shields.io/badge/Go-blue?style=flat\&logo=go)
![Java](https://img.shields.io/badge/Java-red?style=flat\&logo=java)
![JavaScript](https://img.shields.io/badge/JavaScript-yellow?style=flat\&logo=javascript)
![Dart](https://img.shields.io/badge/Dart-blue?style=flat\&logo=dart)

---

### ⚙️ Backend & Infra

![Spring Boot](https://img.shields.io/badge/SpringBoot-red?style=flat\&logo=spring)
![Node.js](https://img.shields.io/badge/Node.js-green?style=flat\&logo=node.js)
![Gin](https://img.shields.io/badge/Gin-blue?style=flat)
![Kafka](https://img.shields.io/badge/Kafka-yellow?style=flat\&logo=apachekafka)
![Redis](https://img.shields.io/badge/Redis-red?style=flat\&logo=redis)
![Docker](https://img.shields.io/badge/Docker-blue?style=flat\&logo=docker)

---

### ☁️ Cloud & Infrastructure

![AWS RDS](https://img.shields.io/badge/AWS%20RDS-orange?style=flat\&logo=amazonaws)
![AWS S3](https://img.shields.io/badge/AWS%20S3-orange?style=flat\&logo=amazonaws)
![Linux](https://img.shields.io/badge/Linux-black?style=flat\&logo=linux)
![CI/CD](https://img.shields.io/badge/CI/CD-grey?style=flat)

---

### 🧠 System Design & Concepts

![Distributed Systems](https://img.shields.io/badge/Distributed%20Systems-blue?style=flat)
![DB Sharding](https://img.shields.io/badge/DB%20Sharding-purple?style=flat)
![Caching](https://img.shields.io/badge/Caching-red?style=flat)
![Rate Limiting](https://img.shields.io/badge/Rate%20Limiting-orange?style=flat)
![Load Balancing](https://img.shields.io/badge/Load%20Balancing-green?style=flat)
![Concurrency](https://img.shields.io/badge/Concurrency-lightgrey?style=flat)
![Event Driven](https://img.shields.io/badge/Event%20Driven-black?style=flat)

---

## 🔥 Projects

---

## 🚗 GarageWala

> 📱 Production-grade vendor management platform (Live on Play Store)

[![Play Store](https://img.shields.io/badge/Download-App-green?style=for-the-badge\&logo=googleplay)](https://play.google.com/store/apps/details?id=com.mrmechanic.app&pcampaignid=web_share)

### 🔥 Highlights

* 🚀 Built and deployed a **scalable full-stack system** serving real-world garage operations
* ⚡ Designed APIs handling **authentication, billing, inventory & bookings**
* 📈 Improved system reliability using **event-driven architecture (Kafka)**
* 🔐 Implemented **secure OTP-based authentication (MSG91)**

### 🧠 System Design & Architecture

* 📡 **Kafka-based async processing** for booking → notification flow
* ⚡ **Redis rate limiting (Token Bucket)** to prevent API abuse
* 🗄️ **MySQL (AWS RDS)** for structured data
* 🖼️ **AWS S3** for scalable image storage

### ⚙️ Features

* 🧾 Smart billing & invoice generation
* 📦 Inventory management system
* 📅 Booking & scheduling workflows
* 🔔 Real-time notifications (Firebase)
* 🔑 Role-based access control for vendors

### 🚀 Tech Stack

`Golang` • `Gin` • `MySQL` • `Redis` • `Kafka` • `AWS (RDS, S3)` • `Firebase` • `Flutter`

### 💡 Why this stands out

* Real **production app (not just project)**
* Covers **LLD + HLD concepts** (rate limiter, async systems, auth)
* Demonstrates **system design + scalability mindset**

---

## 🔗 Snip URL Shortener System

📱 **Scalable backend system with sharding, read replicas & intelligent caching**

---

### 🔥 Highlights

* 🚀 Designed a **production-style distributed system** with sharded PostgreSQL
* ⚡ Implemented **read/write separation** using primary–replica architecture
* 📈 Optimized performance using **Redis cache with LFU eviction strategy**
* 🔐 Built **rate limiting middleware** to prevent API abuse
* 🧠 Integrated **Snowflake ID generation** for distributed uniqueness

---

### 🧠 System Design & Architecture

* 🧩 **Database Sharding** → hash(shortCode) for horizontal scaling
* 🔁 **Primary–Replica Model** → writes to primary, reads from replica
* ⚡ **Cache-Aside Pattern (Redis)** → reduces DB load significantly
* 🔥 **LFU Cache Eviction** → keeps frequently accessed URLs in memory
* 🚦 **Rate Limiting (Redis)** → token bucket style per IP
* 🧵 **Thread-safe Routing (ThreadLocal)** → correct shard selection

---

### ⚙️ Features

* 🔗 URL shortening & fast redirection
* 📊 Click analytics with TTL-based storage
* ⚡ High-performance caching layer
* 🛡️ API rate limiting
* 📡 Observability with request & routing logs

---

### 🚀 Tech Stack

Java • Spring Boot • PostgreSQL • Redis • Docker • NGINX • Flyway

---

### 💡 Why this stands out

* Implements **real system design concepts** (not CRUD)
* Demonstrates **scalability: sharding + replicas**
* Shows **deep backend thinking (caching, routing, infra)**
* Covers **HLD + LLD + infra-level understanding**

---

## 🛒 EchoShop

> Full-stack e-commerce platform

* 💳 Stripe payment integration
* 🚚 Optimized delivery using **Dijkstra’s Algorithm**

---

## 🧠 Problem Solving

* 🟡 LeetCode Knight (1930+)
* ⭐ CodeChef 3★
* 🔵 Codeforces Pupil

---

## 📚 Currently Learning

* Distributed systems (Kafka, consistency models)
* Kubernetes & container orchestration
* Advanced system design (multi-region, fault tolerance)

---
