# Sharan S

Systems & Applied AI Engineer | Computer Science Undergraduate at BMSCE, Bengaluru (Batch 2024-2028)

---

## Summary

Computer Science undergraduate at BMS College of Engineering with an engineering focus on autonomous multi-agent orchestration, local LLM inference pipelines, resource-constrained edge platforms, and cross-platform mobile systems. Experience spans engineering mobile features at InternLoom, building full-stack products at Homi, and developing hackathon-winning solutions across fintech, geospatial intelligence, and developer tooling. All systems prioritize deterministic state machines, kernel-level isolation, and offline/on-device inference over superficial API wrappers.

---

## Technical Stack

- **Languages:** Python, TypeScript, JavaScript, Dart, Kotlin, C, C++, SQL (PL/pgSQL), Bash
- **Mobile Development:** Flutter, Riverpod, Isar, Android SDK, Jetpack Compose, Native C++/Kotlin Platform Channels
- **Applied AI & Inference:** Ollama (Gemma 3, Qwen 2.5), Structured Output (JSON Schema Mode), Tool Calling / Function Calling, Multi-Agent Verifier Loops, Monte Carlo Simulations, Geospatial Telemetry (GDAL)
- **Backend & Systems:** FastAPI, Node.js, Express.js, Prisma ORM, PostgreSQL, Cloud Firestore, Supabase, MinIO, Docker Engine API, Linux cgroups & Namespaces
- **DevOps & Infrastructure:** Docker, Docker Compose, Linux Server Administration, Git, GitHub Actions, Vercel, Netlify

---

## Featured Systems

### [Finora](https://github.com/sharancode3/Finora)
**Problem Statement:** Merchant-facing financial platforms lack automated, continuous reconciliation between bank statements, purchase ledgers, and government tax returns, resulting in undetected ledger drift.  
**Tech Stack:** TypeScript, Next.js, Python, FastAPI, Ollama (Gemma 3 4B), Cloud Firestore  
**Architecture & Contribution:** Engineered a deterministic 3-way matching engine coupled with a local LLM controller via Ollama. Implemented a dedicated dual-pass Verifier agent loop that inspects tool calls and ledger mutations to mathematically validate financial outputs and eliminate hallucinations prior to state changes. Integrated 1,000-trial Monte Carlo cash-flow forecasting.  
**Outcome:** Built as a targeted submission for the Razorpay AI Buildathon (AI Finance Controller Track).

---

### [JobSwipe](https://github.com/sharancode3/JobSwipe)
**Problem Statement:** Conventional internship boards create high friction with lengthy forms and poor mobile discovery UX for students.  
**Tech Stack:** Flutter, Dart, Riverpod, Supabase, Android SDK  
**Architecture & Contribution:** Architected a swipe-card discovery interface with optimistic UI updates, Riverpod state isolation, candidate profile caching, and a direct-apply pipeline integrated with Supabase authentication and relational schema.  
**Outcome:** Awarded 1st Place at the BMSCE x InternLoom Hackathon 2026 (App Development Track); released signed production Android APKs (v2.0.1).

---

### [ThermoTrace AI](https://github.com/sharancode3/ThermoTrace-AI)
**Problem Statement:** Monitoring industrial flaring compliance and sub-surface thermal anomalies requires continuous, sovereign geospatial intelligence from multispectral satellite telemetry.  
**Tech Stack:** Python, FastAPI, TypeScript, Geospatial AI, GDAL, Vector Maps, Docker Compose v2  
**Architecture & Contribution:** Designed an end-to-end ingestion pipeline processing thermal infrared satellite bands, computing spatial anomaly clusters, and generating deterministic compliance reports with LLM-synthesized executive summaries.  
**Outcome:** Engineered as a comprehensive platform architecture for Smart India Hackathon 2026 (Problem Statement 162 for NTRO & CPCB).

---

### [Homelab BaaS](https://github.com/sharancode3/Homelab)
**Problem Statement:** Cloud backend-as-a-service offerings are cost-prohibitive and memory-heavy for deployment on low-spec edge nodes.  
**Tech Stack:** Python, FastAPI, TypeScript, Docker Engine API, PostgreSQL, MinIO, Linux cgroups & Namespaces, Bash  
**Architecture & Contribution:** Designed a self-hosted multi-tenant developer platform from first principles to operate within a single-node 4 GB RAM edge environment (repurposed ThinkPad on Ubuntu Server). Implemented automated relational database provisioning, deterministic container lifecycle engine, S3-compatible local storage, and kernel-level tenant isolation.  
**Outcome:** Fully operational personal edge BaaS hosting self-contained isolated microservices and persistent databases.

---

### [GiGly](https://github.com/sharancode3/GiGly)
**Problem Statement:** Indian gig-economy workers face dynamic pay opacity, route safety vulnerabilities, and aggressive battery drain from continuous mobile location tracking.  
**Tech Stack:** Flutter, Dart, Python, FastAPI, Firebase, Ollama (Gemma 3 4B), Kotlin, C++ Native Bridge  
**Architecture & Contribution:** Built a cross-platform client with real-time algorithmic pay fairness auditing and proactive emergency safety beacons. Developed a low-overhead native C++/Kotlin bridge for continuous background GPS telemetry with zero-drain battery performance during active delivery shifts.  
**Outcome:** Developed for the Synaptrix Hackathon at BMSCE, covering all core and bonus platform requirements.

---

### [Hireflow](https://github.com/sharancode3/Hireflow)
**Problem Statement:** Recruitment workflows suffer from fragmented ATS pipelines, lack of structured recruiter approvals, and inconsistent candidate resume formatting.  
**Tech Stack:** TypeScript, Next.js, PostgreSQL, PL/pgSQL, Prisma ORM, Express.js, Tailwind CSS  
**Architecture & Contribution:** Engineered a multi-role hiring platform (Job Seeker, Recruiter, Admin) with candidate approval state machines, automated ATS resume generation, and transactional database routines using PL/pgSQL stored procedures.  
**Outcome:** Shipped a production-grade 1.2MB+ TypeScript platform with a public deployment at [hireflow-frontend-wvf2.vercel.app](https://hireflow-frontend-wvf2.vercel.app/login).

---

## Project Catalog

| Project | Domain | Stack | Repository |
| :--- | :--- | :--- | :--- |
| **Finora** | Autonomous AI Finance Controller & 3-Way Reconciliation | TypeScript, Python, Next.js, Ollama, Firestore | [github.com/sharancode3/Finora](https://github.com/sharancode3/Finora) |
| **JobSwipe** | Swipe-Based Mobile Internship Discovery Application | Flutter, Dart, Riverpod, Supabase, Android | [github.com/sharancode3/JobSwipe](https://github.com/sharancode3/JobSwipe) |
| **ThermoTrace AI** | Satellite Thermal & Geospatial Intelligence (SIH 2026) | Python, FastAPI, TypeScript, GDAL, Docker | [github.com/sharancode3/ThermoTrace-AI](https://github.com/sharancode3/ThermoTrace-AI) |
| **Homelab BaaS** | Single-Node 4GB Edge Developer Platform & Orchestrator | Python, FastAPI, Docker Engine API, MinIO, Linux | [github.com/sharancode3/Homelab](https://github.com/sharancode3/Homelab) |
| **GiGly** | Pay Fairness & Safety Companion with Native Telemetry | Flutter, Dart, Python, Firebase, Kotlin, C++ | [github.com/sharancode3/GiGly](https://github.com/sharancode3/GiGly) |
| **Hireflow** | Enterprise ATS, Role-Based Workflows & Resume Generator | TypeScript, Next.js, PostgreSQL, Prisma, PL/pgSQL | [github.com/sharancode3/Hireflow](https://github.com/sharancode3/Hireflow) |
| **Skill-Lens AI** | Adaptive Multi-Turn AI Technical Interview Platform | JavaScript, Node.js, Google Gemini API, Python | [github.com/sharancode3/Skill-lens-AI](https://github.com/sharancode3/Skill-lens-AI) |
| **Hydra Leaf** | Hardware Sensor Fusion Android Physics Game Engine | Java, Kotlin, C, Android Native Sensor API | [github.com/sharancode3/Hydra-leaf-Source-code](https://github.com/sharancode3/Hydra-leaf-Source-code) |
| **CHEAT-LABZ** | Modular Canvas 2D Physics & Browser Game Platform | JavaScript, HTML5 Canvas, Socket.IO, CSS3 | [github.com/sharancode3/CHEAT-LABZ](https://github.com/sharancode3/CHEAT-LABZ) |
| **Hyper-Pong** | Canvas Collision Loop & Dynamic Game Physics Engine | JavaScript, HTML5 Canvas, CSS3 | [github.com/sharancode3/Hyper-Pong](https://github.com/sharancode3/Hyper-Pong) |
| **SmartTrip AI** | Conversational Travel Planning & Route Prototype | HTML5, JavaScript, CSS3 | [github.com/sharancode3/SmartTrip-AI-Basic-design-Prototype](https://github.com/sharancode3/SmartTrip-AI-Basic-design-Prototype) |

---

## Currently Building

Developing scalable offline-first architectures, edge platform runtimes, and verifiable multi-agent orchestration frameworks for constrained deployment environments.

---

## Contact

- **GitHub:** [github.com/sharancode3](https://github.com/sharancode3)
- **LinkedIn:** [linkedin.com/in/sharan-s7](https://www.linkedin.com/in/sharan-s7/)
- **Instagram:** [instagram.com/sharns7_](https://www.instagram.com/sharns7_/)
- **Email:** [sharan18x@gmail.com](mailto:sharan18x@gmail.com)
- **Location:** Bengaluru, India
