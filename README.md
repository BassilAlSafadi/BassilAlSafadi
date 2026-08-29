# Hi, I'm Bassil 👋

### AI Systems Architect · Applied ML Engineer · Distributed Backend Engineer

Computer Engineering & Software Systems student at **Ain Shams University (ICHEP)** and an **AI Engineering Intern at Dell Technologies**. I build **end-to-end AI systems** — from fine-tuning and quantizing custom models to shipping them inside high-throughput, fault-tolerant microservice architectures that run in production.

<p>
  <a href="mailto:alsafadibasil@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://www.linkedin.com/in/bassil-alsafadi"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://github.com/BassilAlSafadi"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
</p>

* 🔭 **Working on:** scaling AI inference, LLM orchestration, and zero-trust microservice patterns.
* 🧠 **Core strength:** closing the gap between Applied ML (NLP/CV) and resilient, distributed backend systems.
* 💼 **Experience:** AI Engineering Intern @ Dell Technologies.
* 🌱 **Currently learning:** GPU-aware serving, model routing economics, and Kubernetes operators.

---

## 🛠️ Engineering Toolbox

| Domain | Technologies |
| --- | --- |
| **AI / ML** | PyTorch, Hugging Face Transformers, ONNX Runtime, LoRA / QLoRA, RAG / CAG, sentence-transformers |
| **LLM Orchestration** | LangChain, LangGraph, multi-provider routing, pgvector / Pinecone vector search |
| **Distributed Systems** | Go, C# / .NET 9, gRPC / Protobuf, NATS JetStream, Saga & Transactional Outbox patterns |
| **Backend & Infra** | FastAPI, ASP.NET Core, Docker Compose, PostgreSQL, MongoDB, Redis, AWS EC2, Cloudflare Tunnel |

---

## 🚀 Featured Systems

### 🩺 ORSA — AI Health Triage Platform
**[Code](https://github.com/BassilAlSafadi/Orsa)**
*A production-grade clinical triage engine built for high availability and clinical precision.*

* **Architecture:** microservices with a Go orchestration gateway and an ASP.NET Core 9 identity engine, wired over gRPC/Protobuf with JWT-scoped sessions.
* **AI engine:** fine-tuned **Bio-ClinicalBERT** served via ONNX Runtime for severity classification, plus multimodal analysis through vision LLMs.
* **Engineering rigor:** a 7-stage clinical triage pipeline with **FHIR R5** bundle generation and a medical knowledge graph grounding the model output.

### ♻️ RecycleHub — Circular-Economy Marketplace *(Dell Technologies · Team 1)*
**[Live Demo](https://recycle-hub-drab.vercel.app/)** · **[Code](https://github.com/BassilAlSafadi/Team1-Dell)**
*A two-sided marketplace connecting waste-producing businesses with recycling vendors — my internship project at Dell, built with a team of engineers.*

* **Polyglot mesh:** 7 processes across **5 languages** — a Go/chi gateway, three ASP.NET Core 9 services (auth, transaction, marketplace), a Node.js + Socket.IO messaging service, a Go notification service, and a Python/LangChain AI service.
* **Financial core:** an escrow-backed wallet with **optimistic concurrency control** (Postgres `xmin`) guaranteeing balance integrity under concurrent writes, spanning the full listing → offer → escrow → handover → payout lifecycle.
* **Zero-trust security:** the gateway is the only published endpoint; the compute host runs with **zero inbound ports** behind an outbound-only Cloudflare Tunnel, and backend services accept only internal mesh tokens — never user JWTs.
* **AI layer:** photo-based waste classification via Gemini vision, a retrieval-augmented (RAG) support chatbot, and cached vendor recommendations.
* **Infrastructure:** the entire system runs on a single AWS EC2 `t3.micro` (1 GB RAM) via Docker Compose — **$0/month** on free tiers.

### 🛒 MyPal — AI-Native Global Marketplace
**[Code](https://github.com/BassilAlSafadi/MyPal)**
*An event-driven PWA unifying global e-commerce with a Perplexity-style generative search experience.*

* **Distributed patterns:** **Saga-based checkout orchestration** and the **Transactional Outbox pattern** for guaranteed cross-service consistency.
* **AI discovery:** a `pgvector` semantic-search layer with multi-provider LLM routing for generative product answers.
* **Performance:** asynchronous event streaming over **NATS JetStream** for fully decoupled inter-service communication.

### 🎟️ Cinema Ticket Booking System
**[Code](https://github.com/tarek-moh/Cinema-Ticket-booking-System)**
*A high-concurrency ticketing platform designed for atomic transactions (group project).*

* **Concurrency:** a booking engine that prevents double-booking under peak load through **pessimistic locking and atomic database transactions**.
* **My contribution:** the backend reservation pipeline — optimized indexing for seat-state management and thread-safe transaction integrity.

### 🎓 Uni SIS — University Management System
**[Code](https://github.com/BassilAlSafadi/SIS)**
*A full-stack academic portal with OAuth 2.0 integration.*

* **Access control:** RBAC across three user types (student, professor, admin).
* **Integration:** automated Google Calendar API scheduling with asynchronous enrollment processing.

### 🎮 Online Multiplayer Grid Clash
**[Code](https://github.com/BassilAlSafadi/Networks_Project)**
*Low-latency real-time state synchronization over raw UDP.*

* **Protocol:** a custom binary wire format with sequence numbers, CRC32 checksums, and ACK-based flow control.

### 🌳 Syntax Tree Visualizer
**[Code](https://github.com/BassilAlSafadi/Syntax-tree-for-mathematical-operations)**
*A modular expression parser and interactive tree visualizer.*

* **Design:** object-oriented separation of the recursive parser from the interactive UI layer.

---

## 📊 GitHub Stats

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=BassilAlSafadi&show_icons=true&theme=tokyonight&count_private=true" alt="Bassil's GitHub stats" height="165">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=BassilAlSafadi&layout=compact&theme=tokyonight&langs_count=8" alt="Top Languages" height="165">
</p>
