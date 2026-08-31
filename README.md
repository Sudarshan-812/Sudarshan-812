# Sudarshan Kulkarni, Full-Stack AI Systems Engineer

Building production AI systems close to the metal.
Voice AI · RAG · Agentic Pipelines · Real-Time Infrastructure

> 🔨 Currently building **GramOS**, an AI risk-intelligence platform for rural-enterprise lending.

## 🌐 Socials
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?logo=vercel&logoColor=white)](https://www.sudarshank.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sudarshankbuilds/)
[![X](https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white)](https://x.com/Sudarshan_dev8)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:sudarshan.builds@gmail.com)

---

## 🚀 What I'm Building

Independent AI systems I've designed and built end to end:

| Project | What It Does | Stack |
|---------|-------------|-------|
| **GramOS** *(building now)* | B2B risk-intelligence platform for lenders to rural micro-enterprises. A LangGraph multi-agent pipeline fuses alternative transaction data, India-WRIS government climate signals and real sugar-mill payment-arrears data into an explainable, auditable NPA risk score, weeks before a missed payment would flag it. | Next.js 16 · FastAPI · LangGraph · Gemini · Supabase · Pydantic · India-WRIS |
| **[Cortex](https://cortex.sudarshank.com)** | Multi-tenant RAG SaaS for chatting with your documents. Hybrid pgvector plus Postgres BM25 retrieval fused with Reciprocal Rank Fusion, Gemini re-ranking, an agentic web-search decision (Tavily), and token-by-token SSE streaming with clickable citations. | Next.js 16 · pgvector · PostgreSQL · RRF · Gemini · Tavily · Upstash Redis · SSE |
| **[Column8](https://column8.sudarshank.com)** | Voice interview simulator plus ATS scoring SaaS. Razorpay subscription billing, HMAC webhook verification, plan-based feature gating, and an Upstash Redis sliding-window rate limiter on live endpoints. | Next.js · FastAPI · Supabase · Upstash Redis · LiveKit · Deepgram · Groq · Razorpay |
| **[Nexus](https://github.com/Sudarshan-812/livekit-voice-agent)** | Real-time WebRTC voice agent grounded in your own documents. Sub-535 ms P95 voice-to-voice, true barge-in in roughly 65 ms, and a dual-stage semantic turn-taking arbiter (regex fast path plus a bounded LLM call) that ignores backchannels and mid-thought pauses. | Python · LiveKit · Deepgram · Groq · ChromaDB · FastAPI · Next.js · Docker |
| **[Plum Claims](https://github.com/Sudarshan-812/plum-claims)** | Deterministic LangGraph pipeline for health-insurance claims adjudication. Persistent state serialization, Human-in-the-Loop `interrupt_before` breakpoints for high-value claims, and legally compliant JSON audit ledgers for every reasoning state. | Python · FastAPI · LangGraph · Gemini Vision · PostgreSQL · Pydantic |
| **[Clary](https://github.com/Sudarshan-812/askfirst-clary-engine)** | Two-stage agentic clinical reasoning engine. Strict Pydantic schema enforcement rejects malformed LLM output, and model-fallback circuit breakers keep the pipeline running through rate limits and provider failures. | Python · Pydantic · FastAPI · Gemini API |
| **Kavya** | Bilingual outbound voice AI for NBFC loan collections. An 8-branch conversation state machine (Hindi, Hinglish, English), omnichannel state hydration via Upstash Redis so a dropped call resumes over WhatsApp, and a pre-flight prompt-injection and PII-redaction layer. RBI and TRAI compliant. | Bolna · Deepgram · Groq · Python · Hindi/Hinglish |

---

## 💻 Tech Stack

### AI & Voice
![Anthropic](https://img.shields.io/badge/Anthropic_Claude-000000?style=for-the-badge&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white)
![Deepgram](https://img.shields.io/badge/Deepgram-101010?style=for-the-badge&logoColor=white)
![LiveKit](https://img.shields.io/badge/LiveKit-0F9D58?style=for-the-badge&logoColor=white)

Also: LangGraph, multi-agent pipelines, RAG, hybrid search (RRF), vector embeddings, agentic tool-calling, ChromaDB.

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

- **GramOS**: LangGraph StateGraph that fans out four parallel Gemini analysis agents plus one deterministic, fully auditable scoring node, then a synthesis node that is forbidden from recomputing the score. Real inputs include Karnataka RTI sugar-mill arrears data and India-WRIS rainfall and groundwater readings.
- **Cortex**: hybrid retrieval (pgvector plus Postgres BM25) fused with Reciprocal Rank Fusion in a single SQL function, Matryoshka 768-dim embeddings, and a zero-latency SSE layer that flushes partial answers to the database on client disconnect.
- **Nexus**: sub-535 ms P95 voice-to-voice on a real WebRTC stack, with a barge-in multiplexer that cancels in-flight generation and purges the TTS and playout buffers in roughly 65 ms.
- **Column8**: live SaaS with real paying users, Razorpay subscriptions with HMAC webhook verification, plan-based gating, and Redis sliding-window rate limiting on live-facing endpoints.
- **Plum Claims**: fault-tolerant LangGraph adjudication with persistent checkpointing and Human-in-the-Loop breakpoints, producing an immutable JSON audit ledger for every reasoning state.
- **Kavya**: 8-branch RBI and TRAI compliant bilingual collections voice AI with omnichannel state recovery across voice and WhatsApp.

---

## 🧠 About Me

Sudarshan Kulkarni
