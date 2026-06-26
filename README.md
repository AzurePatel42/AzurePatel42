# 🧠 Mahesh Patel  
### Distributed Backend Systems • AI Retrieval (RAG) • Cloud Reliability Engineering

I design and build distributed backend platforms that operate across:

- Task orchestration systems  
- AI retrieval pipelines (RAG architectures)  
- Deterministic system-of-record layers  
- Data ingestion & preprocessing pipelines  
- Cloud infrastructure with SRE-grade reliability  

These systems are engineered to remain **correct, observable, and resilient under failure — not just functional in ideal conditions.**

---

# ⚙️ Platform Architecture
                AUTH LAYER (JWT / Identity)
                          │
    ┌──────────────────────────────────────────┐
    │           PLATFORM CORE                  │
    │                                          │
    │  Task Engine   → Orchestration Layer     │
    │  Inventory     → System of Record        │
    │  Retrieval     → AI Intelligence (RAG)   │
    │  Ingestion     → Data Processing Layer   │
    │  File Storage  → Asset Management        │
    └──────────────────────────────────────────┘
                          │
    ┌──────────────────────────────────────────┐
    │        INTELLIGENCE LAYER               │
    │   Embeddings | Ranking | Context Build   │
    └──────────────────────────────────────────┘
                          │
    ┌──────────────────────────────────────────┐
    │      RELIABILITY / SRE LAYER            │
    │ JWT | Docker | DB | Cloud | Cache | API  │
 
    └──────────────────────────────────────────
  
---

# 🧱 Core Platform Systems

## 📦 Inventory System (System of Record)
- FastAPI + PostgreSQL
- Central source of truth for all entities
- Shared across all platform services

---

## ⚙️ Task Engine (Orchestration Layer)
- Lifecycle-based execution system
- State-machine workflow engine
- Worker-based distributed processing

---

## 🧠 Retrieval Service (AI Intelligence Layer)
- Vector search + embedding pipelines
- Ranking + context assembly
- RAG-based retrieval system

---

## 📥 Data Ingestion Pipeline
- Chunking, preprocessing, taxonomy system
- Embedding preparation pipeline
- Structured data normalization

---

## 📁 File Storage API
- Azure Blob Storage integration
- Metadata-driven asset management
- Cross-service file access layer

---

## 🔐 Auth Framework
- JWT-based authentication system
- Distributed trust + RBAC design
- Multi-service identity validation

---

# 🔥 Reliability Engineering (SRE Practice)

I actively design and debug real-world system failures across:

- JWT authentication & authorization failures  
- RAG retrieval and embedding breakdowns  
- Docker deployment issues  
- Database consistency and schema failures  
- Cloud deployment failures (Azure / AWS)  
- Caching and performance bottlenecks  
- Distributed system design failures  

> I don’t just build systems — I stress-test them under failure conditions.

---

# 🧪 Experimental SaaS Systems

- Cloud Waste Detection Platform  
- Unused License Optimization System  
- Lead Generation Intelligence Pipeline (mock → production evolution)

---

# 🧩 Repository Structure

## 🧱 Platform Systems
- inventory_api  
- task-engine  
- retrieval-service  
- ingestion-pipeline  
- file-storage-api  
- auth-framework  

## 🧪 Experiments
- SaaS MVP prototypes  
- mock_data systems  
- lead generation experiments  

## 🔥 Reliability Portfolio (Debugging Systems)
- JWT authentication failures (20+ scenarios)  
- RAG cache, ranking & embedding failures  
- Docker deployment failures  
- Database & schema failures  
- Cloud production issues  
- System design failures  

---

# 🧠 Engineering Philosophy

- System of Record must always be deterministic and isolated  
- AI systems are probabilistic, never authoritative  
- Each service is independently deployable  
- Failures are first-class design inputs  
- Every system follows strict layered architecture  

---

# 🚀 Final Statement

I build and debug distributed backend systems that combine  
AI retrieval, task orchestration, and cloud infrastructure design.

My focus is not building applications —  
but designing systems that behave predictably under failure, scale, and real-world constraints.
