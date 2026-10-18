<div align="center">

<!-- ═══════════ HERO ═══════════ -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:03045C,45:0077B6,100:00B4D8&height=230&section=header&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Senior%20Backend%20Developer%20%7C%20Node.js%20%7C%20NestJS%20%7C%20AI%20Backends&descAlignY=59&descSize=18&descColor=caf0f8&stroke=00B4D8" width="100%"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3200&pause=900&color=00B4D8&center=true&vCenter=true&width=780&lines=I+design+backends+that+don%27t+wake+you+up+at+3+AM;Real-time+Systems+%C2%B7+Microservices+%C2%B7+AI+%26+RAG+Backends;3%2B+years+%C2%B7+5%2B+apps+secured+by+my+auth+service" alt="typing" />

<br/>

<a href="mailto:kanishkas466@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?logo=gmail&logoColor=white&style=for-the-badge"/></a>
<a href="https://linkedin.com/in/kanishk007"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white&style=for-the-badge"/></a>
<a href="https://github.com/kanishk466"><img src="https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white&style=for-the-badge"/></a>
<img src="https://komarev.com/ghpvc/?username=kanishk466&label=👀&color=00B4D8&style=for-the-badge" />

<br/>
<br/>

<a href="#-impact">Impact</a> • <a href="#-tech-stack">Stack</a> • <a href="#-featured-projects">Projects</a> • <a href="#-experience">Journey</a> • <a href="#-analytics">Stats</a>

</div>

<br/>

> ### 🚀 Currently building a **multi-agent AI support system** — LLM router → specialist agents → RAG → human handoff
> All three live projects run **offline with zero API keys**, then scale to cloud by adding env vars. *Graceful degradation is a feature, not an afterthought.*

<br/>

## 📈 Impact, not job titles

<table>
<tr>
<td align="center" width="33%">
<img src="https://img.shields.io/badge/3%2B-Years%20in%20production-00B4D8?style=for-the-badge&labelColor=0D1117&color=00B4D8" /><br/><sub>Backend systems, shipped &amp; on-call</sub>
</td>
<td align="center" width="33%">
<img src="https://img.shields.io/badge/5%2B-Apps%20secured%20by%20my%20JWT%20service-7C3AED?style=for-the-badge&labelColor=0D1117&color=7C3AED" /><br/><sub>Centralized auth microservice</sub>
</td>
<td align="center" width="33%">
<img src="https://img.shields.io/badge/60%25-Less%20auth%20code%20duplication-10B981?style=for-the-badge&labelColor=0D1117&color=10B981" /><br/><sub>After consolidating 5 services</sub>
</td>
</tr>
</table>

<br/>

## 👨‍💻 About

Backend Developer, **3 years** deep in production Node.js. I don't just write endpoints — I own the whole path: **schema → API design → auth → deployment → the pager at night**. Fast-moving Agile teams, real users, real traffic.

<table>
<tr><td width="50%">

🏥 **Multi-tenant healthcare backend** — strict isolation, row-level security, tenant-safe schemas

⚡ **Real-time** — SSE + Redis pub/sub &amp; Socket.IO score streaming, zero-polling updates

🔐 **JWT + RBAC** centralized auth used across 5+ production apps

</td><td width="50%">

🤖 **Agentic AI backends** — tool-calling loops, RAG, LLM routing, confidence-based handoff

🏎️ **Performance** — query plans, strategic indexes, Redis cache layers, measurable latency wins

🧰 **DX obsessed** — `doctor` commands, smoke tests, and zero-config offline demo modes

</td></tr>
</table>

<br/>

## 🛠️ Tech Stack

<div align="center">
<img src="https://skillicons.dev/icons?i=nodejs,express,nestjs,ts,js,postgres,mongodb,redis,mysql,aws,docker,py,fastapi,react,git,githubactions&theme=dark" />
</div>

<br/>

| | |
|:--|:--|
| **Backend** | `Node.js` `Express` `NestJS` `REST` `Microservices` `Fastify` |
| **AI &amp; Agents** | `LangGraph` `RAG` `Qdrant` `Pinecone` `Gemini` `Groq` `OpenAI` |
| **Real-time** | `Socket.IO` `SSE` `Redis Pub/Sub` |
| **Auth &amp; Security** | `JWT` `RBAC` `Rate Limiting` `Input Validation` |
| **Data** | `PostgreSQL` `MongoDB` `MySQL` `Redis` `TypeORM` |
| **Cloud &amp; DevOps** | `AWS EC2/S3` `Docker` `GitHub Actions` `PM2` `CI/CD` |
| **Testing** | `Jest` `Mocha` `Postman` `Smoke tests` |

<br/>

## 🚀 Featured Projects

<table>
<tr><td>

### 🤖 Multi-Agent Customer Support System &nbsp; <img src="https://img.shields.io/badge/building-now-F59E0B?style=flat-square" />

A live chat system where an **LLM Router** classifies each message and dispatches to a specialist agent — **tech / billing / sales** — answering via **RAG** over company docs, with automatic **ticket handoff** when confidence drops.

`NestJS` · `Socket.IO` · `LangGraph` · `Qdrant` · `Redis` · `PostgreSQL` · `Groq/Gemini`

- **Router → specialist → handoff** pipeline with per-reply *agent, intent, confidence &amp; sources* for debuggability
- **RAG** with Gemini embeddings (local hash fallback) so it demos with **zero config**
- `npm run doctor` runs a **full round-trip health check** on every dependency

```console
$ npm run doctor
[PASS] Groq LLM     qwen3.8-27b -> "OK" (260ms)
[PASS] Qdrant       upsert/query/delete round-trip OK
[PASS] PostgreSQL   messages=18  tickets=2
