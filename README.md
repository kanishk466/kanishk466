<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=200&section=header&text=Kanishk%20Singh%20Maurya&fontSize=42&fontColor=ffffff&fontAlignY=40&desc=Backend%20Engineer%20%C2%B7%20Node.js%20%C2%B7%20PostgreSQL%20%C2%B7%20AWS&descAlignY=62&descSize=18&descColor=e0e0e0" width="100%"/>

**I build scalable, secure backend systems, from multi-tenant healthcare APIs to real-time platforms and AI agents.**

📍 Noida, India &nbsp;·&nbsp; 🟢 Open to backend &amp; full-stack roles

<a href="mailto:kanishkas466@gmail.com"><img src="https://img.shields.io/badge/Email-2C5364?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://linkedin.com/in/kanishk007"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/kanishk466"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>

<br/>

[About](#-about) · [Skills](#-tech-stack) · [Projects](#-featured-projects) · [Experience](#-experience) · [Education](#-education)

</div>

---

## 👨‍💻 About

Backend engineer with **3+ years** of experience shipping production systems in Agile teams. I own features end to end: schema design, API architecture, cloud deployment and CI/CD.

| | |
|:--|:--|
| 🏥 **Domain depth** | Multi-tenant healthcare backend with strict data isolation and row-level security |
| ⚡ **Real-time** | WebSockets, SSE and Redis pub/sub, with zero-polling live updates |
| 🔐 **Security** | Centralized JWT + RBAC auth service used across 5+ production apps |
| 🤖 **Now exploring** | Agentic AI backends: routers, tool use, RAG and human handoff |
| 📈 **Performance** | Faster APIs through query optimization, indexing and Redis caching |

---

## 🛠️ Tech Stack

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=nodejs,express,nestjs,ts,js,postgres,mongodb,redis,mysql,aws,docker,githubactions,react,py,fastapi,git&theme=dark&perline=8"/>
  <img src="https://skillicons.dev/icons?i=nodejs,express,nestjs,ts,js,postgres,mongodb,redis,mysql,aws,docker,githubactions,react,py,fastapi,git&theme=light&perline=8" alt="Tech stack"/>
</picture>
</div>

<br/>

| Area | Technologies |
|:--|:--|
| **Backend** | Node.js, Express, NestJS, Fastify, REST APIs, Microservices |
| **Databases** | PostgreSQL, MongoDB, MySQL, Redis, TypeORM |
| **Real-time** | Socket.IO, WebSockets, Server-Sent Events, Redis Pub/Sub, BullMQ |
| **AI &amp; RAG** | LangGraph, Qdrant, Pinecone, Gemini, Groq, OpenAI |
| **Auth &amp; Security** | JWT, RBAC, rate limiting, input validation |
| **Cloud &amp; DevOps** | AWS, Docker, GitHub Actions, PM2, CI/CD |
| **Testing &amp; Tools** | Jest, Mocha, Postman, Git |

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🤖 Multi-Agent Support System
![status](https://img.shields.io/badge/status-in%20progress-orange?style=flat-square)

Live chat where a **Router Agent** classifies each message and sends it to a tech, billing or sales agent. Answers come from **RAG** over company docs, with automatic **ticket handoff** to a human when confidence drops.

- Confidence-based routing and handoff
- Every reply shows agent, intent, confidence and sources
- `npm run doctor` validates each dependency with actionable hints
- Runs with zero API keys and zero databases

**Stack:** NestJS · Socket.IO · LangGraph · Qdrant · Redis · PostgreSQL

[![Code](https://img.shields.io/badge/View%20Code-2C5364?logo=github&logoColor=white&style=flat-square)](https://github.com/kanishk466/multi-agent-support)

</td>
<td width="50%" valign="top">

### 🧠 AI Agent with Real Tools (ReAct)
![status](https://img.shields.io/badge/status-live-2ea44f?style=flat-square)

An agent that **plans, searches the web, runs code, scrapes pages, does math and writes reports**, then answers with cited sources while streaming its reasoning live.

- ReAct loop with 5 tools
- Guardrails: cost cap, timeout, iteration limit, per-IP daily budget
- Live SSE stream of thoughts, actions and observations
- Gemini primary with Groq fallback on rate limits

**Stack:** Fastify · TypeScript · Gemini · Groq · Redis · PostgreSQL

[![Code](https://img.shields.io/badge/View%20Code-2C5364?logo=github&logoColor=white&style=flat-square)](https://github.com/kanishk466/ai-agent)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📄 PDF Q&amp;A System (RAG)
![status](https://img.shields.io/badge/status-live-2ea44f?style=flat-square)

Upload a PDF, ask questions in plain language and get answers with **page-level citations**. Ingestion runs in the background through a queue.

- Recursive chunking (500 tokens, 50 overlap) with page tracking
- BullMQ + Redis ingestion: upload returns `202`, poll until `ready`
- Citations include page ranges and similarity scores
- Offline mode with local embeddings and an in-process vector store

**Stack:** Fastify · TypeScript · OpenAI · Pinecone · BullMQ · PostgreSQL

[![Code](https://img.shields.io/badge/View%20Code-2C5364?logo=github&logoColor=white&style=flat-square)](https://github.com/kanishk466/pdf-qa-system)

</td>
<td width="50%" valign="top">

### 🏏 CricStars (Freelance)
![status](https://img.shields.io/badge/status-delivered-2C5364?style=flat-square)

Real-time cricket platform streaming live scores to many concurrent users over WebSockets, built and deployed end to end.

- Live score streaming at scale
- Owned API design, DB schema, cloud deployment and monitoring

**Stack:** Node.js · MongoDB · WebSockets · AWS

</td>
</tr>
</table>

---

## 💼 Experience

### Backend Developer · ItDose Infosystem Pvt Ltd
`Feb 2025 – Present` · Noida, India
<sub>Node.js · Express · PostgreSQL · Redis · SSE</sub>

- Architected a **multi-tenant healthcare backend** with strict data isolation, row-level security and scalable schemas
- Built REST APIs for telemedicine, patient management, care plans and clinical interventions
- Shipped **real-time notifications** via SSE + Redis pub/sub, removing client polling
- Enforced **JWT + RBAC** across all endpoints
- Reduced API latency with Redis caching and PostgreSQL query optimization

### Backend Developer (Freelance) · MERN Stack
`Sep 2024 – Jan 2025` · Remote
<sub>Node.js · MongoDB · WebSockets</sub>

- Built a complete food-ordering backend: REST APIs, MongoDB modeling, CMS integration and order lifecycle
- Delivered **CricStars** with live score streaming over WebSockets
- Owned delivery end to end: API design, schema, deployment and production monitoring

### Software Engineer, Backend · Techharvest Solutions Pvt Ltd
`May 2023 – Aug 2024` · India
<sub>Node.js · JWT · Redis</sub>

- Designed a **centralized JWT auth microservice** used by 5+ internal apps, cutting duplicated auth logic by **60%**
- Improved API response times through query optimization and Redis caching
- Applied API security practices: rate limiting, validation and secure token handling

---

## 📊 GitHub Stats

<div align="center">
<img src="https://github-readme-stats.vercel.app/api?username=kanishk466&show_icons=true&theme=transparent&hide_border=true&count_private=true" height="160"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=kanishk466&layout=compact&theme=transparent&hide_border=true" height="160"/>
</div>

---

## 🎓 Education

**B.Tech, Computer Science &amp; Engineering** · VITS Satna · 2019 – 2023 · CGPA 8.15

---

<div align="center">

**Let's build something scalable.** &nbsp; 📧 [kanishkas466@gmail.com](mailto:kanishkas466@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,50:203A43,100:0F2027&height=100&section=footer" width="100%"/>

</div>
