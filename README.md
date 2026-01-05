# Pushp Kharat
### ML Systems Researcher & High-Performance Engineer

I build machine learning systems where performance is a first-class citizen. My work sits at the intersection of **Systems Programming (Rust/C++)** and **Applied ML Research**, with a specific focus on **Concept Drift Adaptation** and **Hardware-Aware Optimization**.

I prefer building quietly, measuring carefully, and optimizing relentlessly.

---

## Research & Core Focus

I specialize in **MLSys**—designing the computational engines that power modern AI:

* **Algorithmic Research**: Concept Drift Adaptation and Self-Adaptive Gradient Boosting for non-stationary data streams
* **Low-Level Systems**: High-performance kernels using SIMD, multi-threading via Rayon, and memory-safe systems in Rust
* **Optimization**: Numerical optimization (Newton-Raphson), information theory (Shannon Entropy), and sub-millisecond similarity search
* **Infrastructure**: Asynchronous, high-throughput backends using Axum and Tokio

---

## Featured Research: PKBoost
**Self-Adaptive Gradient Boosting Library in Rust** | *Mentored by Ash Vardanian (Founder, Unum Cloud)*

PKBoost is a production-ready GBDT framework built to handle "drifting" data where standard models fail.

**Technical Innovations:**
* Shannon entropy-guided splitting with second-order Newton optimization
* Metamorphic adaptation: real-time tree vulnerability tracking and selective pruning/retraining
* SIMD-accelerated kernels (SimSIMD) with Rayon parallelism
* PyO3 bindings for seamless Python integration

**Empirical Results:**
* Only **2.8% PR-AUC degradation** under severe concept drift vs. 12-18% for XGBoost/LightGBM
* **2,400+ PyPI downloads** and permanently archived (DOI: 10.5281/zenodo.17568991)

**Links:** [GitHub](https://github.com/Pushp-Kharat1/PKBoost) | [PyPI](https://pypi.org/project/pkboost/) | [Preprint](https://doi.org/10.5281/zenodo.17568991)

---

## Engineering Portfolio

### High-Performance Agentic RAG System
Built a production-grade RAG backend for HR automation (demoed to Godrej Living):

* **Architecture**: High-throughput async backend using Rust, Axum, and Tokio
* **Vector Search**: Custom in-memory vector store with USearch (HNSW) and FastEmbed for sub-millisecond search
* **Agentic Logic**: ReAct-style agent loop with Llama 3.3 for dynamic tool dispatching
* **Persistence**: PostgreSQL with SQLx for ACID-compliant chat history and vector storage

### Production Lead Scoring Pipeline
Enterprise B2B prioritization system deployed at Value Score:

* **Performance**: 0.89 ROC-AUC with 1-2 minute training time on 10k leads
* **Efficiency**: <2GB RAM footprint with native categorical handling
* **Real-World Impact**: 12x efficiency improvement (5% → 60% conversion rate), 80% sales time saved
* **Tech Stack**: CatBoost, Zoho CRM, automated feature engineering pipeline

---

## Technical Stack

| Domain | Technologies |
|:---|:---|
| **Languages** | Rust (expert), Python, C++, JavaScript |
| **ML & Research** | GBDT, Concept Drift Adaptation, Statistical Learning, RAG, Fine-tuning |
| **Systems** | SIMD, Parallel Computing (Rayon), PyO3, Linux, Memory Safety |
| **Backend/Infra** | Axum, Tokio, SQLx, USearch, Docker, n8n |
| **Math** | Information Theory, Numerical Optimization, Statistical Learning Theory |

---

## Experience

**Value Score Business Solutions LLP** | Technical Intern | *Jun 2025 – Present*
- Building agentic RAG workflows with n8n and open-source LLMs
- Developed custom Rust RAG agent for HR automation
- Evaluated Zoho ecosystem for AI/ML production deployment

**Artech Communications** | Network Engineering Trainee | *Dec 2024 – Apr 2025*
- Configured high-availability hospital network infrastructure
- Administered servers and security testing for critical systems

---

## The Discipline of Engineering

Outside of code, I am an **Amateur MMA District Gold Medalist** with a **5-1 record**. Engineering and combat sports share the same DNA:

* **Pressure Testing**: A system's reliability is only proven when stressed to its limits
* **Fundamental Mastery**: Deep knowledge of data structures, operating systems, and mathematics over framework hype
* **Relentless Improvement**: Building elite systems requires daily discipline

**Other Achievements:**
- Amateur MMA District Gold Medalist, Mumbai 2022 (5-1 record)
- TRCAC Chess Gold Medalist 2024

---

## Let's Connect

I'm open to **ML Systems Engineer**, **Applied AI Researcher**, or **Performance Engineering** roles where technical discipline is the standard.

**LinkedIn**: [pushp-kharat](https://www.linkedin.com/in/pushp-kharat-b4181520b/)  
**GitHub**: [Pushp-Kharat1](https://github.com/Pushp-Kharat1)  
**Email**: [kharatpushp16@outlook.com](mailto:kharatpushp16@outlook.com)
---
**BUY ME A COFFEE** : [Buy me a coffee](https://buymeacoffee.com/kharatpushg)
*"Build quietly. Measure carefully. Improve relentlessly."*
