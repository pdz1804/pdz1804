<!-- ═══════════════════════════════  HEADER  ══════════════════════════════ -->
<a href="https://pdz1804.github.io">
  <img width="100%" alt="Nguyen Quang Phu — AI Engineer" src="https://capsule-render.vercel.app/api?type=waving&color=0:0284c7,100:34d399&height=210&section=header&text=Nguyen%20Quang%20Phu&fontSize=46&fontColor=ffffff&fontAlignY=36&desc=AI%20Engineer%20%C2%B7%20Agentic%20AI%20%C2%B7%20LLMs%20%C2%B7%20RAG&descSize=18&descAlignY=58&animation=fadeIn" />
</a>

<div align="center">

<a href="https://github.com/pdz1804">
  <img alt="roles" src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1200&color=38BDF8&center=true&vCenter=true&width=720&height=42&lines=AI+Engineer+%40+FPT+Software+AI+Center;Taking+agentic+AI+to+production;Agent+runtimes+%C2%B7+permissions+%C2%B7+governance;LLM+%C2%B7+RAG+%C2%B7+multi-agent+systems;Python+%C2%B7+FastAPI+%C2%B7+AWS+%C2%B7+Azure+%C2%B7+GCP" />
</a>

<br/>

<a href="https://pdz1804.github.io"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-pdz1804.github.io-0284c7?style=for-the-badge&logo=firefox&logoColor=white"></a>
<a href="https://pdz1804.github.io/assets/cv/Nguyen_Quang_Phu_CV.pdf"><img alt="Resume" src="https://img.shields.io/badge/R%C3%A9sum%C3%A9-PDF-34d399?style=for-the-badge&logo=readdotcv&logoColor=white"></a>
<a href="https://www.linkedin.com/in/quangphunguyen/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-quangphunguyen-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<a href="mailto:quangphunguyen1804@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-quangphunguyen1804-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>

<img alt="profile views" src="https://komarev.com/ghpvc/?username=pdz1804&style=for-the-badge&abbreviated=true&color=0f4c81&label=PROFILE+VIEWS" />

</div>

---

## 👋 &nbsp;About

**AI Engineer at FPT Software AI Center** with 2 years' experience building and deploying AI-powered applications — Large Language Models, Retrieval-Augmented Generation, Agentic AI systems, and machine learning model development.

Most of my work is **taking agentic systems to production**: agent runtimes, tool-use orchestration, permission and governance layers, and multi-tenant administration with auditing, usage and cost reporting. I design end-to-end ML solutions that bridge model training, backend engineering, cloud deployment and production support — model fine-tuning, optimisation, and latency-aware agent design.

I operate services through a modern **observability** stack (structured logging, distributed tracing, metrics, error triage, model/agent trace inspection) and work to disciplined engineering practice — enforced architectural boundaries, decision records, a **default-deny permission model**, forward-only database migrations, staged releases, and layered testing from unit through end-to-end and agent-behaviour evaluations. I regularly author technical specifications and review peers' work.

- 🎓 &nbsp;**B.Sc. Computer Science — Applied Artificial Intelligence**, HCMUT (VNU-HCM) · graduated **Excellent**, GPA **3.8 / 4.0**
- 🌏 &nbsp;Vietnamese (native) · English — Professional Working Proficiency (**IELTS 6.5**)
- 🧭 &nbsp;Full-stack across **FastAPI** backends and **React / TypeScript** portals, deployed on **AWS, Azure and Google Cloud**
- 🌐 &nbsp;Full detail, live demos and every project → **[pdz1804.github.io](https://pdz1804.github.io)**

---

## 🎓 &nbsp;Education

- **Ho Chi Minh City University of Technology (HCMUT)** — B.Sc. Computer Science, Major in Applied Artificial Intelligence &nbsp;·&nbsp; `Sep 2022 – 2026`
  Graduated with **Excellent** classification · **Cumulative GPA 3.8 / 4.0** · Academic Incentive Scholarship (4/8 semesters) · OISP Scholarship (3/8 semesters) · **Consolidation Prize**, Bach Khoa Innovation Contest (Jun 2023)
- **Le Hong Phong High School for the Gifted** — Mathematics Honours Class &nbsp;·&nbsp; `2019 – 2022`

---

## 🧑‍💼 &nbsp;Experience

### Associate AI Engineer — FPT Software AI Center &nbsp;·&nbsp; `Nov 2025 – Present`

- **Agentic ERP Platform** (team of 15) — an enterprise AI workspace where autonomous agents act inside a company's business systems. Scope: **agent runtime, permissions & governance, multi-tenant administration, integrations** and customer-facing interfaces.
- Built the runtime **permission layer** (default-deny, enforced at runtime), per-customer administrator controls with a full **audit trail**, and **usage & cost reporting**; authored the permission-model specification through many review rounds.
- Shipped the first release of **user-authored Skills** and team sharing across agents, skills and artifacts; cut a slow shared-content endpoint from **tens of seconds to a single query**; consolidated user & group management onto one source of truth.
- Built a **third-party integration** from scratch; implemented queued messaging; improved streaming chat (conversation search, composer usable while replies stream).
- Operate services via **OpenTelemetry, Prometheus, Sentry and Arize Phoenix**; daily CI work with quality and architecture gates and migration-safety checks; review peers on architecture boundaries, permission correctness and migration safety.
- Earlier: architected a **healthcare agentic chatbot** and its **Management Portal** on **AWS Bedrock AgentCore** (team of 10), leading POC → production at **&gt;90% end-to-end accuracy**. 🏆 Team received the **"Best Team" award** — FPT Americas (ST25).
- Presented three internal **AI4ALL** knowledge-sharing sessions — *"AWS Strands Agents in the Cloud Era"*, *"Portal for Agent Projects"*, *"Agent as a Judge: How AI Evaluates AI"* — and mentored an intern alongside senior engineers.

### AI Engineer Intern — FPT Software AI Center &nbsp;·&nbsp; `Jun – Oct 2025`

<sub>Remote supervisor: Prof. Kazuyuki Motohashi, The University of Tokyo</sub>

- Built a **Blog System with AI search & recommendation** on Azure AI Search, Cosmos DB (NoSQL), Redis and Azure OpenAI, using **hybrid retrieval** — BM25 + vector + semantic + freshness scoring.
- Designed **[M3ARAG](https://github.com/pdz1804/M3ARAG)**, a locally deployable, GPU-accelerated **Multi-Agent RAG** system answering questions over PDFs, HTML, Office documents and text.
- Developed a **[Dual Attention Model](https://github.com/pdz1804/dual-attn-op-discovery)** extracting technical keywords from company websites, and a Transformation Matrix aligning Company–Patent data for the end-to-end **Innovation Discovery** pipeline.

### Research Assistant — Ho Chi Minh City University of Technology &nbsp;·&nbsp; `Jun – Dec 2024`

- Designed an unsupervised framework to construct a **Knowledge Graph** with minimal domain-expert input, reducing manual labelling and curation effort.
- Evaluated SOTA **LLMs** for entity and intent extraction on raw Vietnamese documents; researched embedding, dimensionality-reduction and clustering techniques to reduce bias in abstract entity representations.

---

## 🚀 &nbsp;Key projects

| Project | When | Stack |
|---|---|---|
| **Agentic ERP Platform** — enterprise AI workspace; agent runtime, permission layer, multi-tenant admin, Skills / Artifacts / Automations, plugin system | `Jun 2026 –` | FastAPI · Temporal · PostgreSQL · GKE · React |
| **Healthcare Agentic Chatbot & Management Portal** — multi-agent chatbot at &gt;90% accuracy + knowledge / prompt / guardrail management portal | `Nov 2025 – May 2026` | AWS Bedrock AgentCore · Strands |
| **Smart Product Recommendation System (SPR)** — rule-based + LLM hybrid recommendation engine for a skin-health device; compliance, quality gates, automated testing | `Oct – Nov 2025` | Amazon Bedrock · Testing Automation |
| **[M3ARAG](https://github.com/pdz1804/M3ARAG)** — GPU-accelerated multi-agent RAG for local, cloud-free document intelligence | `Aug – Oct 2025` | LangGraph · Docling · ColPali |
| **Azure Blog System with Search & Recommendation** — full-stack blog with hybrid semantic search and personalised recommendation | `Aug – Oct 2025` | Azure AI Search · Cosmos DB · Redis |
| **[Dual Attention Model for Innovation Discovery](https://github.com/pdz1804/dual-attn-op-discovery)** — attention model for technical-keyword extraction and Company ↔ Patent alignment | `Jun – Jul 2025` | PyTorch · Sentence-Transformers |

**Academic** &nbsp;·&nbsp; [Fine-tuning LMs for NLP Tasks](https://github.com/pdz1804/BTL_NLP) (T5 / BART / Flan-T5, LoRA) &nbsp;·&nbsp; [Sentiment Analysis with Various Models](https://github.com/pdz1804/ML_LHPD2) (7 ML/DL models) &nbsp;·&nbsp; [Detect AI-generated Text](https://github.com/Frankie2030/PIProject-detect-ai-essay) (DistilBERT vs. classical)

---

## 🛠️ &nbsp;Tech stack

<div align="center">

<img alt="core stack" src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,fastapi,postgres,redis,mongodb,docker,kubernetes,terraform,aws,azure,gcp,react,tailwind,typescript,git,githubactions,linux,nginx&perline=11" />

</div>

**LLM & Agents** &nbsp;— LangGraph · LangChain · AWS Strands · MCP (Model Context Protocol) · RAG & hybrid retrieval · Agent evaluation / LLM-as-a-Judge · OpenAI API · Google Gemini · Docling · ColPali

**ML & Data** &nbsp;— Hugging Face Transformers · Sentence-Transformers · PEFT / LoRA · spaCy · NLTK · Gensim · XGBoost · NumPy · Pandas · Polars

**Platform & Ops** &nbsp;— Temporal · Argo CD (GitOps) · Qdrant / ChromaDB / OpenSearch · OpenTelemetry · Prometheus · Sentry · Arize Phoenix · SonarQube · Backstage · Playwright

<details>
<summary><b>Full breakdown — proficiency &amp; years</b></summary>

| Area | Detail |
|---|---|
| **Languages** | Python (advanced, 4y) · JavaScript / TypeScript (2y) · C / C++ (2y) · SQL (2y) · R (1y) |
| **ML & DL** | PyTorch · TensorFlow / Keras · Scikit-learn · XGBoost · Hugging Face Transformers (Datasets, Accelerate, Evaluate) · Sentence-Transformers · PEFT / LoRA & adapter fine-tuning · spaCy · NLTK · Gensim · Word2Vec · FastText |
| **LLM & Agents** | LangChain · LangGraph · AWS Strands · MCP · RAG systems · Agent evaluation / LLM-as-a-Judge · OpenAI API/SDK · Google Gemini · Docling · ColPali |
| **Data & Analytics** | NumPy · Pandas · Polars · Matplotlib · Seaborn · SciPy · Weights & Biases |
| **Databases** | PostgreSQL · MySQL · MongoDB · Azure Cosmos DB · Redis · Temporal · Vector DBs — Qdrant, ChromaDB, OpenSearch Serverless |
| **Cloud & DevOps** | AWS — Bedrock AgentCore / KnowledgeBase / Guardrails, EC2, S3, ECS, ECR, Lambda, CodeBuild, CloudWatch · Azure — AI Search, Cosmos DB, OpenAI, Blob Storage · Google Cloud — Cloud SQL, GKE, Artifact Registry, Cloud Storage · Docker · Kubernetes · Terraform · Argo CD · CI/CD · OAuth 2.0 / RBAC |
| **Observability & Quality** | OpenTelemetry · Prometheus · Sentry · Arize Phoenix · SonarQube · Backstage · Playwright / Selenium |
| **Backend & Frontend** | FastAPI · Pydantic · SQLAlchemy · Alembic · ReactJS · TypeScript · Tailwind CSS · Streamlit · Linux / Nginx |
| **Practices** | Architectural boundaries & decision records · default-deny permission modelling · forward-only migrations · staged releases · layered testing (unit → integration → e2e → agent-behaviour evals) · technical-specification writing · code review |

</details>

---

## 📜 &nbsp;Certifications

- **Anthropic** — *Model Context Protocol: Advanced Topics*, AI Fluency Framework & Foundations, Claude with Vertex AI (May 2026) · Introduction to Subagents, Claude 101 (Apr 2026)
- **Google** — AI Specialization, AI Fundamentals & 3 more (Feb 2026) · Prompting Essentials & 2 more (Jun 2026) · Foundations of Data Science (May 2026) · Gemini Certified University Student (Dec 2025)
- **DeepLearning.AI** — AI Agents in LangGraph · Functions, Tools & Agents with LangChain · LangChain for LLM App Development · Build AI Apps with MCP Server &nbsp;(+5)
- **Hugging Face** — AI Agents Fundamentals (Jun 2025) &nbsp;·&nbsp; **DataCamp** — AI Engineer for Data Scientists Associate (Sep 2025)

<details>
<summary><b>Google Cloud &amp; the full list</b></summary>

- **Google Cloud** — Intermediate ML: TensorFlow on Google Cloud · Responsible AI for Developers · Inspect Rich Documents with Gemini Multimodality & Multimodal RAG · Develop Gen AI Apps with Gemini and Streamlit · Prompt Design in Vertex AI · Automate Data Capture at Scale with Document AI · Gemini for Data Scientists and Analysts
- **DeepLearning.AI (full)** — AI Agents in LangGraph · Functions, Tools and Agents with LangChain · LangChain for LLM Application Development · LangChain: Chat with Your Data · Build AI Apps with MCP Server · Knowledge Graphs for AI Agents · ChatGPT Prompt Engineering for Developers · Reasoning with o1 · Prompt Engineering with Llama 2 & 3
- **AWS** — Cloud Technology and Services Concepts · AWS Concepts
- **Microsoft** — Office Specialist: Excel, Word, PowerPoint

→ &nbsp;All credentials on [LinkedIn](https://www.linkedin.com/in/quangphunguyen/details/certifications/).

</details>

---

## 📊 &nbsp;GitHub

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=pdz1804&show_icons=true&count_private=true&hide_border=true&rank_icon=percentile&theme=tokyonight&title_color=38bdf8&icon_color=34d399" />
  <img height="165" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=pdz1804&show_icons=true&count_private=true&hide_border=true&rank_icon=percentile&title_color=0284c7&icon_color=0d9488" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=pdz1804&hide_border=true&theme=tokyonight&ring=38bdf8&fire=34d399&currStreakLabel=38bdf8" />
  <img height="165" alt="GitHub streak" src="https://streak-stats.demolab.com/?user=pdz1804&hide_border=true&ring=0284c7&fire=0d9488&currStreakLabel=0284c7" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=pdz1804&layout=compact&count_private=true&hide_border=true&langs_count=10&theme=tokyonight&title_color=38bdf8" />
  <img height="150" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=pdz1804&layout=compact&count_private=true&hide_border=true&langs_count=10&title_color=0284c7" />
</picture>

<img width="92%" alt="Trophies" src="https://github-profile-trophy.vercel.app/?username=pdz1804&theme=flat&no-frame=true&no-bg=true&margin-w=4&column=7" />

</div>

---

## 🔗 &nbsp;Connect

<div align="center">

<a href="https://pdz1804.github.io"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-0284c7?style=for-the-badge&logo=firefox&logoColor=white"></a>
<a href="https://www.linkedin.com/in/quangphunguyen/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<a href="https://www.kaggle.com/zphudzz"><img alt="Kaggle" src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white"></a>
<a href="mailto:quangphunguyen1804@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>

</div>

<img width="100%" alt="" src="https://capsule-render.vercel.app/api?type=waving&color=0:34d399,100:0284c7&height=120&section=footer" />
