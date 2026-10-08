<a href="https://anuragworks.in">
  <img src="https://anuragworks.in/opengraph-image" alt="Anurag Gokhale, AI Engineer. I build AI that survives production." width="100%" />
</a>

<p>
  <a href="https://anuragworks.in"><img src="https://img.shields.io/badge/Portfolio-anuragworks.in-ff2800?style=for-the-badge&labelColor=1a1514" alt="Portfolio" /></a>
  <a href="https://roost.anuragworks.in"><img src="https://img.shields.io/badge/Roost-live-ff2800?style=for-the-badge&labelColor=1a1514" alt="Roost, live" /></a>
  <a href="https://linkedin.com/in/anuraggokhale"><img src="https://img.shields.io/badge/LinkedIn-anuraggokhale-1a1514?style=for-the-badge" alt="LinkedIn" /></a>
  <a href="mailto:anuraggokhaleai@gmail.com"><img src="https://img.shields.io/badge/Email-say%20hi-1a1514?style=for-the-badge" alt="Email" /></a>
  <a href="https://anuragworks.in/AnuragGokhale_AIEngineer_Resume.pdf"><img src="https://img.shields.io/badge/Résumé-PDF-1a1514?style=for-the-badge" alt="Résumé" /></a>
</p>

I'm an **AI engineer** at India's largest explosives manufacturer, a group that also builds for defence and aerospace. I design tool-calling pipelines, retrieval workflows and agent orchestration that connect models to real APIs, databases and business tools, and I've led the computer vision division running **350+ cameras** across its plants.

Most of my production work runs on-premise for my employer, so that code isn't public. The full write-ups are on **[anuragworks.in](https://anuragworks.in)**.

### What I've shipped

| | What it does | Built with |
|---|---|---|
| **[Roost](https://roost.anuragworks.in)** · live | Six-agent job search: discovers roles across 6 ATS platforms, scores them, writes cover letters, fills real forms in a browser, and **never submits without a human yes** | Python, Groq, Gemini, Gemini Live, Playwright, React |
| **Voice RAG** | Fault codes and repair procedures for maintenance crews, asked aloud in Hindi or English | LangChain, embeddings, STT / TTS |
| **LLM chat over plant telemetry** | Questions answered against live sensor data, with context filtered by role before it reaches the model | Next.js, FastAPI, OIDC SSO + RBAC |
| **PPE violation detection** | YOLO trained from scratch, on-premise across 350+ cameras. Daily violations: **~8,000 → under 300** | YOLO, OpenCV, MinIO |
| **ANPR at the gates** | 200+ vehicles read and logged daily into a searchable audit trail | Fine-tuned YOLO, OCR, PostgreSQL |
| **Headcount AI** · pilot | Multi-camera tracking with persistent identity, piloted on 20 cameras | NVIDIA DeepStream, NvDCF re-ID |

### Public here

- **[matterofai](https://github.com/AnuragGokhale17/matterofai)**: an autonomous content pipeline that pulls trending AI news, writes explainers with an LLM, and renders narrated reels and carousels for Instagram.
- **[portfolio](https://github.com/AnuragGokhale17/portfolio)**: the source of [anuragworks.in](https://anuragworks.in). Next.js 16, Motion, Tailwind.

### How I build

- **Code coordinates. Models decide.** Every LLM call should pay for a judgment; routing and retries are plain code.
- **Nothing irreversible without a person.** Agents get an approval gate exactly where the action can't be undone.
- **Measure the number the business feels.** Accuracy is a checkpoint. The result is what changes on the floor.

### Stack

**AI / LLM:** tool calling · multi-agent orchestration · RAG · embeddings · LangChain · Groq · Gemini · VLMs · STT / TTS<br>
**Vision:** YOLO · NVIDIA DeepStream · OpenCV · re-identification · anomaly detection<br>
**Backend:** Python · FastAPI · Flask · Node.js · PostgreSQL · MongoDB · SQLite · MinIO<br>
**Frontend:** Next.js · React · TypeScript · Tailwind
