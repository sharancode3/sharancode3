# Sharan S

**Systems & Applied AI Engineer**  
Computer Science Undergraduate, BMS College of Engineering, Bengaluru (Batch 2024–2028 | 8.52 CGPA)  
App Development Intern at InternLoom

**Interactive Portfolio:** [portfolio-xi-five-94ye2hygga.vercel.app](https://portfolio-xi-five-94ye2hygga.vercel.app/)  
[GitHub](https://github.com/sharancode3) | [LinkedIn](https://www.linkedin.com/in/sharan-s7/) | [Instagram](https://www.instagram.com/sharans7_/) | [Email](mailto:sharan18x@gmail.com) | Bengaluru, India

---

## Engineering Overview

Systems and Applied AI engineer pursuing Computer Science at BMS College of Engineering. Focused on self-hosted edge infrastructure, local-first privacy-preserving AI runtimes, deterministic backend services, and high-performance cross-platform mobile systems. Experience includes engineering mobile feature pipelines and role-based access control at InternLoom, building full-stack products at Homi, and leading teams to multiple first-place hackathon finishes across enterprise decision intelligence, fintech, and remote sensing.

All systems prioritize verifiable execution, physical resource constraints, and edge/on-device inference over third-party cloud API dependencies.

---

## Verified Track Record & Recognitions

- **1st Place Winner** — Build Bengaluru Hackathon (held at Microsoft Office, Track 1: Human Resources) with **WorkSense**, an enterprise workforce decision platform backed by Kahn’s DAG scheduling and 159 automated tests.
- **1st Place Winner** — BMSCE × InternLoom Hackathon (App Development Track) with **JobSwipe**, an offline-first gesture-driven discovery app; directly earned a 3-month App Development Internship at InternLoom.
- **SIH 2026 Internal Qualifier & Submissions** — Qualified in the top 45 teams at BMSCE for Smart India Hackathon 2026 with **ThermoTrace AI** (Problem Statement 26162 for NTRO/CPCB) and **TunnelTrace AI** (Problem Statement 26160 for NTRO).
- **Hackathon Finalist** — *Agents That Act* by TrueFoundry × Polaris (with **RunSafe**, autonomous runbook executor), *Code Canvas* at Medicaps University (with **Hireflow**), and *Browser Battle* at BMSCE (with **Campus Insights**).

---

## Core Technical Stack

- **Languages:** Python, TypeScript, JavaScript, Dart, Kotlin, C, C++, SQL (PL/pgSQL), Bash
- **Frameworks & Runtimes:** FastAPI, React, Next.js, Node.js, Express.js, Flutter, Android SDK
- **Applied AI & Systems:** Ollama (Gemma 3, Qwen 2.5), Structured Output (JSON Schema Mode), Tool/Function Calling, On-Device Whisper (ONNX WASM), GDAL
- **Databases & Infrastructure:** PostgreSQL, Supabase, SQLite (WAL Mode), Docker, MinIO, Linux (Ubuntu Server)

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
- **Offline Document Intelligence:** In-browser speech-to-text pipeline powered by ONNX WASM running Whisper transcription, coupled with WebCrypto AES-GCM-256 client-side encryption.
- **Stack:** Python, FastAPI, TypeScript, Next.js, Ollama, Vector Search, WebCrypto, Local Storage

---

### [ThermoTrace AI](https://github.com/sharancode3/ThermoTrace-AI)
**Satellite Thermal Intelligence & Industrial Flaring Anomaly Monitoring Platform**  
*Smart India Hackathon 2026 Submission (NTRO & CPCB) | Live Deployment: [thermo-trace-ai.vercel.app](https://thermo-trace-ai.vercel.app/)*

- **Multispectral Telemetry Processing:** Ingests satellite thermal infrared imagery (NASA VIIRS & MODIS) to locate persistent industrial flaring hotspots and subsurface thermal anomalies.
- **Spatial Anomaly Pipeline:** Computes spatio-temporal event clustering using ST-DBSCAN and GDAL vector coordinate transformations.
- **Instance-Level Model Attribution:** Calibrated XGBoost classifier backed by TreeSHAP game-theoretic Shapley attributions, enabling environmental inspectors to audit anomaly criteria.
- **Stack:** Python, FastAPI, TypeScript, Geospatial AI, GDAL, Vector Maps, Docker Compose

---

### [Hireflow](https://github.com/sharancode3/Hireflow)
**Production Enterprise Hiring Platform, Role-Based ATS & Resume Engine**  
*Code Canvas Hackathon Finalist | Live Deployment: [hireflow-frontend-ten.vercel.app](https://hireflow-frontend-ten.vercel.app/)*

- **Transactional Workflow Automation:** Multi-role portal pipelines (Job Seeker, Recruiter, Admin) with state-machine-driven candidate evaluation stages.
- **Database Architecture:** Backed by PostgreSQL with custom PL/pgSQL stored procedures for relational integrity, coupled with Prisma ORM migrations and Next.js frontend state machines.
- **ATS Compilation:** Client-side ATS resume match scoring against target job descriptions and keyword densities.
- **Stack:** React 19, TypeScript, Next.js, PostgreSQL, PL/pgSQL, Prisma ORM, Express.js, Tailwind CSS

---

### [Hydra Leaf](https://github.com/sharancode3/Hydra-leaf-Source-code)
**Hardware Gyroscope Sensor Fusion Mobile Physics Game Engine**  
*Releases: [Source Code](https://github.com/sharancode3/Hydra-leaf-Source-code) | [Signed Release APK (v1.5.1 / v5.1)](https://github.com/sharancode3/Hydra-leaf-apk/releases/latest)*

- **Hardware Sensor Fusion:** Real-time Android gyroscope telemetry integration utilizing low-pass filtering on acceleration vectors to eliminate hand tremors while preserving responsive motion control.
- **Collision Mathematics & Optimization:** Custom 2D particle and obstacle collision detection engine built natively in Java and Kotlin, continuously optimized over 5 major release cycles to reduce APK footprint from 50 MB to under 15 MB.
- **Stack:** Kotlin, Java, Jetpack Compose, Android Native Sensor API, Gradle

---

### [Finora](https://github.com/sharancode3/Finora)
**Autonomous AI Finance Controller & Continuous Reconciliation Platform**  
*Built for the Razorpay AI Buildathon (AI Finance Controller Track)*

- **Continuous 3-Way Matching Engine:** Automatically reconciles inconsistencies across banking feeds, internal purchase registers, and GSTR-2B datasets to detect ledger drift.
- **Dual-Pass Verification Gatekeeper:** Integrates a locally-hosted Gemma 3 4B model via Ollama. Implements a dedicated Verifier class that tokenizes and cross-checks all numeric values from draft model outputs against tool execution results before committing ledger mutations or triggering UI actions.
- **Stochastic Forecasting:** Integrates Monte Carlo cash-flow simulation routines to project liquidity trajectories under varying settlement timelines.
- **Stack:** Python, FastAPI, TypeScript, Next.js, Ollama, Cloud Firestore

---

## Systems Catalog & Hackathon Builds

| Project | Primary Domain | Core Stack | Live Demo / Repository |
| :--- | :--- | :--- | :--- |
| **WorkSense** | Workforce Decision Intelligence (1st Place Build Bengaluru) | React, TypeScript, FastAPI, Python, Supabase | [Live Demo](https://work-sense-tau.vercel.app/) / [Code](https://github.com/sharancode3/WorkSense) |
| **TunnelTrace AI** | IPsec VPN Security Intelligence Platform (SIH 2026 / NTRO) | Python, FastAPI, IPsec Telemetry, Next.js | [Live Demo](https://tunneltraceai-7e6g.vercel.app/) / [Code](https://github.com/sharancode3/TunnelTrace-AI) |
| **RunSafe** | Verified Autonomous Runbook Executor (Agents That Act Finalist) | TrueForge, TypeScript, SQLite, Docker, Zod | [Repository](https://github.com/sharancode3/RunSafe) |
| **Skill Labs AI** | Adaptive Multi-Turn AI Technical Interview Platform | JavaScript, Node.js, Express, Gemini & Qwen | [Repository](https://github.com/sharancode3/Skill-lens-AI) |
| **GiGly** | Worker Pay Fairness & Low-Overhead Native Telemetry | Flutter, Dart, Python, Firebase, Kotlin, C++ | [Repository](https://github.com/sharancode3/GiGly) |
| **JobSwipe** | Mobile Internship Discovery Client (1st Place Hackathon Win) | Flutter, Dart, Riverpod, Supabase, Android SDK | [Repository](https://github.com/sharancode3/JobSwipe) |
| **CHEAT-LABZ** | Browser Gaming Platform with Canvas Physics & Socket.IO | JavaScript, HTML5 Canvas, Socket.IO, CSS3 | [Live Arcade](https://sharancode3.github.io/CHEAT-LABZ/) / [Code](https://github.com/sharancode3/CHEAT-LABZ) |
| **Campus Insights** | WebGL Three.js University Portal (Browser Battle Finalist) | Next.js, TypeScript, Three.js, WebGL Shaders | [Live Portal](https://sharancode3.github.io/Campus-Insights/) |
| **Hyper-Pong** | Canvas Collision Loop & Dynamic Game Physics Engine | JavaScript, HTML5 Canvas, CSS3 | [Repository](https://github.com/sharancode3/Hyper-Pong) |

---

## Currently Building

Developing offline-first state synchronization patterns, edge container orchestration runtimes, and local-first inference architectures.

---

## Contact

- **Portfolio:** [portfolio-xi-five-94ye2hygga.vercel.app](https://portfolio-xi-five-94ye2hygga.vercel.app/)
- **GitHub:** [github.com/sharancode3](https://github.com/sharancode3)
- **LinkedIn:** [linkedin.com/in/sharan-s7](https://www.linkedin.com/in/sharan-s7/)
- **Instagram:** [instagram.com/sharans7_](https://www.instagram.com/sharans7_/)
- **Email:** [sharan18x@gmail.com](mailto:sharan18x@gmail.com)
- **Location:** Bengaluru, India
