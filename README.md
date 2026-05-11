# Hi there, I'm Seungwoo 👋

**Backend & Data Engineer focused on building robust data pipelines and optimized systems.**

From resolving OS-level concurrency issues on Edge devices to optimizing distributed processing for 50GB+ datasets, I specialize in root-cause analysis, performance tuning, and designing architectures tailored to data characteristics.

<br/>

## 🛠 Tech Stack

### Backend
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/springboot-%236DB33F.svg?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=Spring-Security&logoColor=white)

### Data & Distributed Systems
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/postgresql-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![InfluxDB](https://img.shields.io/badge/InfluxDB-22ADF6?style=for-the-badge&logo=InfluxDB&logoColor=white)
![Apache Hadoop](https://img.shields.io/badge/Apache%20Hadoop-66CC00?style=for-the-badge&logo=apachehadoop&logoColor=white)
![Apache Spark](https://img.shields.io/badge/apache%20spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)

### Infra & DevOps
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)

<br/>

## 💻 Projects & Experience

### 🔬 Distributed Data Processing Researcher | High-Performance Computing (HPC) Lab
*Focused on optimizing large-scale data pipelines and cluster performance.*
* **Data Skew Resolution:** Successfully processed 50GB of vehicle GPS data by identifying shuffle bottlenecks. Implemented a **'Salting'** technique to evenly distribute data across partitions, preventing Out-of-Memory (OOM) errors.
* **Shuffle Optimization:** Refactored Spark Java API codes from `groupByKey` to `reduceByKey`, enforcing Local Aggregation (Combiner) to drastically reduce network I/O and optimize overall batch processing time.

### 🧳 Trip-Pack | SW Maestro (16th Cohort)
*Backend for an AI-based travel planning & checklist service.*
* **Performance Tuning:** Slashed list API response time from **2.3s to 0.4s** by resolving JPA N+1 query issues and optimizing execution plans.
* **Architecture & Cost:** Designed an Aggregation API to minimize client-side network calls and decreased external AI API costs by implementing a rule-based Redis caching architecture.
* **Standardization:** Unified error handling across 14 RESTful endpoints, significantly reducing frontend debugging time and improving API consistency.

### 🔧 Smart Gardening IoT | Embedded SW Competition (National 4th Place)
*WebOS-based IoT architecture & real-time server control.*
* **Architecture Migration:** Replaced traditional Polling with **WebSocket** for real-time bidirectional communication and migrated from RDBMS to **InfluxDB** (LSM-Tree) to handle high-throughput time-series sensor data.
* **Deep Troubleshooting:** Traced and resolved an intermittent race condition by analyzing system-level IPC (Luna Service Bus) traffic via WebOS Inspector, moving beyond simple application-level debugging.
* **Open Source Contribution:** Discovered and reported a parameter type error in the official LG WebOS API documentation during the debugging process, leading to an official correction.

### 💳 SaaS Subscription Module | Industry Collaboration Project
*Payment and subscription backend implementation.*
* **Data Integrity:** Ensured 100% transaction consistency between external payment gateways (PG) and the internal DB by applying compensating transactions, idempotency keys, and **Distributed Locks**.
* **Deployment:** Successfully integrated and merged the core payment module into the production branch without disrupting existing microservices.

<br/>

## 🏆 Hackathons & Awards
* **Two-time Award Winner (2023, 2024):** Designed and shipped end-to-end MVP services under strict 24–36 hour constraints, demonstrating rapid prototyping and fast adaptation to new tech stacks (e.g., Firebase).

<br/>

## 🌱 Currently
* Deepening knowledge in message queues (Kafka) and event-driven architectures.
* Documenting technical learnings, root-cause analyses, and troubleshooting processes on my blog.

<br/>

## 📬 Contact Me

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dhtmddn00@gmail.com)
[![Tistory](https://img.shields.io/badge/Tistory-000000?style=for-the-badge&logo=Tistory&logoColor=white)](https://oh-futuristic-lifestyle.tistory.com/)
