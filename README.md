<div align="center">

# Timur (wataee)
### Full-Stack & Backend Engineer | AI Systems, Distributed Architectures & SaaS

Astana, Kazakhstan &nbsp;•&nbsp; [Email](mailto:timurkorc@gmail.com) &nbsp;•&nbsp; [GitHub](https://github.com/wataee)

<p align="center">
  I design and build production-grade web applications, resilient backend services, and practical AI integrations.<br/>
  My focus centers on clean architectural boundaries, robust data isolation (PostgreSQL RLS & pgvector), and low-latency asynchronous pipelines in TypeScript and Python.
</p>

</div>

---

### What I Build

* **Enterprise SaaS & Monorepos**: Multi-tenant architectures with database-level isolation (PostgreSQL Row-Level Security), granular RBAC, and clean domain boundaries.
* **Production RAG & AI Retrieval Gateways**: Conversational search systems featuring real-time Server-Sent Events (SSE) token streaming, Reciprocal Rank Fusion (hybrid lexical + dense vector search), and context-aware document chunking.
* **Asynchronous & Event-Driven Systems**: Distributed background worker queues (BullMQ, Celery), Redis-backed multi-turn session caching, and the Transactional Outbox pattern for guaranteed delivery.
* **Operations & Forecasting Engines**: Time-series inventory demand forecasting with safety stock optimization and automated document extraction pipelines.

---

### Tech Stack

| Layer | Technologies |
| :--- | :--- |
| **Languages** | TypeScript, Python, SQL, JavaScript |
| **Backend** | NestJS, FastAPI, Django (DRF), Node.js |
| **Frontend** | Next.js 15 (App Router), React 19, Tailwind CSS |
| **Databases & Cache** | PostgreSQL (Row-Level Security, `pgvector`), Redis, Qdrant |
| **AI & Data Systems** | RAG Architecture, Hybrid Search (Dense + BM25 via RRF), LangChain, LightGBM, Scikit-Learn |
| **DevOps & Architecture** | Docker, Docker Compose, GitHub Actions CI/CD, BullMQ, Celery, Clean Architecture, TDD |

---

### Featured Projects

| Project | Description | Stack | Verification |
| :--- | :--- | :--- | :---: |
| [**InvoiceFlow**](https://github.com/wataee/invoice-flow) | Autonomous invoice processing & multi-tier approval platform with Clean Architecture, BullMQ worker queues, and the Transactional Outbox pattern. | NestJS 11 · Next.js 15 · TypeORM · PostgreSQL · BullMQ | [![CI](https://github.com/wataee/invoice-flow/actions/workflows/ci.yml/badge.svg)](https://github.com/wataee/invoice-flow/actions/workflows/ci.yml)<br/>`379 tests passed` |
| [**StreamRAG**](https://github.com/wataee/streamrag) | Low-latency conversational RAG gateway with Server-Sent Events (SSE) token streaming, Reciprocal Rank Fusion (RRF) hybrid search, and Redis sliding-window memory. | FastAPI · Qdrant · Redis · LangChain · Docker | [![CI](https://github.com/wataee/streamrag/actions/workflows/ci.yml/badge.svg)](https://github.com/wataee/streamrag/actions/workflows/ci.yml)<br/>`24 tests passed` |
| [**TenantStack**](https://github.com/wataee/tenant-stack) | Production-ready multi-tenant B2B SaaS monorepo enforcing engine-level tenant isolation via PostgreSQL Row-Level Security (RLS) and Celery workers. | Django 5.1 · Next.js 15 · PostgreSQL 16 (RLS) · Celery | [![CI](https://github.com/wataee/tenant-stack/actions/workflows/ci.yml/badge.svg)](https://github.com/wataee/tenant-stack/actions/workflows/ci.yml)<br/>`passing` |
| [**DemandFlow**](https://github.com/wataee/demandflow) | Time-series demand forecasting and automated replenishment engine combining LightGBM, automated lag/calendar features, and safety stock optimization. | FastAPI · LightGBM · Scikit-Learn · PostgreSQL · Alembic | [![CI](https://github.com/wataee/demandflow/actions/workflows/ci.yml/badge.svg)](https://github.com/wataee/demandflow/actions/workflows/ci.yml)<br/>`passing` |
| [**ChunkFlow**](https://github.com/wataee/chunkflow) | Layout-aware document ingestion and ETL pipeline for complex unstructured PDFs, generating contextual embeddings stored in PostgreSQL via `pgvector`. | FastAPI · PostgreSQL 16 · pgvector · Celery · Docker | [![CI](https://github.com/wataee/chunkflow/actions/workflows/ci.yml/badge.svg)](https://github.com/wataee/chunkflow/actions/workflows/ci.yml)<br/>`passing` |

---

### Engineering Focus

* **Architectural Boundaries**: Isolating domain logic from frameworks and external SDKs using Clean / Hexagonal architecture principles and testable service contracts.
* **Database-Level Isolation**: Implementing defense-in-depth multi-tenancy using PostgreSQL Row-Level Security (`SET LOCAL app.current_tenant_id`) rather than relying on application-layer filtering.
* **Guaranteed Delivery & Asynchrony**: Using the Transactional Outbox pattern and robust message queues (BullMQ, Celery) to guarantee event persistence and handle asynchronous jobs safely.
* **Production RAG & Streaming**: Designing hallucination-resistant retrieval with hybrid lexical/dense search and fast time-to-first-token (TTFT) via Server-Sent Events.
* **Rigorous Automated Testing**: Enforcing strict CI gates and test suites across all services, ensuring reliable regression prevention and high test coverage.

---

### Currently Exploring

* Advanced layout-aware document parsing and multimodal tabular extraction for unstructured business filings.
* High-throughput event streaming architectures and transactional outbox scaling patterns.

---

### Contact & Availability

* **Location**: Astana, Kazakhstan (UTC+5)
* **Email**: [timurkorc@gmail.com](mailto:timurkorc@gmail.com)
* **GitHub**: [@wataee](https://github.com/wataee)
* **Engagements**: Open to contract projects, technical consulting, and full-time software engineering roles.

<div align="center">
  <sub>Maintained by <strong>wataee</strong> • Built for enterprise-grade performance and reliability</sub>
</div>
