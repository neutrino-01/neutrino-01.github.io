---
layout: page
icon: fas fa-code
order: 3
title: Projects
---

## Spring Boot Starter — Redis Glide

Designed and developed a production-ready Spring Boot starter to integrate **Valkey Glide Client** with Spring Data Redis, enabling seamless adoption in Spring-based microservices.

- Built a custom abstraction layer to bridge Glide’s API with Spring’s RedisTemplate and repository ecosystem.
- Leveraged Glide’s high-performance architecture and **AZ affinity support** to reduce cross-availability-zone latency and minimize inter-AZ data transfer costs.
- Implemented configurable read/write routing strategies to optimize cache access patterns in distributed environments.
- Improved service-level cache latency and operational consistency by standardizing Redis integration across services.
- Designed for extensibility, allowing pluggable serialization strategies and future clustering support.

---

## Rapid Automatic Keyword Extraction (RAKE)

Designed and implemented a Python-based keyword extraction library built on the **RAKE (Rapid Automatic Keyword Extraction)** algorithm, optimized for multi-format document processing.

- Extended the core RAKE algorithm with linguistic rule enhancements and post-processing techniques to improve keyword quality.
- Added support for multiple document formats including **txt, pdf, and docx**, enabling real-world applicability across varied data sources.
- Achieved **+9% improvement in keyword precision** and **+7% improvement in recall** through tuning of stop-word filtering and phrase scoring mechanisms.
- Optimized parsing and preprocessing pipelines to improve performance on large documents.
