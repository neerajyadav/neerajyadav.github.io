# **Neeraj Kumar**

**Principal Architect / Founding Engineer | SaaS | Solana Blockchain | Cloud | Distributed Systems | Sustainability Tech**  
Gurgaon, India • [linkedin.com/in/neeraj-kosliya](https://linkedin.com/in/neeraj-kosliya)

---

## **SUMMARY**

- 14+ years building and scaling **SaaS platforms, distributed systems, and data-intensive products** across startups and enterprises.  
- Blend of **founding engineer / principal architect** experience: 0→1 product development, multi-tenant SaaS architecture, and leading cross-functional engineering teams.  
- Deep hands-on expertise in **Node.js, Go, microservices, Kubernetes, and event-driven systems** across **AWS, Azure, and GCP**.  
- Recent focus on **Solana blockchain trading and analytics**: Geyser indexers, Transaction and Instructions decoders, on-chain data pipelines, and ML-assisted trading engines.  
- Proven track record of **end-to-end ownership** — discovery, architecture, implementation, CI/CD, observability, and stakeholder alignment with business and product goals.

---

## **CORE STRENGTHS**

- 0→1 Product Development & Startup Execution  
- SaaS & Platform Architecture
- Cloud Infrastructure (AWS, Azure, GCP, Kubernetes)  
- Distributed Systems  
- Solana Blockchain Ecosystem
- Engineering Leadership 
- Sustainability Tech

---

## **TECHNICAL SKILLS**

**Languages:** TypeScript/JavaScript (Node.js), Go, C#, Dart  
**Blockchain:** Solana (Geyser Stream, Jito bundles, Raydium AMM/CPMM, pump.fun, Anchor decoding)  
**Cloud:** AWS (EKS, EC2, RDS, SQS, S3), Azure (Functions, Service Bus), GCP (Firestore, GKE)  
**Distributed Systems:** Microservices, gRPC, NATS JetStream, event-driven patterns  
**Databases:** PostgreSQL, ClickHouse, MongoDB, ArangoDB  
**DevOps:** Docker, Kubernetes, Helm, GitHub CI/CD, Skaffold, ArgoCD  
**Architecture:** SaaS, multi-tenancy, high-throughput ingestion systems  

---

## **RECENT BLOCKCHAIN & CRYPTO ENGINEERING(May 2025 – Present)**

### **Solana Token Trading Engine & Analytics Platform — Architect & Engineer**  
**Independent Product Builder | Crypto & AI Engineering**

- Built low-latency **Solana Geyser listener** in Go for real-time block/transactions ingestion.  
  - Designed ingestion pipeline using **Geyser Stream → NATS JetStream → ClickHouse/Postgres** with sub-second end-to-end latency.
  - Developed decoding pipeline with custom instructions/events decoders for mint, swap, pool creation and pool migration events for major solana programs like **pump.fun**, **pump-swap**, **Raydium AMM/CPMM**.  
- Developed **ML-assisted trading engine**:
  - Trained XGBoost model on historical on-chain data to predict short-term price movements of newly minted tokens.
  - Implemented feature engineering techniques to extract insights from on-chain mint event data, improving model accuracy.
  - Developed trading engine with features like Delayed Buy, Multiple Take Profits, trailing Stop-loss etc.
  - Optimised trading engine in Go for ultra-low latency execution which listens to geyser stream, decodes transactions, constructs price stream and executes trades on chain within milliseconds.
- Leveraged **AI-assisted coding** tools (GitHub Copilot, Claude Code, ChatGPT Codex) to increase development throughput by ~5x.

---

## **EXPERIENCE**

### **Principal Architect — Emission Critical Pvt. Ltd.**  
**Jul 2022 – May 2025 | Gurgaon, India**

- Architected and developed a **multi-tenant ESG/PCF SaaS platform** on **AWS EKS** and **Aurora Postgres** enabling large enterprise customers to capture/model supply chain emissions and ESG reporting.   
- Designed **Integration and ETL workflows** using **Airbyte**, **NATS JetStream** and **Postgres** for loading and transforming activity data to sustainability reports.  
- Translated complex **carbon accounting and ESG models** into intuitive digital workflows, improving adoption and data quality for clients.   
- Owned **system design, cloud architecture, performance, reliability, and security posture** of the platform.

---

### **Head of Technology — Poker Sports League (Hashtag Poker)**  
**Aug 2020 – Jun 2022 | Gurgaon, India**

- Joined as founding technology leader; **built the entire engineering team from scratch** (11 members across backend, mobile, web, QA).  
- Architected and delivered the **Hashtag Poker** platform — Flutter mobile apps, Node.js microservices, and **Kubernetes + NATS + PostgreSQL** backend.  
- Integrated **real-time game logic, payments, and event-driven microservices**, scaling to thousands of concurrent users.  
- Established **CI/CD, monitoring, and operational runbooks**, significantly improving release frequency and platform stability.

---

### **Engineering Manager & Co-Founder — Mu Software Solutions Pvt. Ltd.**  
**2014 – 2017, 2018 – 2020 | Gurgaon, India**

- Co-founded a technology services and product studio delivering **end-to-end product development** for startups and mid-sized enterprises.  
- Helped multiple founders go from **idea → MVP → early traction**, emphasizing fast validation and real user feedback.  
- Led architecture and development of **cloud-native products** using **Node.js (NestJS)**, **.NET Core**, **Flutter**, **Azure** and **GCP**.  
- Built and managed engineering teams (0→25), owning **requirement analysis, architecture, execution, delivery, and client communication**.  

---

### **Consultant (Microsoft India — HP Inc.) — Data Glove IT Solutions**  
**2017 – 2018 | Bangalore, India**

- Automated **Azure analytics pipelines** for **HP Inc.**, improving speed and reliability of complex data operations.  
- Implemented scripts and workflows using **ADLA, ADLS, ADF, Logic Apps, Automation Runbooks**, reducing manual interventions by ~60%.  

---

### **Senior Software Engineer — PS Intelegencia Analytics Pvt. Ltd.**  
**2012 – 2014 | India**

- Built modern web and mobile applications using **.NET MVC**, **Entity Framework**, and related technologies.  
- Owned end-to-end delivery from requirement discovery and design to deployment and stabilization.  

---

### **Software Engineer — Elixir Computech Pvt. Ltd.**  
**2010 – 2012 | India**

- Developed **enterprise automation solutions** using **ASP.NET**, JavaScript, and SQL Server.  
- Collaborated directly with clients to translate business needs into scalable technical designs.  

---

## **PROJECTS**

### **Crypto Meme-Coin Trading Bot (Solana)**
High performance trading bot with ultra-low latency for newly minted Solana tokens. Trade based on XGBoost model predictions and on-chain signals and execute sell strategies like multiple take-profits and trailing stop-loss by continuously monitoring token price movements.

- Designed a custom **Go-based trading engine** using **Solana Geyser Streams** for ultra-fast execution and real-time mint detection.  
- Integrated **developer-buy tracking, liquidity pool intelligence, wallet metrics, and early-signal analytics** to drive trading decisions.

### **Product Carbon Footprint (PCF) SaaS Platform**
SOC2 certified multi-tenant SaaS platform for enterprise sustainability management, enabling organizations to measure, report, and reduce their carbon footprint and ESG impact.

- Implemented multi-tenant architecture with RBAC + ABAC access control, data isolation, and compliance features.
  - Used OpenFGA for fine-grained access control across tenants and user roles. OpenFGA is an open-source authorization system based on **Google Zanzibar**.
- Implemented a complex model to enable customers to create their process map and ingest activity data which in turn calculate product carbon footprints as per **GHG Standard**.
- **NestJs (NodeJs)** based microservices using NATS for inter-service communication and event-driven workflows.
- Created and maintained **EKS** Kubernetes cluster for hosting microservices and other workloads with **Helm/Kustomize** and **ArgoCD** for GitOps-based continuous deployment.
- Designed data ingestion pipelines using **Airbyte** to connect various data sources (S3, ERP, CRM, spreadsheets) to the platform.
- OpenTelemetry-based observability with distributed tracing, metrics, and logging using **SigNoz**.

### **Hashtag Poker Platform**
End-to-end poker learning and playing platform with cross-platform mobile apps, real-time game engine, and scalable backend infrastructure.

- Led full-stack development of **Flutter mobile apps** (iOS/Android) with shared business logic using MVVM architecture.  
- Built **Node.js microservices** for game logic, user management, payments, and notifications.  
- Deployed backend on **Kubernetes** with **NATS JetStream** for real-time messaging and **MongoDB** for data storage.
- Established CI/CD pipelines using **GitHub Actions** and implemented monitoring with **Prometheus** and **Grafana**.

### **Arkaa Digital Healthcare Platform**
A comprehensive digital healthcare platform for telemedicine, patient management, and health data analytics.

- Built a **cloud-native digital consultation ecosystem** on **Azure microservices** with secure patient-doctor interactions, appointment scheduling, and document sharing.  
- Designed distributed microservices with **Azure AD**, queues, and notification systems; led an 11-member cross-functional team.

### **Adda52 Poker & Rummy Apps**
Leading online poker and rummy gaming platform in India with millions of users.

- Architected cross-platform **Xamarin** apps, enabling ~60% of overall traffic via mobile.  
- Implemented shared business logic and MVVM patterns to streamline iOS/Android development.

---

## **EDUCATION**

**Bachelor of Engineering — Computer Science Engineering**  
Somany Institute of Technology & Management • 2005–2009
