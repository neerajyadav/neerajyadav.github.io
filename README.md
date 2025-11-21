# **Neeraj Kumar**

**Principal Architect / Founding Engineer | SaaS | Solana Blockchain | Cloud | Distributed Systems | Sustainability Tech** 
Gurugram, Haryana, India
er.neerajyadav@gmail.com
linkedin.com/in/neeraj-kosliya
 
## **SUMMARY**

- 14+ years building and scaling **SaaS platforms, distributed systems, and data-intensive products** across startups and enterprises.  
- Blend of **founding engineer / principal architect** experience: 0→1 product development, multi-tenant SaaS architecture, and leading cross-functional engineering teams.  
- Deep hands-on expertise in **Node.js, Go, microservices, Kubernetes, and event-driven systems** across **AWS, Azure, and GCP**.  
- Recent focus on **Solana blockchain trading and analytics**: Geyser indexers, Transaction and Instructions decoders, on-chain data pipelines, and ML-assisted trading engines.  
- Proven track record of **end-to-end ownership** — discovery, architecture, implementation, CI/CD, observability, and stakeholder alignment with business and product goals.

## **CORE STRENGTHS**

- 0→1 Product Development & Startup Execution  
- SaaS & Platform Architecture
- Cloud Infrastructure (AWS, Azure, GCP, Kubernetes)  
- Distributed Systems  
- Solana Blockchain Ecosystem
- Engineering Leadership 
- Sustainability Tech

## **TECHNICAL SKILLS**

**Languages:** TypeScript/JavaScript (Node.js), Go, C#, Dart  
**Blockchain:** Solana (Geyser Stream, Jito bundles, Raydium AMM/CPMM, pump.fun, Anchor decoding)  
**Cloud:** AWS (EKS, EC2, RDS, SQS, S3), Azure (Functions, Service Bus), GCP (Firestore, GKE)  
**Distributed Systems:** Microservices, gRPC, NATS JetStream, event-driven patterns  
**Databases:** PostgreSQL, ClickHouse, MongoDB, ArangoDB  
**DevOps:** Docker, Kubernetes, Helm, GitHub CI/CD, Skaffold, ArgoCD  
**Architecture:** SaaS, multi-tenancy, high-throughput ingestion systems
 
## **EXPERIENCE**
 
**Independent Product Builder**  
**Solana Token Trading Engine & Analytics Platform**  
*May 2025 – Present*
High performance trading bot with ultra-low latency for newly minted Solana tokens. Trade based on XGBoost model predictions and on-chain signals and execute sell strategies like multiple take-profits and trailing stop-loss by continuously monitoring token price movements.

- End-to-end development of a high-frequency trading platform on Solana, focusing on sub-second latency and data accuracy.
- Designing scalable architecture to handle high throughput from blockchain streams, ensuring reliability for real-time trading decisions.
- Integrating advanced ML models into the trading workflow to automate decision-making based on live on-chain signals.
- Utilizing AI-assisted development workflows to maximize individual engineering throughput and rapid prototyping.

**Key Technical Implementation:**
- **Ingestion Pipeline:** Engineered a custom **Go-based Geyser listener** consuming raw solana blockchain streams. Implemented a **NATS JetStream** buffer to decouple ingestion from processing, ensuring zero data loss during bursts.
- **ML-model assisted trading engine:** Trained XGBoost model on historical on-chain data to predict short-term price movements of newly minted tokens. Implemented feature engineering techniques to extract insights from on-chain mint events, improving model accuracy.
- **Data Storage:** Optimized **ClickHouse** schemas for high-speed write ingestion of block data and **PostgreSQL** for transactional state management.
- **Decoding Logic:** Wrote custom binary decoders for **Anchor** programs (Raydium, Pump.fun, pump-swap) to extract trade events directly from raw instruction data, bypassing slower public RPCs.
- **Execution:** Built an execution engine that constructs and signs transactions in microseconds, utilizing **Jito bundles** for guaranteed inclusion.

**Principal Architect**  
**Emission Critical Pvt. Ltd.**  
*Jul 2022 – May 2025*
SOC2 certified multi-tenant SaaS platform for enterprise sustainability management, enabling organizations to measure, report, and reduce their carbon footprint and ESG impact.

- Spearheaded the technical vision and architecture for the platform, enabling enterprise clients to manage complex ESG reporting.
- Led the migration of complex carbon accounting methodologies into scalable digital workflows, directly impacting customer adoption.
- Owned the platform's reliability, security, and cloud infrastructure strategy, ensuring compliance with enterprise standards (SOC2).
- Designed and implemented high-volume data integration strategies to ingest fragmented supply chain data from diverse client systems.

**Key Technical Implementation:**
- **Multi-Tenancy:** Implemented a hard-isolated multi-tenant architecture on **AWS EKS**. Leveraged **OpenFGA** (Google Zanzibar implementation) for fine-grained, relationship-based access control (ReBAC) across complex organizational hierarchies.
- **Event-Driven ETL:** Designed an asynchronous ETL pipeline using **Airbyte** for data extraction and **NATS** for event propagation, allowing users to upload massive datasets without blocking the UI.
- **Infrastructure:** Managed **EKS** Kubernetes clusters for hosting microservices and other workloads, utilizing **ArgoCD** and **Helm** to implement GitOps deployments for rapid, consistent updates across environments.
- **Observability:** Integrated **SigNoz** (OpenTelemetry) for end-to-end distributed tracing, enabling rapid root-cause analysis of performance bottlenecks in microservices.

**Head of Technology**  
**Poker Sports League (Hashtag Poker)**  
*Aug 2020 – Jun 2022*
End-to-end poker learning and playing platform with mobile apps, real-time game engine, and scalable backend infrastructure.

- Built and led the engineering division from the ground up, hiring and mentoring a cross-functional team of 11 developers and QA engineers.
- Defined the technology roadmap and architecture for a highly concurrent gaming platform, ensuring stability during peak tournament traffic.
- Established engineering best practices, including CI/CD pipelines, automated testing, and observability, reducing deployment failures and downtime.

**Key Technical Implementation:**
- **Mobile Apps:** Led full-stack development of **Flutter mobile apps** (iOS/Android) with shared business logic using MVVM architecture.
- **Concurrency:** Utilized **NATS JetStream** for broadcasting real-time game events (moves, folds, wins) to **Flutter** clients with millisecond latency.
- **Scalability:** Deployed on **Kubernetes** with horizontal pod autoscaling (HPA) and monitoring with **Prometheus** and **Grafana**.

**Co-Founder & Engineering Manager**  
**Mu Software Solutions Pvt. Ltd.**  
*2014 – 2017, 2018 – 2020*
- Co-founded a product engineering studio, guiding startups from initial concept to MVP and market traction.
- Managed multiple concurrent product lifecycles, acting as the technical partner for non-technical founders.
- Led the architectural decision-making process, selecting appropriate tech stacks (Cloud-native, Microservices) for scalability and cost-efficiency.
- Mentored engineering teams, fostering a culture of ownership, code quality, and rapid delivery.

**Key Technical Implementation:**
- **Arkaa Digital Healthcare:** Built a **cloud-native digital consultation ecosystem** on **Azure microservices** with secure patient-doctor interactions, appointment scheduling, and document sharing. Designed distributed microservices with **Azure AD**, queues, and notification systems.
- **Adda52 Poker & Rummy:** Architected cross-platform **Xamarin** apps, enabling ~60% of overall traffic via mobile. Implemented shared business logic and MVVM patterns to streamline iOS/Android development.

**Consultant (Microsoft India — HP Inc.)**  
**Data Glove IT Solutions**  
*2017 – 2018*
- Optimized large-scale data analytics operations for HP Inc., focusing on automation and reliability of Azure-based pipelines.
- Streamlined manual data processes into automated workflows, significantly reducing operational overhead and error rates.

**Key Technical Implementation:**
- **Azure Data Factory & Logic Apps:** Automated complex data ingestion and transformation workflows for HP's global sales data, reducing manual effort by 70%.
- **Power BI Integration:** Developed interactive dashboards for real-time performance monitoring and anomaly detection in data pipelines.

**Senior Software Engineer**  
**PS Intelegencia Analytics Pvt. Ltd.**  
*2012 – 2014*
- Led the development of core web and mobile application modules using the .NET ecosystem.
- Managed the full software development lifecycle (SDLC) for key client projects, ensuring on-time delivery.

**Software Engineer**  
**Elixir Computech Pvt. Ltd.**  
*2010 – 2012*
- Developed custom enterprise automation tools, translating business requirements into functional software solutions.
- Collaborated with clients to refine technical specifications and deliver scalable .NET applications.

## **EDUCATION**

**Bachelor of Engineering — Computer Science Engineering**  
Somany Institute of Technology & Management • 2005–2009
