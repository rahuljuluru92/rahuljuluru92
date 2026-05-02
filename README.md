# Rahul Juluru

**Software Engineer · AI/ML Systems · MS Computer Science Researcher @ University of Oklahoma**

3.5+ years of industry experience across enterprise, startup, and research engineering.
Building production-grade systems at the intersection of distributed infrastructure and intelligent AI.

> Actively seeking full-time SWE / AI Engineering roles · Available May 2026

---

## About

I'm a graduate researcher and full stack engineer with hands-on experience shipping systems at Salesforce, a Series-A startup, and an active university research lab.

My work spans the full stack — React/Next.js frontends, Node.js/FastAPI backends, containerized microservices on GCP and AWS — with a growing specialization in LLM-powered applications: RAG pipelines, vector search (FAISS/Chroma), Text-to-SQL engines, and ML pipelines for biomedical classification and anomaly detection.

Currently exploring: agentic AI systems, distributed inference, and large-scale system design.

---

## What I'm Currently Working On

- Distributed systems design — rate limiting, consensus, fault-tolerant pipelines
- Agentic LLM workflows and multi-step reasoning systems
- ML infrastructure for research-grade biomedical data at OU

---

## Publication

**Prediction of Graft-Versus-Host Disease Severity Using Optical Biopsy**
*SPIE Digital Library — Proceedings of SPIE, Vol. 13843 · March 2026*

Applied PCA, PLS-DA, SVM-DA, and Multiple Instance Learning to Raman spectroscopy gut biopsy data.
Achieved up to 84% F1-score for A-GVHD severity classification — demonstrating optical biopsy as a viable early-diagnosis signal.

---

## Experience

**Software Engineer** · University of Oklahoma *(Aug 2024 – Present)* `Research Engineering · ML Infrastructure`
- Architected a containerized GCP data pipeline (Cloud Run + Pub/Sub) processing 1.8 TB of research data — reducing end-to-end time from 12 hrs to 45 min
- Reduced async task failure rate from ~35% to under 5% via Pydantic schema validation, structured logging, and exponential-backoff retry orchestration across a GCP Dataflow pipeline
- Boosted feature extraction throughput 4x using Python multiprocessing and shm-based shared memory pools across 32-core GCP Compute Engine instances
- Instrumented full pipeline observability (GCP Cloud Monitoring + structured JSON logging), cutting mean time to detect silent failures from hours to under 10 minutes

**Software Engineer** · NeoSpark Solutions *(Jun 2022 – Jun 2024)* `Full Stack · Internal Tooling`
- Shipped a self-serve internal reporting portal (Node.js / Express / React) replacing ad-hoc spreadsheet workflows across 5+ teams — reclaiming 8 hrs/week of analyst time
- Reduced dashboard load time 25% (1.8s → 1.35s) by batching async API calls and eliminating redundant sequential fetches in the Express response layer
- Refactored state management from prop-drilling to Redux/Context API — cutting wasted renders from 340ms to 95ms, Lighthouse score 61 → 84
- Established JWT-based auth with RBAC across 3 permission tiers, enabling per-team audit trails for compliance reporting

**Software Engineer** · Salesforce *(Jan 2022 – Jun 2022)* `Enterprise · CRM Platform`
- Engineered 12 Apex triggers and Flow automations unifying cross-object logic across 3 Salesforce orgs — eliminating ~30% of support escalations
- Built 4 Lightning Web Components with async RESTful bindings, cutting data retrieval latency by 40%
- Hardened least-privilege access across 6 custom objects — zero unauthorized field-access incidents across a 200+ user compliance audit

---

## Featured Projects

| Type | Project | Stack | Highlight |
|---|---|---|---|
| Systems | [DistriLimit](https://github.com/rahuljuluru92) | Redis, Lua, Python, Docker | Distributed rate limiter; atomic Lua scripts; <5ms overhead at 2,000 req/sec, 99.9% uptime under simulated DDoS |
| Systems | [CollabSpace](https://co-lab-roan.vercel.app/) | Next.js, Socket.io, Redis Pub/Sub, PostgreSQL, JWT | Real-time collaborative editor with OT conflict resolution across 50+ concurrent sessions; sub-100ms cursor sync |
| Full Stack | [Smart Expense Tracker](https://github.com/rahuljuluru92) | Next.js, FastAPI, GPT-4o, Redis, PostgreSQL, Docker | OCR-to-LLM receipt pipeline; 92% classification accuracy; 600 req/sec at P95 120ms |
| AI / LLM | [Domain-Specific RAG Chatbot](https://github.com/rahuljuluru92) | LangChain, FAISS, OpenAI, FastAPI, GCP | Answer accuracy 62% → 86%; 35% latency reduction via embedding memoization |
| AI / LLM | [Conversational Text-to-SQL](https://text-to-sql-rahul.streamlit.app/) | GPT-4, LangChain, FastAPI, PostgreSQL | Query execution rate 68% → 91%; hallucination rate cut 40% via schema-aware prompting |
| ML | [Biomedical ML — Acute GVHD](https://github.com/rahuljuluru92) | Python, SVM, MIL, scikit-learn, PCA | MIL pipeline; 84% F1; +24% specificity over average-spectrum baselines |

---

## Technical Skills

**Languages:** Python, TypeScript, JavaScript, Java, C/C++, SQL, Go

**Frontend:** React.js, Next.js, Tailwind CSS

**Backend:** Node.js, Express.js, FastAPI, Django/DRF, Flask

**AI / LLM:** LangChain, RAG, OpenAI GPT-4, FAISS, Chroma, Prompt Engineering, Text-to-SQL, AI Agents, Hugging Face

**ML / Data:** scikit-learn, Pandas, NumPy, XGBoost, Isolation Forest, SVM, Random Forest, Multiple Instance Learning, Streamlit

**Infrastructure:** Docker, Kubernetes, GCP (Cloud Run, Pub/Sub, Vertex AI), AWS (Lambda, S3, SageMaker), CI/CD, GitHub Actions

**Databases:** PostgreSQL, MongoDB, Redis, MySQL, Firebase, Pinecone

---


## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rahul-juluru/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:rahuljuluru92@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=vercel&logoColor=white)](https://rahuljuluru.com)

