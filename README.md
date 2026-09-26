<div align="center">

# Hi there, I'm Timur (wataee) 👋
### Senior Software & AI Systems Engineer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://linkedin.com)
[![GitHub followers](https://img.shields.io/github/followers/wataee?label=Follow&style=flat&color=334155)](https://github.com/wataee)
[![Location](https://img.shields.io/badge/Location-Astana%2C%20Kazakhstan-059669?style=flat&logo=googlemaps)](https://maps.google.com)

<p align="center">
  Specializing in <strong>Clean & Hexagonal Architecture</strong>, production <strong>Retrieval-Augmented Generation (RAG)</strong>, and <strong>distributed event-driven microservices</strong>.
</p>

</div>

---

### 🛠️ Core Tech Stack & Capabilities

```
Backend Architecture  ::  NestJS (TypeScript) • FastAPI (Python 3.11+) • Clean / Hexagonal Design • TDD
AI & Retrieval        ::  LangChain • Qdrant • pgvector • Hybrid Search (RRF) • Unstructured • Gemini Flash
Event & Persistence   ::  PostgreSQL • Redis • BullMQ • Celery • Transactional Outbox Pattern
Frontend & Tooling    ::  Next.js 15 (App Router) • TypeScript • Tailwind CSS • Docker • GitHub Actions CI/CD
```

---

### 🚀 Flagship Open-Source Projects

| Project | Focus & Architecture Highlights | Stack | Quality & Verification |
| :--- | :--- | :--- | :---: |
| [**`invoice-flow`**](https://github.com/wataee/invoice-flow) | **Autonomous invoice processing & multi-tier approval platform** with Clean Architecture, TDD, BullMQ asynchronous worker queues, and the Outbox pattern for guaranteed delivery. | NestJS 11 · Next.js 15 · TypeORM · BullMQ | [![CI](https://github.com/wataee/invoice-flow/actions/workflows/ci.yml/badge.svg)](https://github.com/wataee/invoice-flow/actions/workflows/ci.yml)<br/>`379 tests passed` |
| [**`streamrag`**](https://github.com/wataee/streamrag) | **Low-latency conversational RAG retrieval gateway** with real-time Server-Sent Events (SSE) token streaming (TTFT < 350ms), Reciprocal Rank Fusion (RRF), and Redis sliding-window memory. | FastAPI · Qdrant · Redis · LangChain | [![CI](https://github.com/wataee/streamrag/actions/workflows/ci.yml/badge.svg)](https://github.com/wataee/streamrag/actions/workflows/ci.yml)<br/>`24 tests passed` |
| [**`chunkflow`**](https://github.com/wataee/chunkflow) | **High-throughput document chunking & vectorization pipeline** for unstructured enterprise documents (PDF, DOCX) into pgvector vector embeddings with Celery workers. | FastAPI · LangChain · pgvector · Unstructured | [![CI](https://github.com/wataee/chunkflow/actions/workflows/ci.yml/badge.svg)](https://github.com/wataee/chunkflow/actions/workflows/ci.yml)<br/>`passing` |
| [**`tenant-stack`**](https://github.com/wataee/tenant-stack) | **Enterprise multi-tenant conversational knowledge base** featuring strict tenant data isolation, per-workspace vector stores, and RBAC authentication guards. | FastAPI · pgvector · LangChain · Multi-tenancy | [![CI](https://github.com/wataee/tenant-stack/actions/workflows/ci.yml/badge.svg)](https://github.com/wataee/tenant-stack/actions/workflows/ci.yml)<br/>`passing` |
| [**`demandflow`**](https://github.com/wataee/demandflow) | **Multi-horizon inventory demand forecasting & replenishment intelligence** combining Facebook Prophet trend decomposition with XGBoost residual regressors. | FastAPI · Prophet · XGBoost · Streamlit | [![CI](https://github.com/wataee/demandflow/actions/workflows/ci.yml/badge.svg)](https://github.com/wataee/demandflow/actions/workflows/ci.yml)<br/>`passing` |
| [**`invoice-lens`**](https://github.com/wataee/invoice-lens) | **Multimodal vision AI document parser** leveraging Google Gemini 1.5 Flash for zero-shot line-item tabular extraction and Pydantic schema validation. | Streamlit · Gemini Flash · Pydantic · SQLite | [![CI](https://github.com/wataee/invoice-lens/actions/workflows/ci.yml/badge.svg)](https://github.com/wataee/invoice-lens/actions/workflows/ci.yml)<br/>`passing` |

---

### 📐 Engineering Principles

* **Clean Domain Modeling**: Domain logic is strictly isolated from frameworks, databases, and third-party SDKs through repository ports and use case interactors.
* **Test-Driven Rigor**: Comprehensive automated unit and integration tests with strict CI gates enforcing zero regression.
* **Production Observability**: Structured JSON logging, Prometheus/OpenTelemetry instrumentation, and health/readiness probes on all services.
* **Safe Resiliency Patterns**: Outbox transaction guarantees, idempotency keys, and exponential backoff retry policies on distributed workers.

---

<div align="center">
  <sub>Maintained by <strong>wataee</strong> • Built for enterprise-grade performance and reliability</sub>
</div>
