# Ayush Singh

### Software Engineer | Java | Spring Boot | Microservices

I’m a Software Engineer with **2+ years of experience** building backend systems and distributed applications, primarily in the fintech domain.

Currently working at **Worldline India**, where I build Java/Spring Boot services for merchant onboarding and high-throughput payment transaction processing.

I enjoy solving backend engineering challenges involving distributed systems, concurrency, performance optimization, fault tolerance, and scalable architecture.

- 🎓 B.Tech in Computer Science — **IIIT Vadodara (2024)**
- 💼 Full Stack Engineer at **Worldline India**
- 💻 Solved **900+ DSA problems** across GeeksforGeeks and LeetCode
- 🏆 Regional Winner — Azadi Ka Amrit Mahotsav Hackathon 2022, Government of Gujarat

---

## Tech Stack

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)

**Backend & Frameworks**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

**Messaging, Databases & Distributed Systems**

![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)

**Tools & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)

---

## Featured Projects

### [SmartProxy](https://github.com/rectifier796/Smart-Proxy)
**Distributed API Gateway · Rate Limiter · Custom L7 Load Balancer**

A Java-based API gateway focused on request routing, distributed rate limiting, and backend resilience.

- Built a horizontally scalable L7 API gateway handling **500+ requests/sec in local benchmarks** across 5+ backend nodes.
- Implemented a Redis-backed distributed token-bucket rate limiter using atomic Lua scripts, enforcing limits within approximately 2 ms across 10+ concurrent instances.
- Developed round-robin, weighted, least-connections, and power-of-two load-balancing strategies.
- Added active health checks, circuit breaking, and bounded retries for fault-tolerant request routing.

**Tech:** Java · Spring Boot · WebFlux · Redis · PostgreSQL

### [ByteStoreX](https://github.com/rectifier796/ByteStoreX)
**Resumable Object Storage & File Processing Platform**

An S3-compatible large-file storage platform designed for reliable uploads, recovery, and efficient storage utilization.

- Implemented bounded-parallel chunk uploads and HTTP Range-based recovery, supporting files up to **10+ GB**.
- Reduced redundant storage by approximately **30%** through SHA-256 content-based deduplication.
- Built concurrency-safe upload finalization using PostgreSQL transactions, optimistic locking, and Redis.
- Implemented a PostgreSQL-backed job queue using `FOR UPDATE SKIP LOCKED`, processing **100+ jobs/min** with retry and backoff.

**Tech:** Node.js · TypeScript · Express · PostgreSQL · Redis · MinIO

---

## Professional Experience

### Worldline India Pvt. Ltd.
**Full Stack Engineer | October 2024 – Present**

Working on fintech platforms involving merchant onboarding and high-volume payment transaction processing.

**Generic Listener — Payment Transaction Processing**
- Architected a configuration-driven Spring Boot consumer framework running independent listeners across **20+ RabbitMQ queues** using JSON definitions.
- Reduced new queue integration time from **3–4 days to under an hour**, without requiring code changes.
- Designed retry, dead-letter, and quarantine pipelines, with cache-based sequencing to achieve **99.9% ordered-delivery reliability**.
- Engineered partition-key-based message routing and dynamic listener scaling to absorb **7x peak traffic**.

**Merchant & Terminal Management**
- Developed Orchestration and Terminal Services within a **10+ microservice** merchant onboarding platform.
- Optimized PostgreSQL queries through indexing, pagination, query rewriting, and schema normalization, reducing execution time from **2–3 seconds to 20–40 ms**.
- Improved cross-service incident investigation using Zipkin, Spring Boot Admin, Config Server, and ELK-based logging.

### Maximl Labs Pvt. Ltd.
**Software Development Intern | January 2024 – April 2024**

- Developed a no-code website builder backend using NestJS, building **25+ REST APIs** for page rendering and publishing.
- Implemented JWT authentication and PostgreSQL integration using TypeORM.
- Built a coupon engine supporting **7+ discount rule types** and automated **100+ monthly invoices** through Zoho REST API integration.

---

## Achievements

- 🏆 **Regional Winner** — Azadi Ka Amrit Mahotsav Hackathon 2022, Government of Gujarat.
- 💡 Solved **900+ Data Structures and Algorithms problems** across GeeksforGeeks and LeetCode.

---

## Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ayush_Singh-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/ayush796)
[![GitHub](https://img.shields.io/badge/GitHub-rectifier796-181717?style=flat-square&logo=github)](https://github.com/rectifier796)
[![Email](https://img.shields.io/badge/Email-Contact_Me-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ayusgsingh796@gmail.com)

---

*Building reliable systems, solving interesting problems, and continuously learning.*
