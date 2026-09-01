# Sharan S

**Systems & Applied AI Engineer**  
Computer Science Undergraduate, BMS College of Engineering, Bengaluru (Batch 2024–2028)

[LinkedIn](https://www.linkedin.com/in/sharan-s7/) | [GitHub](https://github.com/sharancode3) | [Instagram](https://www.instagram.com/sharns7_/) | [Email](mailto:sharan18x@gmail.com) | Bengaluru, India

---

## Engineering Overview

Systems and Applied AI engineer with an emphasis on deterministic backend architecture, local LLM orchestration, resource-constrained edge computing, and high-performance cross-platform mobile systems. Experience spans developing mobile features at InternLoom, building full-stack products at Homi, and engineering hackathon platforms across fintech, geospatial telemetry, and developer tooling. 

All systems prioritize verifiable execution, physical resource efficiency, and local/on-device inference over superficial API wrappers.

---

## Core Technical Competencies

- **Applied AI & Local Inference:** Local LLM deployment via Ollama (Gemma 3, Qwen 2.5), Structured Output (JSON Schema Mode), Function/Tool Calling, Dual-Pass Verifier Architectures, Monte Carlo Simulation Models.
- **Mobile & Native Systems:** Flutter, Dart, Riverpod State Architecture, Isar Offline DB, Android SDK, Native Platform Channels (C++/Kotlin), Gyroscope Hardware Sensor Fusion.
- **Backend & Edge Infrastructure:** FastAPI, Node.js, Express.js, Docker Engine API, Linux Server Administration (Ubuntu), Relational Schema Design, MinIO Object Storage.
- **Data Engineering & Databases:** PostgreSQL, PL/pgSQL Stored Procedures, Prisma ORM, Supabase, Cloud Firestore, Firebase Realtime Database.
- **Languages:** Python, TypeScript, JavaScript, Dart, Kotlin, C, C++, SQL, Bash.

---

## Flagship Systems

### [Finora](https://github.com/sharancode3/Finora)
**Autonomous AI Finance Controller & Continuous Reconciliation Platform**  
*Built for the Razorpay AI Buildathon (AI Finance Controller Track)*

- **Continuous 3-Way Matching Engine:** Automatically reconciles inconsistencies across banking feeds, internal purchase registers, and GSTR-2B datasets to detect ledger drift.
- **Dual-Pass Verification Gatekeeper:** Integrates a locally-hosted Gemma 3 4B model via Ollama. Implements a dedicated Verifier class that tokenizes and cross-checks all numeric values from draft model outputs against tool execution results before committing ledger mutations or triggering UI actions.
- **Stochastic Forecasting:** Integrates Monte Carlo cash-flow simulation routines to project liquidity trajectories under varying settlement timelines.
- **Stack:** Python, FastAPI, TypeScript, Next.js, Ollama, Cloud Firestore

---

### [JobSwipe](https://github.com/sharancode3/JobSwipe)
**Gesture-Driven Mobile Internship Discovery & Application Client**  
*1st Place Winner at BMSCE x InternLoom Hackathon 2026 (App Development Track)*

- **Fluid Swipe UX:** Designed a gesture-driven card-stack interface with optimistic local UI state management and custom card dismiss physics.
- **State & Data Pipeline:** Implemented Riverpod state container architecture for isolated candidate state, persistent offline profile caching, and multipart resume upload handling.
- **Release Status:** Shipped production-ready signed Android application packages (v2.0.1 APK).
- **Stack:** Flutter, Dart, Riverpod, Supabase, Android SDK

---

### [ThermoTrace AI](https://github.com/sharancode3/ThermoTrace-AI)
**Satellite Thermal Intelligence & Industrial Flaring Anomaly Monitoring Platform**  
*Engineered for Smart India Hackathon 2026 (Problem Statement 162 for NTRO & CPCB)*

- **Multispectral Telemetry Processing:** Ingests satellite thermal infrared imagery to locate persistent industrial flaring hotspots and subsurface thermal anomalies.
- **Spatial Anomaly Pipeline:** Computes geographic clustering of heat signatures using GDAL and vector coordinate transformations.
- **Service Orchestration:** Features a containerized FastAPI backend configured via Docker Compose v2 for automated event streaming and compliance report generation.
- **Stack:** Python, FastAPI, TypeScript, Geospatial AI, GDAL, Vector Maps, Docker Compose

---

### [Homelab BaaS](https://github.com/sharancode3/Homelab)
**Self-Hosted Backend-as-a-Service & Edge Container Orchestration Runtime**  
*Engineered for Single-Node Resource-Constrained Hardware (4 GB RAM ThinkPad)*

- **Hardware-Constrained Design:** Built to run isolated developer services within a physical 4 GB memory ceiling on Ubuntu Server.
- **Automated Resource Provisioning:** Built a FastAPI management service interfacing directly with the Docker Engine API to provision isolated PostgreSQL databases and MinIO object storage buckets per project.
- **Security & Authorization:** Implements granular API key generation, project scoping, and role-based endpoint authorization.
- **Stack:** Python, FastAPI, Docker Engine API, PostgreSQL, MinIO, Linux, Bash

---

### [GiGly](https://github.com/sharancode3/GiGly)
**Gig-Economy Worker Safety Companion & Algorithmic Pay Fairness Analyzer**  
*Built for the Synaptrix Hackathon at BMSCE*

- **Algorithmic Pay Transparency:** Computes real-time earning rates against active shift durations to detect payout discrepancies.
- **Low-Overhead Native Telemetry:** Implemented a custom native C++ and Kotlin bridge communicating over Flutter platform channels to maintain persistent GPS telemetry and safety beacons while minimizing battery consumption during multi-hour delivery shifts.
- **Local AI Verification:** Integrates on-device Gemma 3 4B via Ollama for offline-accessible shift insights and emergency workflows.
- **Stack:** Flutter, Dart, Python, FastAPI, Firebase, Ollama, Kotlin, C++

---

### [Hireflow](https://github.com/sharancode3/Hireflow)
**Production Enterprise Hiring Platform, Role-Based ATS & Resume Engine**  
*Public Deployment: [hireflow-frontend-wvf2.vercel.app](https://hireflow-frontend-wvf2.vercel.app/login)*

- **Transactional Workflow Automation:** Provides multi-role portal pipelines (Job Seeker, Recruiter, Admin) with state-machine-driven candidate evaluation stages.
- **Database Architecture:** Backed by PostgreSQL with custom PL/pgSQL stored procedures for relational integrity, coupled with Prisma ORM migrations and Next.js frontend state machines.
- **ATS Compilation:** Automated structured resume generation and candidate profile export pipelines.
- **Stack:** TypeScript, Next.js, PostgreSQL, PL/pgSQL, Prisma ORM, Express.js, Tailwind CSS

---

### [Skill-Lens AI](https://github.com/sharancode3/Skill-lens-AI)
**Adaptive Technical Interview Simulation & Structured Taxonomy Extraction Platform**  
*Built for ABTalks Vibe Code Hackathon*

- **Constrained Semantic Extraction:** Ingests candidate technical artifacts and transforms them into multidimensional skill graphs using Google Gemini structured JSON Schema outputs.
- **Adaptive Evaluation Loop:** Dynamically calibrates question difficulty across multiple modalities (conceptual, architectural, and analytical coding assessments) based on previous turn responses.
- **Stack:** JavaScript, Node.js, Express.js, Google Gemini API, Python

---

### [Hydra Leaf](https://github.com/sharancode3/Hydra-leaf-Source-code)
**Hardware Gyroscope Sensor Fusion Mobile Physics Game Engine**  
*Releases: [Source Code](https://github.com/sharancode3/Hydra-leaf-Source-code) | [Signed Release APK](https://github.com/sharancode3/Hydra-leaf-apk)*

- **Hardware Sensor Fusion:** Real-time Android gyroscope telemetry integration utilizing low-pass filtering for responsive motion control.
- **Collision Mathematics:** Custom 2D particle and obstacle collision detection engine built natively in Java and Kotlin.
- **Stack:** Java, Kotlin, C, Android Native Sensor API, Gradle

---

## Technical Projects Index

| Project | Primary Domain | Core Stack | Repository Link |
| :--- | :--- | :--- | :--- |
| **Finora** | AI Finance Controller & 3-Way Reconciliation | TypeScript, Python, Next.js, Ollama, Firestore | [github.com/sharancode3/Finora](https://github.com/sharancode3/Finora) |
| **JobSwipe** | Mobile Internship Discovery Client (1st Place Hackathon Win) | Flutter, Dart, Riverpod, Supabase, Android SDK | [github.com/sharancode3/JobSwipe](https://github.com/sharancode3/JobSwipe) |
| **ThermoTrace AI** | Satellite Thermal & Geospatial Hotspot Monitoring (SIH 2026) | Python, FastAPI, TypeScript, GDAL, Docker | [github.com/sharancode3/ThermoTrace-AI](https://github.com/sharancode3/ThermoTrace-AI) |
| **Homelab BaaS** | Self-Hosted 4GB Edge Developer Platform & Orchestrator | Python, FastAPI, Docker Engine API, MinIO, Linux | [github.com/sharancode3/Homelab](https://github.com/sharancode3/Homelab) |
| **GiGly** | Worker Pay Fairness & Low-Overhead Native Telemetry | Flutter, Dart, Python, Firebase, Kotlin, C++ | [github.com/sharancode3/GiGly](https://github.com/sharancode3/GiGly) |
| **Hireflow** | Enterprise ATS, Role-Based Workflows & Resume Engine | TypeScript, Next.js, PostgreSQL, Prisma, PL/pgSQL | [github.com/sharancode3/Hireflow](https://github.com/sharancode3/Hireflow) |
| **Skill-Lens AI** | Adaptive Multi-Turn AI Technical Interview Platform | JavaScript, Node.js, Google Gemini API, Python | [github.com/sharancode3/Skill-lens-AI](https://github.com/sharancode3/Skill-lens-AI) |
| **Hydra Leaf** | Hardware Sensor Fusion Android Physics Game Engine | Java, Kotlin, C, Android Native Sensor API | [github.com/sharancode3/Hydra-leaf-Source-code](https://github.com/sharancode3/Hydra-leaf-Source-code) |
| **CHEAT-LABZ** | Browser Gaming Platform with Canvas Physics & Socket.IO | JavaScript, HTML5 Canvas, Socket.IO, CSS3 | [github.com/sharancode3/CHEAT-LABZ](https://github.com/sharancode3/CHEAT-LABZ) |
| **Hyper-Pong** | Canvas Collision Loop & Dynamic Game Physics Engine | JavaScript, HTML5 Canvas, CSS3 | [github.com/sharancode3/Hyper-Pong](https://github.com/sharancode3/Hyper-Pong) |

---

## Currently Building

Developing offline-first state synchronization patterns, verifiable local LLM evaluation loops, and edge container orchestration runtimes.

---

## Contact

- **GitHub:** [github.com/sharancode3](https://github.com/sharancode3)
- **LinkedIn:** [linkedin.com/in/sharan-s7](https://www.linkedin.com/in/sharan-s7/)
- **Instagram:** [instagram.com/sharns7_](https://www.instagram.com/sharns7_/)
- **Email:** [sharan18x@gmail.com](mailto:sharan18x@gmail.com)
- **Location:** Bengaluru, India
