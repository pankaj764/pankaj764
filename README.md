<div align="center">

# Hey, I'm Pankaj 👋
### **Forward Deployed Engineer · AI Solutions · Full-Stack Systems**

*I build software that connects AI, business workflows, and production systems.*

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/pankaj-842b00230)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:leecory121@gmail.com)
[![Location](https://img.shields.io/badge/Pune%2C%20India-1E293B?style=for-the-badge&logo=google-maps&logoColor=white)](#)
[![Company](https://img.shields.io/badge/SuperGaming-FF4500?style=for-the-badge&logo=google-play&logoColor=white)](https://www.supergaming.com/)

</div>

---

### 📌 About Me

I am a **Forward Deployed Engineer** with a passion for architecting and deploying end-to-end technology solutions. My experience spans LLM-powered applications, distributed backend architectures, full-stack platforms, high-throughput gaming ecosystems, and custom e-commerce infrastructure.

I specialize in taking products from an operational bottleneck to a resilient, production-ready system — handling everything from technical discovery and systems design to hands-on implementation, cloud deployment, and continuous performance iteration. Aside from large-scale enterprise titles, I take pride in building projects **solo end-to-end**: from initial product design and responsive UI/UX to system architecture, database modeling, backend APIs, third-party integrations, and cloud infrastructure.

- 💼 **Current Role:** Community Tech Specialist at **[SuperGaming](https://www.supergaming.com/)**
- 📍 **Location:** Pune, India
- 📧 **Direct Contact:** [leecory121@gmail.com](mailto:leecory121@gmail.com)
- 🔗 **Professional Profile:** [LinkedIn](https://linkedin.com/in/pankaj-842b00230)

---

### 🚀 What I Work On

- 🤖 **AI & LLM Solutions:** Production-grade RAG pipelines, semantic embeddings, vector databases, tool-enabled AI agents, and Model Context Protocol (MCP) integrations.
- ⚡ **Full-Stack Development:** Responsive, scalable applications built with Next.js, React, Node.js, and TypeScript/Python.
- 🛠️ **Backend Systems & Microservices:** Resilient REST APIs, RBAC authentication, PostgreSQL data modeling, Redis caching & message queues, and webhook processing.
- ☁️ **Cloud Infrastructure & DevOps:** Azure Linux VM deployments, Docker container orchestration, CI/CD automation, PM2 process management, and scheduled worker jobs.
- 💡 **Product & Systems Engineering:** Bridging complex business operations with scalable software, automation workflows, and internal tooling.

---

### 🛠️ Tech Stack

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Languages** | C#, Python, TypeScript, JavaScript, SQL, HTML5, CSS3 |
| **Backend & Runtimes** | .NET 10 / ASP.NET Core, Node.js, NestJS, FastAPI, Django, Express.js, RESTful APIs |
| **AI / LLMs** | OpenAI API, Anthropic Claude, Google Gemini, LangChain, RAG Pipelines, Vector Search, AI Agents, MCP |
| **Frontend** | Next.js, React, Tailwind CSS, Responsive Web Design |
| **Databases & Search** | MongoDB, PostgreSQL, Elasticsearch 8, Supabase, Prisma ORM, MikroORM |
| **Caching, Queues & Workers** | Redis (StackExchange.Redis), BullMQ, Quartz.NET, Distributed Locks |
| **Gaming & Real-Time** | SignalR, Photon Fusion, Google Play Billing, Apple StoreKit, XSolla |
| **Cloud & DevOps** | Microsoft Azure, Docker & Docker Compose, Vercel, Railway, Linux, PM2, GitHub Actions, Nginx, Prometheus, OpenTelemetry |
| **E-Commerce & Payments** | Medusa.js, PhonePe, Razorpay, CCAvenue, PayU, Juspay, Stripe |
| **Logistics & Messaging** | Shiprocket API, Nodemailer (SMTP), BytePaper / AiSensy WhatsApp API |

---

### 📈 Proven Impact & Outcomes

<div align="center">

| Metric | Achievement |
| :---: | :---: |
| 👥 **100,000+** | Webshop User Signups |
| 🎯 **13.72%** | Signup-to-Paying Conversion Rate |
| 📈 **45%** | Total Game Revenue Driven via Webshop |
| 🌐 **1 Million+** | Community Members Supported through Operational Workflows |

</div>

---

### 💻 Featured Projects

> 💡 **Solo Engineering Highlight:** Aside from the enterprise-scale **Indus Battle Royale** backend platform, all projects below were designed and engineered **100% solo end-to-end** — owning system architecture, database modeling, RESTful APIs, product design, responsive UI/UX, and cloud deployments.

#### 🤖 SuperX Support — AI-Powered Player Support
*`Solo Project` · System Architecture · AI Agents & RAG Pipeline · UI Design · Cloud Deployment*
- AI-assisted player support infrastructure integrating LLM intelligence into real-time live gaming support operations.
- **Core Architecture:** Retrieval-Augmented Generation (RAG) with vector embeddings for instant knowledge retrieval.
- **Autonomous Agents:** Tool-calling AI agents for looking up player records, account states, and FAQ troubleshooting.
- **Integrations:** Direct API integrations bridging support desks with internal game service databases.

---

#### 🎮 Indus Battle Royale — Distributed Game Backend & LiveOps Platform
*`Enterprise Platform` · Scalable Multiplayer Game Backend & LiveOps Infrastructure (SuperGaming)*

- **Architecture & Runtime:** Engineered with **.NET 10 / ASP.NET Core** and **C#**, organized around Clean Architecture and CQRS patterns across independently deployable containerized services.
- **Primary Data & Caching Tier:** **MongoDB** (primary domain store), **Redis** (caching, pub/sub event bus, and cluster-wide distributed locks), and **Elasticsearch 8** (high-throughput full-text player discovery).
- **Core Microservices & Background Workers:**
  - **Core Client API:** High-throughput API powering player accounts, social authentication (Google, Apple, Play Store), inventory, gacha loot-box probabilistic systems, progressions, friend systems, and match history.
  - **Configuration Scheduler Worker:** Background worker utilizing **Quartz.NET** and Redis pub/sub for scheduled, zero-downtime game configuration rollouts (weapons, drop tables, avatar stats, and seasonal events).
  - **Leaderboard Snapshot Worker:** High-performance cron service periodically snapshotting Redis sorted sets into cached, ranked global and regional player standings.
  - **Automated Refund & Fraud Reconciliation Worker:** Background engine polling Google Play's `voidedpurchases` API and executing state reversal strategies (`revert`, `modify`, `save-copy`) to maintain game-economy balance.
- **Custom Dynamic Rules Engine (DSL):**
  - Engineered a custom Domain-Specific Language (lexer, parser, AST visitor evaluator) to evaluate dynamic game rules, reward modifiers, and personalized offer conditions at runtime without client/server redeployments.
- **In-App Commerce & Entitlements:**
  - Multi-platform payment verification covering **Google Play Billing, Apple App Store, XSolla (store & webshop), and Razorpay**.
  - Cluster-wide Redis distributed locks preventing race conditions in currency consumption, gacha pulls, and promotional code redemptions.
- **LiveOps & Admin Operations Platform:**
  - Administrative microservices and UI for player management, economy adjustments, custom room lobbies, live battle royale match telemetry, and tournament match result broadcasts.
  - Real-time client updates orchestrated through **SignalR** and inbound webhook pipelines for **Photon Fusion** and **XSolla**.
- **Observability & Telemetry:**
  - Prometheus `/metrics` exporters for request rates and database connection pools, paired with OpenTelemetry OTLP distributed tracing.

---

#### 🎮 SuperX Hub — Gaming Platform & Player Ecosystem
*`Solo Project` · Product & UI/UX Design · Full-Stack Platform Architecture · Game API Integrations · LiveOps*
- An integrated platform unifying player engagement, digital commerce, creator monetization, and live tournament management.
- **Unified Authentication:** Single sign-on across player web accounts and game server APIs.
- **Creator Economy:** Creator storefronts, real-time commission tracking, and earnings payout dashboards.
- **Live Operations:** Dynamic webstore, memberships, digital item synchronization, and live tournament leaderboards with automated prize distribution.

---

#### 🛒 Pasupati / Savikalpa — Headless E-Commerce & Operations Infrastructure
*`Solo Project` · Complete Systems Architecture · Custom Backend & Workflows · Next.js Storefront & Admin UI · DevOps*

* **Live Deployment:** Production Storefront ([pasupatitailam.com](https://pasupatitailam.com/)) · Backend API ([shop.pasupatitailam.com](https://shop.pasupatitailam.com/))
* **Core Architecture:** Built with **Medusa v2.8.3** and **NestJS / Next.js**, running on **Node.js, TypeScript, PostgreSQL (Prisma & MikroORM), and Redis**.
* **Multi-Gateway Payment Infrastructure:**
  - Full lifecycle integration for Indian payment gateways: **PhonePe, Razorpay, CCAvenue, and PayU**.
  - Signature-verified webhooks, transaction reconciliation, payment state machines, and automated hosted-gateway refunds.
* **Indian GST Tax Engine:**
  - Custom tax provider calculating dual **CGST (2.5%) + SGST (2.5%)** for intra-state and **IGST** routing based on seller/delivery state codes, with tax-inclusive pricing.
* **Order Automation & Logistics Pipeline:**
  - Event-driven subscribers listening to `order.placed` and `shipment.created`.
  - **Shiprocket API** integration for automated adhoc shipment creation, AWB generation, pickup scheduling, and live tracking.
  - Automated PDF tax invoice generation (**React-PDF**, PDFKit) uploaded to S3-compatible cloud storage and attached to customer emails.
* **Lifecycle Messaging & Abandoned Cart Recovery:**
  - Multi-channel notification pipeline using **Nodemailer** (SMTP) and **BytePaper / AiSensy WhatsApp Business API** (order placement, tracking updates with CTA buttons, and payment failure notifications).
  - Staged abandoned-cart recovery automation at **12-hour, 48-hour, and 7-day** intervals.
* **Custom Admin Console & Merchandising:**
  - 30-day abandoned cart administration dashboard with real-time session diagnostics and item calculations.
  - Single-use coupon verification engine preventing duplicate redemptions via customer metadata tracking.
  - Injected admin widgets for storefront merchandising: dynamic carousels, health cures, FAQ builders, customer testimonials, and video playlists.
* **Cloud & Server Infrastructure:**
  - Multi-container **Docker Compose** release on Azure Linux VM reverse-proxied behind **Nginx** with SSL termination and BullMQ background workers.

---

#### 🏆 Tournament Management System
*`Solo Project` · Database Schema Design · Scoring Calculations Engine · Admin UI · Background Automation*
- High-concurrency esports tournament operations engine.
- Backed by PostgreSQL with optimized relational schemas for teams, invitations, and brackets.
- Automated scheduled scoring calculations, dynamic seedings, and live competitive leaderboards.

---

#### 📊 Game Administration & Automation Suite
*`Solo Project` · Internal Tooling Design · Operations Dashboard UI · Telemetry & Automation Workflows*
- Suite of internal operational tools, administrative dashboards, and telemetry workflows designed to support game masters and community managers across live game events and operational audits.

---

### 🧠 Currently Exploring & Deep Diving

- ⚡ **Lightweight & Specialized LLMs:** Deploying cost-effective, high-throughput SLMs / quantized open models for targeted enterprise tasks.
- 🧩 **Agentic Architectures & MCP:** Building tool-augmented autonomous agents leveraging the Model Context Protocol.
- 🔍 **Advanced Retrieval Systems:** Hybrid sparse/dense retrieval, re-ranking strategies, and chunking heuristics for domain-specific RAG.
- 🏗️ **Resilient Distributed Workflows:** Fault-tolerant event-driven architectures with BullMQ, Redis, and transactional outbox patterns.

---

### 🤝 Connect & Collaborate

I'm always interested in discussing **Forward Deployed Engineering**, **AI Solutions Architecture**, and **Full-Stack Product Systems**.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-pankaj--842b00230-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/pankaj-842b00230)
[![Email](https://img.shields.io/badge/Email-leecory121%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:leecory121@gmail.com)

*Building useful software, connecting systems, and solving real operational problems.*

</div>
