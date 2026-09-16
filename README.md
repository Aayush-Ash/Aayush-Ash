<div align="center">

# Hi, I'm Aayush Kumar 👋 — call me **Ash**

### Agentic AI Engineer · Building autonomous systems that reason, act, and ship

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-0B1120?style=for-the-badge&logo=vercel&logoColor=00E5FF)](https://github.com/Aayush-Ash)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/aayush-kumar-ash/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Aayush-Ash)

</div>

---

### 👨‍💻 About Me

I'm a Computer Science Engineering student (Lovely Professional University) obsessed with the space between **LLMs and real-world autonomy** — agents that don't just chat, but plan, use tools, and get things done.

- 🧠 **Focus:** Agentic AI systems — multi-step reasoning, tool-calling, and orchestration with **LangGraph** & **LangChain**
- 🔌 **Also building with:** Model Context Protocol (MCP), Retrieval-Augmented Generation (RAG), and vector databases
- 🛠️ **Shipping with:** Python, FastAPI, Docker, AWS, PostgreSQL
- 🎯 **Right now:** Open to **AI Engineer / Applied AI Engineer / LLM Engineer** roles — on-site, hybrid, or remote
- 📍 Based in Amritsar, Punjab, India

---

### ⚡ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

</div>

---

### 🚀 Featured Projects

| Project | What it does | Stack |
|---|---|---|
| **🌸 [SakuraKeys](https://github.com/Aayush-Ash/sakura-keys)** | Anime-inspired typing speed trainer — interactive 3D keyboard, live WPM/accuracy tracking, keystroke sound feedback, gamified practice | Next.js 16, React 19, TypeScript, Tailwind CSS v4, Web Audio API |
| **PhishGuard AI** | LLM-powered security suite for detecting zero-day phishing attempts and malicious communications | Gemini API, React Three Fiber, GSAP |
| **[Neural Hologram Interface](https://github.com/Aayush-Ash/neural-hologram-interface)** | Emotion-aware AI hologram — tracks faces in real time, adapts expressions, lip-syncs speech, responds like a JARVIS-style avatar | Python, Facial Landmark Tracking, TTS |
| **[Xtremis](https://github.com/Aayush-Ash/Xtremis)** | Real-time object tracking helmet HUD, Iron Man–inspired — live detection overlaid on a heads-up display | Python, YOLOv8, Computer Vision |
| **[AirFlip](https://github.com/Aayush-Ash/AirFlip)** | Touchless PDF navigation controlled entirely by real-time hand gestures | Python, MediaPipe, OpenCV |
| **K8s App Monitoring** | Observability setup for containerized applications running on Kubernetes | Kubernetes, Docker |

> 🔭 Currently deepest in agentic workflows — chaining tool-calling LLMs with LangGraph into pipelines that plan and self-correct.

<details>
<summary>🌸 <b>SakuraKeys — full stack breakdown</b></summary>

<br>

**Framework & language**
Next.js 16 (App Router, webpack build) · React 19 · TypeScript (strict mode, `tsc --noEmit` clean)

**Styling**
Tailwind CSS v4 · hand-written custom CSS for the core visual design (keyboard, config bar, typing area, settings modal) · `class-variance-authority` / `clsx` / `tailwind-merge` combined into a `cn()` helper · shadcn/ui scaffolded via `components.json` (Base UI primitives, "radix-nova" style, Phosphor icons) — not yet pulled in, UI is fully custom

**Audio engine**
Native Web Audio API (`AudioContext`, `AudioBuffer`, `AudioBufferSourceNode`, `GainNode`) driving the mechanical-keyboard-sound system, wrapped in a custom `useTypingSound` hook

**Database** *(scaffolded, not yet active)*
Drizzle ORM + `drizzle-kit` · `@libsql/client` (Turso-compatible LibSQL), currently pointed at a local `local.db` with an empty placeholder schema

**PWA**
Serwist (`@serwist/next`) generating the service worker (`app/sw.ts` → `public/sw.js`)

**Env validation**
`@t3-oss/env-nextjs` + Zod — validates `DATABASE_URL`, `DATABASE_AUTH_TOKEN`, `NEXT_PUBLIC_SITE_URL` at build time

**SEO / Analytics**
Next.js metadata routes (`robots.ts`, `sitemap.ts`, `opengraph-image.png`, `icon.png`) · `@vercel/analytics` + `@vercel/speed-insights` (consent-gated)

**Tooling & deployment**
Biome (Ultracite preset) for lint/format · npm (`package-lock.json`) · deployed on Vercel

</details>

---

### 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=Aayush-Ash&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0B1120" width="49%" alt="Ash's GitHub stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Aayush-Ash&layout=compact&theme=tokyonight&hide_border=true&bg_color=0B1120" width="42%" alt="Top languages" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Aayush-Ash&theme=tokyonight&hide_border=true&background=0B1120" width="60%" alt="GitHub streak" />

</div>

---

### 🎓 Certifications

- Introduction to Artificial Intelligence — Google / Coursera
- IBM DevOps and Software Engineering — Coursera

---

<div align="center">

*Building agents that don't just talk — they act.* 🤖

</div>
