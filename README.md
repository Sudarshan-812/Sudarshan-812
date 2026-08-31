# Sudarshan Kulkarni — Full-Stack AI Systems Engineer

Building production AI systems close to the metal.
Voice AI · RAG · Agentic Pipelines · Real-Time Infrastructure

> 🔨 Currently building **GramOS**.

## 🌐 Socials
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?logo=vercel&logoColor=white)](https://www.sudarshank.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sudarshankbuilds/)
[![X](https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white)](https://x.com/Sudarshan_dev8)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:sudarshan.builds@gmail.com)

---

## 🚀 What I'm Building

Production AI systems shipped independently:

| Project | What It Does | Stack |
|---------|-------------|-------|
| **GramOS** | In progress — building now | _more soon_ |
| **[Cortex](https://cortex.sudarshank.com)** | Multi-tenant RAG platform — hybrid pgvector + BM25 search fused via RRF, custom zero-latency SSE token streaming, automated Ragas/Braintrust eval pipelines | Python · pgvector · PostgreSQL · RRF · SSE · Claude API · Ragas · Braintrust · Next.js |
| **[Column8](https://column8.sudarshank.com)** | Voice interview simulator + ATS scoring SaaS — Razorpay subscriptions, HMAC webhook verification, plan-based feature gating | Next.js · FastAPI · Supabase · Upstash Redis · LiveKit · Deepgram · Groq · Razorpay |
| **[Nexus](https://github.com/Sudarshan-812/livekit-voice-agent)** | Real-time WebRTC voice agent — sub-580ms turn-taking, Silero VAD barge-in kill-switch, live model failover | Python · asyncio · LiveKit WebRTC · Deepgram · Groq · ChromaDB · Docker |
| **[Plum Claims](https://github.com/Sudarshan-812/plum-claims)** | Deterministic LangGraph pipeline for health-insurance claims adjudication — Human-in-the-Loop breakpoints, JSON audit ledgers | Python · FastAPI · LangGraph · Gemini Vision · PostgreSQL · Pydantic |
| **[Clary](https://github.com/Sudarshan-812/askfirst-clary-engine)** | Two-stage agentic clinical reasoning engine — strict Pydantic schema enforcement, model-fallback circuit breakers | Python · Pydantic · FastAPI · Gemini API |
| **Kavya** | Bilingual outbound voice AI for NBFC collections — 8-branch state machine, omnichannel Redis state hydration, RBI/TRAI compliant | Bolna · Deepgram · Groq · Python · Hindi/Hinglish |

---

## 💻 Tech Stack

### AI & Voice
![Anthropic](https://img.shields.io/badge/Anthropic_Claude-000000?style=for-the-badge&logo=anthropic&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Deepgram](https://img.shields.io/badge/Deepgram-101010?style=for-the-badge&logoColor=white)
![LiveKit](https://img.shields.io/badge/LiveKit-0F9D58?style=for-the-badge&logoColor=white)

Also: LangGraph · RAG pipelines · hybrid search (RRF) · vector embeddings · agentic tool-calling · ChromaDB · Ragas · Braintrust

### Backend
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![PostgreSQL](https://img.shields.io/badge/postgresql-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

### Frontend
![Next.js](https://img.shields.io/badge/next.js-%23000000.svg?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Tailwind CSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Infrastructure
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-131415?style=for-the-badge&logo=railway&logoColor=white)

---

## 📊 Engineering Highlights

- **Cortex** — hybrid RAG (pgvector + BM25 fused via RRF) with a custom zero-latency SSE token-streaming layer; automated Ragas/Braintrust eval pipelines to trace context alignment and cut hallucination frequency.
- **Column8** — live SaaS with real paying users; Razorpay subscription monetization with HMAC webhook verification, plan-based feature gating, and an Upstash Redis sliding-window rate limiter on live-facing endpoints.
- **Nexus** — sub-580ms end-to-end voice turn-taking on Indian cellular networks; Silero VAD barge-in kill-switch cancelling in-flight tasks within ~45ms of user speech, plus live model failover to backup endpoints.
- **Kavya** — 8-branch RBI/TRAI-compliant bilingual (Hindi/Hinglish) collections voice AI with omnichannel state recovery across voice and WhatsApp.
- **Plum Claims** — fault-tolerant LangGraph adjudication pipeline with Human-in-the-Loop `interrupt_before` breakpoints and legally compliant JSON audit ledgers for every reasoning state.

---

## 🧠 About Me

Self-taught AI engineer based in Bengaluru.

I don't use LangChain. I build close to the metal so every layer is debuggable and every failure is traceable.

Currently building **GramOS**.

---

_Last updated: September 2026_
