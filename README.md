<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Sankeerth%20TS&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20%7C%20Full-Stack%20%7C%20Systems%20Builder&descAlignY=60&descColor=a78bfa" width="100%" />

<a href="https://linkedin.com/in/sankeerth-ts/">
  <img src="https://img.shields.io/badge/LinkedIn-Sankeerth%20TS-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
&nbsp;
<a href="mailto:sankeerthts54@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-sankeerthts54-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
&nbsp;
<a href="https://github.com/sankeerthts54-glitch">
  <img src="https://img.shields.io/badge/GitHub-sankeerthts54--glitch-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
&nbsp;
<img src="https://komarev.com/ghpvc/?username=sankeerthts54-glitch&color=7c3aed&style=for-the-badge&label=Profile+Views" />

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=500&color=A78BFA&center=true&vCenter=true&multiline=true&width=700&height=80&lines=Building+AI+agents+that+think%2C+act+%26+heal+%F0%9F%A4%96;From+3D+Gaussian+Splats+to+Civic+AI+%F0%9F%8C%90;CGPA+9.5+%E2%80%A2+Hackathon+Finalist+%E2%80%A2+Systems+Builder" alt="Typing SVG" />

</div>

---

## ⚡ About Me

```python
class SankeerthTS:
    role       = "AI & Full-Stack Systems Engineer"
    academics  = "BTech CSE · CGPA: 9.5 / 10.0"
    passions   = ["Autonomous Agents", "Neural Rendering (3DGS)", "Computer Vision", "DevOps & Cloud"]
    currently  = "Architecting resilient multi-agent workflows and high-throughput pipelines"
    contact    = "sankeerthts54@gmail.com"
    linkedin   = "https://linkedin.com/in/sankeerth-ts/"
    hackathons = [
        "HackerRank Orchestrate (Oct 2026)",
        "TrueFoundry × Polaris 'Agents That Act' (Sep 2026)",
        "WeMakeDevs × AWS Environmental Hacks (2026)",
        "Build with AI: Code for Communities (Google / India)",
        "AWS Bharat Builds — First Commit"
    ]
```

> High-performing Computer Science undergraduate (**CGPA 9.5**) obsessed with building robust software: from **autonomous LLM agents that self-heal broken deployments** and **audit GDPR data deletion compliance**, to **real-time 3D Gaussian Splatting** and **large-scale async ingestion engines**. Every project is built end-to-end, tested, and deployed live.

---

## 🏆 Featured Projects & System Showcases

> *Carefully ordered by architectural depth, systems complexity, and industry impact.*

---

### 🥇 Tier 1 — Autonomous Agents, Systems Engineering & 3D Vision

---

#### 🔮 [GhostAudit](https://github.com/sankeerthts54-glitch/GhostAudit)
> **Built for HackerRank Orchestrate — October 2026 Hackathon**

An intelligent audit agent that solves the critical privacy problem of **"Ghost Data"** — situations where deletion workflows report *Complete*, yet personal identifiable data (PII) lingers inside read-replicas, search indexes, multi-modal evidence logs, or SQL backups.

- **Deep Evidence Traversal**: Parses heterogeneous evidence artifacts (PDFs, images, raw server logs, JSON payloads, and relational SQLite snapshots across regional read & failover replicas).
- **Decision Engine**: Classifies deletion states (`COMPLETE`, `INCOMPLETE`, `NOT_APPLICABLE`), isolates data recreation risks, and outputs ordered, deterministic remediation and verification steps.
- **Tech Stack**: `Python 3.11+` `Google Gemini 2.0/2.5 Flash API` `SQLite` `Multi-modal Parsing` `Agentic Workflows`

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=flat-square&logo=google&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

---

#### 🌌 [Gaussian Splat Viewer](https://github.com/sankeerthts54-glitch/gaussian-splat-viewer) · [Live Interactive Demo ↗](https://gaussian-splat-viewer-kmk1.vercel.app/)
> **End-to-End Photogrammetry & Neural Scene Reconstruction Pipeline**

A complete computer vision pipeline converting raw 2-minute smartphone video footage into an interactive 3D neural scene rendered at 60 FPS directly inside the browser.

```
Phone Video → Laplacian Blur Filtering → COLMAP SfM → 3DGS Training (nerfstudio/CUDA) → WebGL / Three.js
```

- **Novel View Synthesis**: Parameterizes complex physical spaces as millions of 3D Gaussian ellipsoids (position, covariance matrix, opacity, and spherical harmonic view-dependent color).
- **GPU Acceleration**: Trained with CUDA and `nerfstudio` (`splatfacto`); rendered client-side using custom WebGL/Three.js shaders with tile-based rasterization.
- **Tech Stack**: `Python` `CUDA 11.8+` `COLMAP` `nerfstudio` `Three.js` `WebGL` `Vercel`

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=three.js&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

---

#### 🛒 [SmartKart](https://github.com/sankeerthts54-glitch/SmartKart) · [Live App ↗](https://smart-kart-iota.vercel.app/) · [Backend API ↗](https://smartkart-ndrc.onrender.com)
> **AI-Powered Multi-Agent E-Commerce Intelligence Platform**

Real-time price comparison and recommendation engine querying e-commerce platforms (Amazon, Flipkart, Croma, BigBasket, Reliance Digital) with fallback web scraping and Gemini-powered decision synthesis.

- **Intelligent Synthesis**: Computes real discounts, extracts review sentiment, checks stock availability, and outputs unified recommendation verdicts.
- **Production Architecture**: Decoupled FastAPI async backend running on Render paired with a responsive Next.js/React frontend deployed on Vercel.
- **Tech Stack**: `FastAPI` `Python` `React` `Next.js` `Google Gemini API` `Render` `Vercel`

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=flat-square&logo=google&logoColor=white)

---

#### 🩺 [DeployMentor (Deploy Doctor)](https://github.com/sankeerthts54-glitch/DeployMentor)
> **TrueFoundry × Polaris "Agents That Act" Hackathon (Sep 2026)**

A self-healing deployment failsafe agent built on the **Model Context Protocol (MCP)**. Continuously observes live deployment infrastructure (Render, Hugging Face Spaces, Vercel, GitHub Pages), parses build and runtime error logs, and automatically intervenes.

- **3-Tier Remediation Guardrails**:
  - `Tier 1 (Automated)`: Low-risk, fully reversible fixes (service restarts, rollbacks, cached build purges).
  - `Tier 2 (Human-in-the-Loop)`: Configuration updates or environment variable patches that pause for explicit user approval before execution.
  - `Tier 3 (Diagnostic Alert)`: Outage, quota, or billing limit reports requiring developer escalation.
- **Post-Fix Verification**: Hits live endpoints after changes to guarantee uptime and zero regression.
- **Tech Stack**: `Node.js 22+` `MCP (Model Context Protocol)` `TrueForge` `OpenAI` `Cloud Platform APIs`

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-Protocol-blueviolet?style=flat-square)

---

#### ⚡ [GraphOne Intelligence Pipeline](https://github.com/sankeerthts54-glitch/graphone-pipeline)
> **Production-Grade Async AI Ecosystem Ingestion & Graph Feeder**

High-performance, async data pipeline designed for ingesting startups, research papers (arXiv), job postings, and technical news at scale for the FrontierAtlas Intelligence Graph.

- **Fault-Tolerant LLM Extraction**: Tri-model cascade fallback strategy (`Gemini` → `Groq` → `DeepSeek`) to seamlessly circumvent rate limits (`429`) and upstream service downtime.
- **Data Integrity**: Token chunking estimators to prevent `413 Payload Too Large`, fuzzy entity resolution, deduplication via SQLite hashing, and 24h freshness filters.
- **Tech Stack**: `Python 3.11+` `asyncio` `aiohttp` `SQLite` `Groq` `DeepSeek` `Gemini`

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![asyncio](https://img.shields.io/badge/asyncio-High--Throughput-blue?style=flat-square)

---

### 🥈 Tier 2 — Civic AI, Cloud Architectures & Full-Stack Products

---

#### 🏛️ [CivicPulse AI](https://github.com/sankeerthts54-glitch/CivicPulse) · [Citizen Portal ↗](https://civicpulse-ai.web.app) · [Policymaker Dashboard ↗](https://civicpulse-ai.web.app/dashboard)
> **Build with AI: Code for Communities Hackathon — Track 1: Digital Public Infrastructure**

A multilingual civic grievance and demand aggregation platform enabling Indian citizens to submit infrastructure concerns in regional languages via voice or text, matched against real `data.gov.in` datasets.

```
Citizen (Voice/Text) → Cloud Translation → Gemini Hotspot Engine → Firestore → BigQuery → Dashboard
```

- **Policymaker Analytics**: Aggregates complaints into spatial demand clusters, ranking priority developmental projects with automated budget & impact estimates.
- **Tech Stack**: `Next.js 15` `TypeScript` `Tailwind CSS` `Firebase / Firestore` `Gemini 2.0 Flash` `Google Cloud Translation` `Recharts`

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

---

#### ♻️ [WasteWise](https://github.com/sankeerthts54-glitch/WasteWise)
> **WeMakeDevs × AWS Environmental Hacks 2026 — Track 03: Waste & Energy**

Intelligent advisory portal providing personalized, hyper-local action plans for waste segregation, e-waste compliance, recycling, and rooftop solar adoption for urban Indian households and MSMEs.

- **Tech Stack**: `React 18` `Vite` `TypeScript` `Node.js / Express` `Supabase (PostgreSQL + Auth)` `Gemini 2.5 Flash` `AWS Amplify` `AWS App Runner`

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)

---

#### 🛫 [OffBoard](https://github.com/sankeerthts54-glitch/OffBoard)
> **AWS Bharat Builds — First Commit Hackathon (Sep 2026)**

Universal Digital Life-Transition Assistant orchestrating account migration, subscription cancellations, and data memorialization across major life events (relocation, career transitions, retirement).

- **Serverless AWS State Machine**: Powered by `AWS Step Functions`, `AWS Bedrock` classification agents, `AWS Lambda` worker pools, and `DynamoDB` transaction ledgers.
- **Tech Stack**: `AWS Lambda` `AWS Bedrock` `DynamoDB` `Step Functions` `EventBridge` `SNS/SES` `Amplify` `React`

![AWS](https://img.shields.io/badge/AWS_Serverless-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

---

### 🥉 Tier 3 — Algorithms, Computer Vision & Interactive Applications

---

| Project | Description | Stack | Links |
| :--- | :--- | :--- | :--- |
| **🎬 [CineMatch](https://github.com/sankeerthts54-glitch/CineMatch)** | AI film recommender providing 6 curated titles, streaming providers, trailers & critic blurbs with animated gradient UI. | `React 19`, `Express 5`, `Gemini`, `Docker` | [Live Demo ↗](https://huggingface.co/spaces/Vader26/cinematch) · [Code](https://github.com/sankeerthts54-glitch/CineMatch) |
| **🚀 [GestShoot](https://github.com/sankeerthts54-glitch/GestShoot)** | Zero-engine space shooter controlled via webcam hand gestures. Features Kalman filter tracking and dynamic combo multipliers. | `Python`, `MediaPipe`, `OpenCV`, `NumPy` | [Code](https://github.com/sankeerthts54-glitch/GestShoot) |
| **🎵 [Song Ranker](https://github.com/sankeerthts54-glitch/song-ranker)** | Pairwise music ranking using **Binary Insertion Sort**, halving decision fatigue (~30% fewer clicks than merge sort). | `Python`, `Streamlit`, `Spotify API`, `Algorithms` | [Live Demo ↗](https://huggingface.co/spaces/Vader26/song-ranker) · [Code](https://github.com/sankeerthts54-glitch/song-ranker) |
| **📄 [ATS Resume Checker](https://github.com/sankeerthts54-glitch/ats-resume-checker)** | NLP resume evaluation engine measuring job description alignment via TF-IDF vectorization and cosine distance. | `Python`, `scikit-learn`, `Streamlit`, `NLP` | [Live Demo ↗](https://huggingface.co/spaces/Vader26/ats-resume-checker) · [Code](https://github.com/sankeerthts54-glitch/ats-resume-checker) |
| **🎨 [ColorCat](https://github.com/sankeerthts54-glitch/ColorCat)** | Lightweight Chrome Extension with crosshair cursor mode to dynamically inspect and recolor web DOM nodes. | `JavaScript (ES6+)`, `Chrome Extensions API`, `CSS` | [Code](https://github.com/sankeerthts54-glitch/ColorCat) |
| **🗃️ [AI Models Dataset](https://github.com/sankeerthts54-glitch/ai-models-dataset)** | Automated data extraction & cleaning pipeline generating 2,000+ structured AI model entries mapped to strict 40-col schemas. | `Python`, `pandas`, `HuggingFace API`, `Gemini` | [Code](https://github.com/sankeerthts54-glitch/ai-models-dataset) |

---

## 🛠️ Skills & Technologies

<div align="center">

### 💻 Languages & Runtimes
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)

### 🤖 AI, LLM & Computer Vision
![Google Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![AWS Bedrock](https://img.shields.io/badge/AWS_Bedrock-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0F9D58?style=for-the-badge&logo=google&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)

### 🌐 Frontend & User Interface
![React](https://img.shields.io/badge/React_18%2F19-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)

### ⚙️ Backend, Cloud & Databases
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_Cloud-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=for-the-badge&logo=amazondynamodb&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

</div>

---

## 📊 Activity & Statistics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sankeerthts54-glitch&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=A78BFA&text_color=ffffff&rank_icon=github" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sankeerthts54-glitch&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=ffffff&langs_count=8" height="165" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=sankeerthts54-glitch&theme=tokyonight&hide_border=true&background=0D1117&ring=A78BFA&fire=A78BFA&currStreakLabel=A78BFA" />
</div>

<details>
<summary><b>🐍 Dynamic Contribution Snake Animation</b></summary>
<br/>
<div align="center">
  <img src="https://raw.githubusercontent.com/sankeerthts54-glitch/sankeerthts54-glitch/output/github-contribution-grid-snake.svg" alt="Contribution Snake" />
</div>
</details>

---

## 🏅 Hackathon Track Record

| Hackathon | Organizer / Sponsor | Project | Theme / Focus |
|:---|:---|:---|:---|
| **HackerRank Orchestrate** (Oct 2026) | HackerRank | [GhostAudit](https://github.com/sankeerthts54-glitch/GhostAudit) | AI Data Deletion Compliance & Evidence Audit |
| **Agents That Act** (Sep 2026) | TrueFoundry × Polaris | [DeployMentor](https://github.com/sankeerthts54-glitch/DeployMentor) | Self-Healing Deployment Agents via MCP |
| **Environmental Hacks 2026** | WeMakeDevs × AWS | [WasteWise](https://github.com/sankeerthts54-glitch/WasteWise) | AI Waste & Renewable Energy Advisory |
| **Code for Communities** | Build with AI (Google / India) | [CivicPulse](https://github.com/sankeerthts54-glitch/CivicPulse) | Multilingual Citizen Grievance Hotspot Analysis |
| **First Commit Hackathon** | AWS Bharat Builds | [OffBoard](https://github.com/sankeerthts54-glitch/OffBoard) | Serverless Digital Life-Transition Assistant |

---

## 🎯 What I'm Looking For

- **Target Roles:** AI Systems Engineer · Full-Stack Software Engineer · Machine Learning Engineer
- **Core Focus:** Autonomous Agent Architectures · Scalable Cloud Pipelines · 3D Neural Rendering & Computer Vision
- **Availability:** SWE Internships · High-Impact Research Collaborations · Early-Stage AI Engineering

---

<div align="center">

### 📬 Connect With Me

<a href="mailto:sankeerthts54@gmail.com">
  <img src="https://img.shields.io/badge/Email-sankeerthts54%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
&nbsp;
<a href="https://linkedin.com/in/sankeerth-ts/">
  <img src="https://img.shields.io/badge/LinkedIn-Sankeerth%20TS-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<br/><br/>

*"First make it work, then make it right, then make it fast."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" width="100%" />

</div>
