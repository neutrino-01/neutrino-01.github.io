---
layout: page
icon: fas fa-briefcase
order: 2
title: Experience
---

## SDE-3 — Changejar Technologies  
*Jan 2023 – Present | Bangalore, India*

Led backend architecture for large-scale fintech systems processing millions of daily transactions.

- Led end-to-end architecture and delivery of a **UPI application within 3 months**, coordinating backend and app teams; designed a centralized **job-runner system for real-time NPCI reconciliation** with idempotent processing, retry mechanisms, and failure recovery workflows.
- Architected and built a **multi-tenant digital gold platform** processing **6M+ transactions/day at 2000+ RPS**, achieving **99.99% success rate** through optimized data modeling, caching strategies, and proactive observability.
- Designed and implemented a **high-performance API gateway (10000+ RPS)** with rate limiting, authentication, IP whitelisting, and service onboarding abstractions.
- Built reusable internal frameworks for **Redis, MongoDB, and PostgreSQL** enabling:
  - Read-through caching with TTL invalidation
  - Standardized encryption/decryption pipelines
  - Custom ID generation strategies
  Resulting in faster service bootstrapping and consistent data handling.
- Developed a production-grade HTTP framework incorporating **circuit breaking, structured logging, metrics instrumentation, and standardized error handling**, reducing external API integration effort by **50%**.
- Improved multi-tenant observability by implementing structured logging, tenant-scoped metrics tagging, and distributed tracing, **reducing MTTR by ~40%** and enabling faster root-cause analysis across transactions.

---

## Backend Engineer (R1) — 99.co  
*Jan 2022 – Dec 2022*

Built scalable automation systems to optimize listing workflows across platforms.

- Designed and implemented a **smart listing automation pipeline** leveraging graph algorithms and third-party SDK integrations, reducing posting time by **40% (text)** and **50% (video)**.
- Built a **cross-platform publishing system** enabling agents to distribute listings across multiple marketplaces in a single workflow, significantly reducing manual operational overhead.
- Improved content publishing reliability and reduced human intervention in listing lifecycle management.

---

## SDE-2 — Games24x7  
*Apr 2021 – Jan 2022*

Focused on backend scalability for high-concurrency gaming systems.

- Built a **Quartz-based tournament scheduler service** orchestrating time-bound online tournaments with configurable execution rules and reliable job management.
- Integrated a data science model into the add-cash service to personalize user experiences, improving engagement and monetization signals.
- Enhanced system stability under concurrent gaming traffic through backend optimizations and service isolation strategies.

---

## SDE-1 — Games24x7  
*Oct 2019 – Apr 2021*

Worked on backend performance optimization and infrastructure efficiency.

- Migrated Kafka-based cleanup pipeline from EC2 to AWS Lambda, achieving **90% infrastructure cost reduction** while preserving downstream processing guarantees.
- Optimized MySQL query performance by **70%** using seek-based pagination for high-cardinality datasets, reducing latency and improving throughput.
- Built a contest prioritization engine based on cohort behavior to personalize contest visibility and improve user engagement.