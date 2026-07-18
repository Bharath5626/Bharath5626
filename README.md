<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Hey%2C%20I'm%20Bharath%20👋&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=AI%20Engineer%20%7C%20Full%20Stack%20Developer&descAlignY=55&descSize=18" width="100%"/>

</div>

---

## 🧑‍💻 About Me

**AI Engineer & Full-Stack Developer** from Chennai, India. I build and ship full-stack AI products end-to-end — prompt engineering and multi-modal AI pipelines on the backend, React on the frontend, Dockerized on Azure. Two of my projects are live in production right now, not just running locally.

- 🎓 B.Tech in Information Technology (Honors) — Anna University, CGPA 8.51/10
- 🚀 Shipped two live platforms: **[Elevra](https://elevraa.me)** (AI career suite) and **[ScopeAI](https://scope-shift.vercel.app)** (scope creep detection)
- 🤖 Working with **LLM orchestration** (Gemini + Claude), and exploring **RAG and LoRA/QLoRA fine-tuning**
- 📬 **Bharathsiva453@gmail.com**

---

## 💼 Experience

**Full-Stack Developer Intern** — Jasmin InfoTech Pvt. Ltd. · Jun 2026 – Jul 2026
Led a 3-member team to build and ship **ScopeAI** from zero to live in 4 weeks. Designed a hybrid AI architecture combining Gemini API feature-level analysis with a deterministic capacity engine for explainable timeline and risk output.

**Full-Stack Development Intern** — Approtech R&D Solutions · Jun 2025 – Aug 2025
Re-engineered the authentication module (Flask + JWT), cutting API response time by 40% through query optimization and connection pooling. Designed and documented 12+ RESTful endpoints for independent frontend delivery.

---

## 🛠️ Core Stack

*(Full stack details for each project are in their own READMEs — linked below.)*

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Anthropic Claude](https://img.shields.io/badge/Anthropic_Claude-D97706?style=for-the-badge&logo=anthropic&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

<details>
<summary>Also worked with: Flask, SQLAlchemy, Prisma, MongoDB, Redis, spaCy, Hugging Face / LoRA · PEFT, OpenCV, faster-whisper, Nginx, DigitalOcean, Gradio</summary>
<br>

These show up in specific projects below rather than everywhere — see each project's stack for context.

</details>

---

## 🚀 Featured Projects

### 🎯 [Elevra](https://github.com/Bharath5626/elevra) — AI Career Development Platform
> *Production-deployed full-stack career suite — my most comprehensive project*

An all-in-one career platform for freshers: **Resume Intelligence**, **Mock Interview Coaching** with real audio/video analysis, **JD Gap Analysis**, **Live Job Search**, a **Career Readiness Index**, an **AI Career Roadmap**, and a **Chrome Extension** for one-click applications.

🔗 **Live App:** [elevraa.me](https://elevraa.me) &nbsp;|&nbsp; **Stack:** React 19 · TypeScript · FastAPI · PostgreSQL · Gemini + Claude (provider auto-detected from API key) · Docker · Azure

- Built a provider-agnostic AI client that detects Gemini vs. Claude from the API key format at startup, so switching providers is a config change, not a code change
- Built an AI Mock Interview Coach running real speech and vision analysis — `faster-whisper` for transcription, DeepFace for sentiment, MediaPipe for eye-contact tracking — not just text-based scoring
- Shipped 7 modules end-to-end, including a Manifest V3 Chrome extension for one-click job applications

---

### 📋 [ScopeAI](https://github.com/Bharath5626/scope_shift) — AI Project Scope Manager
> *Catches scope creep before it derails a project*

Detects **scope creep** in real time, runs **what-if scenario modeling** (team size, deadlines, feature changes), and produces AI-backed capacity and risk analysis with PDF/CSV export.

🔗 **Live Demo:** [scope-shift.vercel.app](https://scope-shift.vercel.app) &nbsp;|&nbsp; **Stack:** React 19 · TypeScript · Express.js · Prisma ORM · MySQL · Gemini API · Tailwind CSS v4

- Hybrid AI architecture: Gemini reasons about individual features, while a deterministic backend engine computes all project-level math — keeps every analysis reproducible instead of subject to AI variance
- SHA-256 hashing of the current feature set avoids re-running (and re-billing) AI analysis on a scope that hasn't changed

---

### 🗂️ More Projects

- **[ResumeAI Analyzer](https://github.com/Bharath5626/ResumeAIAnalyzer)** — Final-year capstone. Weighted ATS scoring (skills/experience/education/format), spaCy skill extraction, Gemini-generated improvement suggestions, plus a resume builder with 5 templates. **[Live demo](https://resume-ai-frontend-28cb.onrender.com/)** · FastAPI · React · SQLite · spaCy
- **[InterviewAI Coach](https://github.com/Bharath5626/interviewai-coach)** — Mock interview platform with live webcam recording, Whisper-based speech analysis, and MediaPipe/DeepFace-based eye-contact and emotion tracking, graded via Claude/GPT-4. React · FastAPI · MongoDB · AWS S3 · Redis
- **[AI Troubleshooting Assistant](https://github.com/Bharath5626/AI-Troubleshooting-Assistant)** — Mistral-7B fine-tuned with LoRA (rank 16, alpha 32) on dev/infra troubleshooting Q&A pairs, deployed via Gradio. Python · PEFT · Hugging Face

---

## 📈 GitHub Activity

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=Bharath5626&theme=tokyo-night&hide_border=true&area=true" alt="Contribution Activity Graph" width="100%" />
</div>

---

## 🌐 Connect with Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bharath5626)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Bharath5626)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Bharathsiva453@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://bharath5626.vercel.app)

</div>

---

<div align="center">

*"Building applications that combine smart design with intelligent AI — one commit at a time."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

</div>
