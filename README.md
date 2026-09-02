<h1 align="center">Hi, I am Tibor Vamos</h1>
<p align="center">
  AI engineer. I put LLMs into production workflows where wrong answers have consequences.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/tiborvamos">LinkedIn</a> •
  <a href="mailto:tibor.vamos@proton.me">Email</a> •
  <a href="https://github.com/vamostibor03?tab=repositories">Repositories</a>
</p>

---

## What I build

Three years building software for enterprise clients across Austria, Germany and the
Netherlands — most of it AI features inside regulated products, where "the model
usually gets it right" isn't good enough.

- **Document AI** — schema-constrained extraction that turns unstructured PDFs into
  structured records, with provenance tracking so AI-extracted and human-corrected
  values stay distinguishable and auditable.
- **Retrieval-augmented assistants** — grounded Q&A over private document sets with
  cited sources, instead of open-ended generation.
- **Agent systems** — tool-calling agents with explicit execution traces, deterministic
  fallbacks and human approval gates on anything consequential.
- **Local-first AI** — Ollama, LM Studio, llama.cpp and faster-whisper for workloads
  that cannot leave the machine.

## How I think about LLMs

Treat model output as untrusted input. Prefer a constrained schema over free text, a
deterministic path over a clever prompt, and a narrow tool over a broad one. Most of
the engineering in an AI feature is the part that runs *around* the model — validation,
grounding, guardrails and a way for a human to see what happened and why.

## Featured projects

| Project | What it is |
|---|---|
| [clipper-studio](https://github.com/vamostibor03/clipper-studio) | Long video into vertical short-form clips. Local Whisper transcription, LLM clip selection with virality scoring, active-speaker reframing, burned-in captions. Tiered model routing with cost tracking. |
| [trendforge](https://github.com/vamostibor03/trendforge) | Trend-to-design agent. 15 signal collectors feed multi-agent local-LLM ideation, IP-risk filtering and diffusion rendering to print-resolution masters. Runs entirely on one machine. |
| [ollama-calendar-agent](https://github.com/vamostibor03/ollama-calendar-agent) | Desktop chat app where a local model manages Google Calendar through tool calls. Each capability is an auto-discovered tool folder. |
| [fridge-keeper](https://github.com/vamostibor03/fridge-keeper) | Photograph a receipt, a local model reads it, and your home inventory and price history update themselves. No cloud OCR, no API bill. |
| [zepp-health-agent](https://github.com/vamostibor03/zepp-health-agent) | Scheduled service pulling wearable health data into SQLite, computing 7/30/90-day trends and delivering an LLM daily report to Telegram. |

Client work is under NDA and stays private. The largest is a ~370k-line Austrian
legal-tech platform where I am the top contributor (573 of 1,777 commits), covering
AI invoice intake, payments, and electronic court filing.

## Tech stack

**AI / LLM**  
LLM application design · agents & tool calling · structured output · RAG & embeddings ·
document AI & OCR · Whisper / faster-whisper · local inference (Ollama, LM Studio,
llama.cpp) · multi-model routing · MCP servers · OpenAI, Anthropic, Gemini, OpenRouter

**Languages**  
TypeScript · Python · JavaScript · SQL

**Backend**  
Fastify · FastAPI · Node.js · PostgreSQL · Supabase · Azure SQL · SQLite

**Frontend**  
React · TanStack · Vite · Tailwind · React Native

**Cloud and DevOps**  
Azure (Container Apps, Entra ID, Managed Identity, Bicep) · Docker · GitHub Actions ·
Railway · Vercel · Cloudflare Workers

## Contact

- Email: `tibor.vamos@proton.me`
- LinkedIn: `linkedin.com/in/tiborvamos`
- Location: Vienna, Austria
