# Sharan S

Computer Science undergraduate at BMS College of Engineering, Bengaluru (2024–2028). Engineering focus on local LLM orchestration, edge backend systems, and cross-platform mobile applications.

---

## About

I build systems across the stack, focusing on deterministic backend logic, on-device AI integration via Ollama, and mobile clients using Flutter and native Android. My work includes building mobile features at InternLoom, prototyping full-stack applications at Homi, and developing systems for hackathons in finance, developer tooling, and geospatial telemetry. I prioritize verifiable logic, constrained-hardware efficiency, and offline-first workflows over third-party API dependencies.

---

## Technical Skills

- **Languages:** Python, TypeScript, JavaScript, Dart, Kotlin, C, C++, SQL (PL/pgSQL), Bash
- **Mobile Development:** Flutter, Riverpod, Isar, Android SDK, Jetpack Compose, Native Platform Channels (C++/Kotlin)
- **AI & Local Inference:** Ollama (Gemma 3, Qwen 2.5), Structured Output (JSON Schema Mode), Tool Calling, Verifier Agent Architectures, Monte Carlo Simulations, GDAL
- **Backend & Infrastructure:** FastAPI, Node.js, Express.js, Prisma ORM, PostgreSQL, Supabase, Cloud Firestore, MinIO, Docker Engine API, Linux (Ubuntu Server)
- **DevOps & Tooling:** Docker, Docker Compose, Git, GitHub Actions, Vercel, Netlify

---

## Featured Projects

### [Finora](https://github.com/sharancode3/Finora)
A reconciliation platform built for the Razorpay AI Buildathon (AI Finance Controller track). It pairs a deterministic 3-way matching engine across bank statements, internal registers, and GSTR-2B data with a local Gemma 3 4B model running on Ollama. To prevent hallucinations during financial queries, the backend uses a dedicated Verifier class that extracts numeric values from the draft answer and validates them against tool execution outputs before allowing state updates or UI dispatch.

**Stack:** Python, FastAPI, TypeScript, Next.js, Ollama, Cloud Firestore

---

### [JobSwipe](https://github.com/sharancode3/JobSwipe)
A mobile internship discovery application built for the BMSCE x InternLoom Hackathon 2026 (App Development Track). The app implements a gesture-driven swipe interface for listing and filtering internship roles, with local state managed through Riverpod, resume file uploads, and persistent profile caching. Shipped as a signed Android APK release (v2.0.1).

**Stack:** Flutter, Dart, Riverpod, Supabase, Android SDK

---

### [Homelab BaaS](https://github.com/sharancode3/Homelab)
A personal Backend-as-a-Service and container orchestration platform engineered to run on a repurposed ThinkPad with 4 GB of RAM running Ubuntu Server. The system features a FastAPI authentication and project management service that communicates directly with the Docker Engine API to provision isolated PostgreSQL databases and MinIO object storage buckets per project.

**Stack:** Python, FastAPI, Docker Engine API, PostgreSQL, MinIO, Bash

---

### [ThermoTrace AI](https://github.com/sharancode3/ThermoTrace-AI)
An industrial flaring and thermal anomaly detection platform developed for Smart India Hackathon 2026 (Problem Statement 162 for NTRO and CPCB). The backend ingests satellite thermal band data, runs spatial clustering to locate potential flaring hotspots, and structures compliance summaries via a FastAPI service orchestrated through Docker Compose.

**Stack:** Python, FastAPI, TypeScript, GDAL, Vector Maps, Docker Compose

---

### [GiGly](https://github.com/sharancode3/GiGly)
A companion app for gig-economy delivery workers developed for the Synaptrix Hackathon at BMSCE. It provides automated pay transparency calculations against shift duration and dynamic safety telemetry. The mobile client integrates a native Android background service via C++ and Kotlin platform channels to maintain GPS tracking while minimizing battery consumption during multi-hour shifts.

**Stack:** Flutter, Dart, Python, FastAPI, Firebase, Ollama (Gemma 3 4B), Kotlin, C++

---

### [Hireflow](https://github.com/sharancode3/Hireflow)
A multi-role hiring portal supporting job seeker applications, recruiter review pipelines, and administrator controls. Built with Next.js and TypeScript, the data layer utilizes Prisma ORM backed by PostgreSQL with custom PL/pgSQL stored procedures for application state transitions and automated ATS resume compilation. Deployed live on Vercel.

**Stack:** TypeScript, Next.js, PostgreSQL, PL/pgSQL, Prisma ORM, Express.js, Tailwind CSS  
**Live Demo:** [hireflow-frontend-wvf2.vercel.app](https://hireflow-frontend-wvf2.vercel.app/login)

---

## Other Repositories

| Project | Domain | Stack | Repository |
| :--- | :--- | :--- | :--- |
| **Skill-Lens AI** | Adaptive technical interview simulation platform | JavaScript, Node.js, Google Gemini API, Python | [Link](https://github.com/sharancode3/Skill-lens-AI) |
| **Hydra Leaf** | Android river game with gyroscope hardware controls | Java, Kotlin, C, Android Native Sensor API | [Link](https://github.com/sharancode3/Hydra-leaf-Source-code) |
| **CHEAT-LABZ** | Browser gaming platform with canvas physics and Socket.IO | JavaScript, HTML5 Canvas, Socket.IO, CSS3 | [Link](https://github.com/sharancode3/CHEAT-LABZ) |
| **Hyper-Pong** | Canvas collision loop and game physics prototype | JavaScript, HTML5 Canvas, CSS3 | [Link](https://github.com/sharancode3/Hyper-Pong) |
| **SmartTrip AI** | Conversational travel route planning prototype | HTML5, JavaScript, CSS3 | [Link](https://github.com/sharancode3/SmartTrip-AI-Basic-design-Prototype) |

---

## Currently Building

Offline-first synchronization patterns, local LLM evaluation harnesses, and edge container orchestration runtimes.

---

## Contact

- **GitHub:** [github.com/sharancode3](https://github.com/sharancode3)
- **LinkedIn:** [linkedin.com/in/sharan-s7](https://www.linkedin.com/in/sharan-s7/)
- **Instagram:** [instagram.com/sharns7_](https://www.instagram.com/sharns7_/)
- **Email:** [sharan18x@gmail.com](mailto:sharan18x@gmail.com)
- **Location:** Bengaluru, India
