# Sharan S

**Systems & Applied AI Engineer**  
Computer Science Undergraduate, BMS College of Engineering, Bengaluru (Batch 2024–2028)

[LinkedIn](https://www.linkedin.com/in/sharan-s7/) | [GitHub](https://github.com/sharancode3) | [Instagram](https://www.instagram.com/sharans7_/) | [Email](mailto:sharan18x@gmail.com) | Bengaluru, India

---

## Engineering Overview

Systems and Applied AI engineer specializing in self-hosted edge infrastructure, local-first privacy-preserving AI runtimes, deterministic backend services, and high-performance cross-platform applications. Experience includes engineering mobile feature pipelines at InternLoom, building full-stack products at Homi, and designing hackathon platforms across infrastructure, geospatial telemetry, and automated financial auditing.

All projects emphasize verifiable system execution, physical resource constraints, and edge/on-device inference over third-party cloud API dependencies.

---

## Technical Skills

- **Languages:** Python, TypeScript, JavaScript, Dart, Kotlin, C, C++, SQL (PL/pgSQL), Bash
- **Edge & Infrastructure:** Docker Engine API, Linux Server Administration (Ubuntu), Microservices Orchestration, Relational Schema Architecture, MinIO Object Storage
- **Applied AI & Local Runtimes:** Local LLM Inference via Ollama (Gemma 3, Qwen 2.5), Structured Output Enforcement (JSON Schema Mode), Function Calling, Dual-Pass Verification Loops, Semantic Embedding Pipelines, GDAL Geospatial Telemetry
- **Mobile & Native Systems:** Flutter, Riverpod, Isar Offline Storage, Android SDK, Native Platform Channels (C++/Kotlin), Gyroscope Sensor Fusion
- **Full-Stack & Databases:** Next.js, FastAPI, Node.js, Express.js, PostgreSQL, PL/pgSQL Stored Procedures, Prisma ORM, Supabase, Cloud Firestore
- **DevOps & Tooling:** Docker, Docker Compose, Git, GitHub Actions, Vercel, Netlify

---

## Featured Systems

### [Homelab BaaS](https://github.com/sharancode3/Homelab)
**Self-Hosted Backend-as-a-Service & Edge Container Orchestration Runtime**  
*Engineered for Single-Node Resource-Constrained Hardware (4 GB RAM ThinkPad on Ubuntu Server)*

- **Hardware-Constrained Architecture:** Engineered from first principles to operate isolated development environments within a strict 4 GB memory ceiling.
- **Automated Container Provisioning:** Built a FastAPI management daemon that communicates directly with the Docker Engine API to provision isolated PostgreSQL database instances and MinIO S3-compatible storage buckets per project.
- **Authorization & Project Scoping:** Implements project-scoped API key generation, credential rotation, and role-based endpoint access control without relying on external cloud authentication vendors.
- **Stack:** Python, FastAPI, Docker Engine API, PostgreSQL, MinIO, Linux, Bash

---

### [Privex AI](https://www.privexai.in)
**Local-First Privacy-Preserving AI & On-Device Intelligence Platform**  
*Production Deployment: [privexai.in](https://www.privexai.in)*

- **Zero-Egress Inference Architecture:** Engineered for sensitive data environments where proprietary source code, internal notes, and confidential documents must never leave the host device.
- **Local Embedding & Retrieval Engine:** Implements on-device semantic retrieval over local document stores, pairing lightweight vector search with local model execution via Ollama and quantized weights (Gemma / Qwen).
- **Offline Document Intelligence:** Processes and extracts structured insights from unstructured PDFs, spreadsheets, and text records entirely on local hardware with zero external API calls.
- **Stack:** Python, FastAPI, TypeScript, Next.js, Ollama, Vector Search, Local Storage

---

### [Hireflow](https://github.com/sharancode3/Hireflow)
**Production Enterprise Hiring Platform, Role-Based ATS & Resume Engine**  
*Full-Stack Application: [github.com/sharancode3/Hireflow](https://github.com/sharancode3/Hireflow)*

- **Transactional Workflow Automation:** Provides multi-role portal pipelines (Job Seeker, Recruiter, Admin) with state-machine-driven candidate evaluation stages.
- **Database Architecture:** Backed by PostgreSQL with custom PL/pgSQL stored procedures for relational integrity, coupled with Prisma ORM migrations and Next.js frontend state machines.
- **ATS Compilation:** Automated structured resume generation and candidate profile export pipelines.
- **Stack:** TypeScript, Next.js, PostgreSQL, PL/pgSQL, Prisma ORM, Express.js, Tailwind CSS

---

### [ThermoTrace AI](https://github.com/sharancode3/ThermoTrace-AI)
**Satellite Thermal Intelligence & Industrial Flaring Anomaly Monitoring Platform**  
*Engineered for Smart India Hackathon 2026 (Problem Statement 162 for NTRO & CPCB)*

- **Multispectral Telemetry Processing:** Ingests satellite thermal infrared imagery to locate persistent industrial flaring hotspots and subsurface thermal anomalies.
- **Spatial Anomaly Pipeline:** Computes geographic clustering of heat signatures using GDAL and vector coordinate transformations.
- **Service Orchestration:** Features a containerized FastAPI backend configured via Docker Compose v2 for automated event streaming and compliance report generation.
- **Stack:** Python, FastAPI, TypeScript, Geospatial AI, GDAL, Vector Maps, Docker Compose

---

### [GiGly](https://github.com/sharancode3/GiGly)
**Gig-Economy Worker Safety Companion & Algorithmic Pay Fairness Analyzer**  
*Built for the Synaptrix Hackathon at BMSCE*

- **Algorithmic Pay Transparency:** Computes real-time earning rates against active shift durations to detect payout discrepancies.
- **Low-Overhead Native Telemetry:** Implemented a custom native C++ and Kotlin bridge communicating over Flutter platform channels to maintain persistent GPS telemetry and safety beacons while minimizing battery consumption during multi-hour delivery shifts.
- **Local AI Verification:** Integrates on-device Gemma 3 4B via Ollama for offline-accessible shift insights and emergency workflows.
- **Stack:** Flutter, Dart, Python, FastAPI, Firebase, Ollama, Kotlin, C++

---

### [Finora](https://github.com/sharancode3/Finora)
**Autonomous AI Finance Controller & Continuous Reconciliation Platform**  
*Built for the Razorpay AI Buildathon (AI Finance Controller Track)*

- **Continuous 3-Way Matching Engine:** Automatically reconciles inconsistencies across banking feeds, internal purchase registers, and GSTR-2B datasets to detect ledger drift.
- **Dual-Pass Verification Gatekeeper:** Integrates a locally-hosted Gemma 3 4B model via Ollama. Implements a dedicated Verifier class that tokenizes and cross-checks all numeric values from draft model outputs against tool execution results before committing ledger mutations or triggering UI actions.
- **Stochastic Forecasting:** Integrates Monte Carlo cash-flow simulation routines to project liquidity trajectories under varying settlement timelines.
- **Stack:** Python, FastAPI, TypeScript, Next.js, Ollama, Cloud Firestore

---

## Technical Projects Index

| Project | Primary Domain | Core Stack | Repository / Link |
| :--- | :--- | :--- | :--- |
| **Homelab BaaS** | Self-Hosted 4GB Edge Developer Platform & Orchestrator | Python, FastAPI, Docker Engine API, MinIO, Linux | [github.com/sharancode3/Homelab](https://github.com/sharancode3/Homelab) |
| **Privex AI** | Local-First Privacy-Preserving AI Platform | Python, Next.js, TypeScript, Ollama, Vector Search | [privexai.in](https://www.privexai.in) |
| **Hireflow** | Enterprise ATS, Role-Based Workflows & Resume Engine | TypeScript, Next.js, PostgreSQL, Prisma, PL/pgSQL | [github.com/sharancode3/Hireflow](https://github.com/sharancode3/Hireflow) |
| **ThermoTrace AI** | Satellite Thermal & Geospatial Hotspot Monitoring (SIH 2026) | Python, FastAPI, TypeScript, GDAL, Docker | [github.com/sharancode3/ThermoTrace-AI](https://github.com/sharancode3/ThermoTrace-AI) |
| **GiGly** | Worker Pay Fairness & Low-Overhead Native Telemetry | Flutter, Dart, Python, Firebase, Kotlin, C++ | [github.com/sharancode3/GiGly](https://github.com/sharancode3/GiGly) |
| **Finora** | AI Finance Controller & 3-Way Reconciliation | TypeScript, Python, Next.js, Ollama, Firestore | [github.com/sharancode3/Finora](https://github.com/sharancode3/Finora) |
| **Skill-Lens AI** | Adaptive Multi-Turn AI Technical Interview Platform | JavaScript, Node.js, Google Gemini API, Python | [github.com/sharancode3/Skill-lens-AI](https://github.com/sharancode3/Skill-lens-AI) |
| **JobSwipe** | Mobile Internship Discovery Client (Signed APK v2.0.1) | Flutter, Dart, Riverpod, Supabase, Android SDK | [github.com/sharancode3/JobSwipe](https://github.com/sharancode3/JobSwipe) |
| **Hydra Leaf** | Hardware Sensor Fusion Android Physics Game Engine | Java, Kotlin, C, Android Native Sensor API | [github.com/sharancode3/Hydra-leaf-Source-code](https://github.com/sharancode3/Hydra-leaf-Source-code) |
| **CHEAT-LABZ** | Browser Gaming Platform with Canvas Physics & Socket.IO | JavaScript, HTML5 Canvas, Socket.IO, CSS3 | [github.com/sharancode3/CHEAT-LABZ](https://github.com/sharancode3/CHEAT-LABZ) |
| **Hyper-Pong** | Canvas Collision Loop & Dynamic Game Physics Engine | JavaScript, HTML5 Canvas, CSS3 | [github.com/sharancode3/Hyper-Pong](https://github.com/sharancode3/Hyper-Pong) |

---

## Currently Building

Developing offline-first state synchronization patterns, edge container orchestration runtimes, and local-first inference architectures.

---

## Contact

- **GitHub:** [github.com/sharancode3](https://github.com/sharancode3)
- **LinkedIn:** [linkedin.com/in/sharan-s7](https://www.linkedin.com/in/sharan-s7/)
- **Instagram:** [instagram.com/sharans7_](https://www.instagram.com/sharans7_/)
- **Email:** [sharan18x@gmail.com](mailto:sharan18x@gmail.com)
- **Location:** Bengaluru, India
