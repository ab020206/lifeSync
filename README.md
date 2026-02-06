# 🌊 LifeSync  
### A Unified Intelligence Ecosystem for Life Orchestration

![LifeSync Banner](./public/LifeSync.png)

[![Next.js](https://img.shields.io/badge/Next.js-16-black?logo=next.js)](https://nextjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-v4-38B2AC?logo=tailwind-css)](https://tailwindcss.com/)
[![Prisma](https://img.shields.io/badge/Prisma-ORM-2D3748?logo=prisma)](https://www.prisma.io/)
[![Clerk](https://img.shields.io/badge/Auth-Clerk-6C47FF?logo=clerk)](https://clerk.dev/)
[![AI](https://img.shields.io/badge/AI-Gemini%202.0-blue?logo=google-gemini)](https://deepmind.google/technologies/gemini/)

---

## 🌟 Introduction

Modern digital life is fragmented.

We use separate apps for:
- Research and learning  
- Health tracking  
- Financial planning  
- Task management  
- Journaling and reflection  

Each tool stores data in isolation, forcing users to **manually connect the dots**. This results in:
- Cognitive overload  
- Repeated effort  
- Poor long-term decision-making  

**LifeSync** is designed to solve this fragmentation.

---

## 📌 Project Snapshot

**LifeSync** is an AI-powered personal productivity and lifestyle ecosystem that unifies multiple life domains—**Research, Health, Finance, Planning, and Journaling**—into a single intelligent system.

Instead of acting as a passive tracker, LifeSync functions as an **active intelligence layer**.  
It understands user intent, analyzes inputs, and produces structured, actionable outputs using **Generative AI (Gemini 2.0 via OpenRouter)**.

> Think of LifeSync as a personal “Chief of Staff” for your digital life.

---

## 🎯 Core Philosophy

LifeSync is built on three core ideas:

1. **Context Matters**  
   The same question should produce different answers depending on whether the user is researching finance, academics, or health.

2. **Data Should Compound**  
   Information entered once should improve future outputs across modules.

3. **Outputs Must Be Actionable**  
   Insights are valuable only when they can be exported, scheduled, or applied.

---

## 🛠️ Project Analysis & Technical Evaluation

### 🗂️ System Overview

LifeSync follows a **modular, multi-agent architecture**.

Each domain (Research, Planning, Journal, Health, Finance) is handled by a specialized AI workflow, while all modules share a **central relational database**. This allows:

- Cross-module intelligence
- Persistent user context
- Long-term learning from historical data

Unstructured human inputs (text or voice) are transformed into:
- Structured schemas
- Validated outputs
- Reusable life-data

---

### 🧪 Current Execution & Active Modules  
*Status: Backend logic implemented with active API routes*

| Module | What It Does | Status |
|------|--------------|--------|
| **Deep Research Agent** | Searches, filters, and synthesizes web knowledge intelligently | ✅ Active |
| **AI Planner** | Converts unstructured thoughts into daily schedules | ✅ Active |
| **Smart Journal** | Analyzes emotions and sentiments from journal entries | ✅ Active |
| **Health Check** | Generates structured health insights from symptoms | ✅ Active |
| **FinTrack** | Tracks budgets and financial goals | ✅ Active |

Each module is designed to function independently **and** collaboratively.

---

### 🏗️ Technical Infrastructure (Explained Simply)

- **Frontend:**  
  Built using **Next.js 16 (App Router)** for scalability and server-side intelligence.

- **Authentication:**  
  **Clerk** handles user authentication, sessions, and route protection.

- **Middleware:**  
  Global route protection is enforced via Clerk middleware.  
  > ⚠️ Note: Next.js requires this logic in `middleware.js` at the root for proper execution.

- **Database:**  
  **PostgreSQL** with **Prisma ORM** ensures structured, relational, and type-safe data storage.

- **AI Orchestration:**  
  **Vercel AI SDK** ensures AI outputs strictly follow predefined schemas using **Zod validation**.

---

## 🚀 Intelligent Research & Context-Aware “Life Modes”

### 🔍 Deep Research Agent (Neural Retrieval)

LifeSync’s research engine is **intent-aware**.  
Instead of a single generic search, it adapts using **Life Modes**.

### 📈 Finance Mode
- Automatically detects stock tickers
- Analyzes market news sentiment
- Generates structured **Investment Thesis tables**

### 🎓 Academic Mode
- Prioritizes peer-reviewed journals
- Generates APA / MLA citations
- Produces **Anki-ready flashcards** for learning

### 🩺 Healthcare Mode
- Uses verified medical sources
- Displays explicit **“Consult a Doctor”** disclaimers
- Builds symptom timelines and visit-preparation summaries

This ensures **safe, relevant, and domain-appropriate outputs**.

---

## 🕸️ Visual Knowledge Synthesis (“Brain Map”)

Text alone often hides relationships.

LifeSync introduces **visual cognition** through interactive mind maps using libraries like `react-flow`.

Users can visually explore:
- How concepts connect
- Source credibility networks
- Geographic origins of information

This helps users **understand knowledge, not just consume it**.

---

## 🧠 Intelligence Layers & Feature Ecosystem

### 🗓️ Smart AI Planner

The planner converts “brain dumps” into structured plans by:
- Identifying tasks
- Estimating effort
- Categorizing activities (Work, Health, Finance, Personal)
- Suggesting productivity insights

This reduces planning friction and mental load.

---

### 🔄 The “Syncer” — Real-Time Monitoring

LifeSync supports persistent intelligence.

When users enable **“Stay Synced”**:
- Topics are periodically re-checked
- New developments are detected
- Users receive concise **What’s New** updates

**Example:**  
> “Keep me synced on AI regulation changes for my startup.”

---

### 🎙️ Multimodal “Knowledge Seeds”

LifeSync accepts multiple input formats:

- **URL / PDF Deep-Dive**  
  Analyze large documents (50+ pages) and cross-reference them with live web data.

- **Voice Input**  
  Speak thoughts naturally for planning or research while multitasking.

---

### 📂 Actionable AI Artifacts

LifeSync focuses on **output usefulness**, not just insights.

Supported exports include:
- 📚 **Notion / Obsidian Sync**
- 📊 **Auto-generated slide decks**
- 📅 **Smart calendar event creation**

This bridges the gap between thinking and execution.

---

## 💻 Technical Stack & API Audit

### 🧱 Technology Stack

| Layer | Technology | Purpose |
|----|-----------|--------|
| Framework | Next.js 16 | App Router, APIs |
| Language | TypeScript / JavaScript | Hybrid codebase |
| AI Engine | Vercel AI SDK | Schema-based AI |
| LLM | Gemini 2.0 Flash | Reasoning & synthesis |
| Search | Exa.ai | Neural retrieval |
| Database | PostgreSQL + Prisma | Persistent state |
| Styling | Tailwind CSS v4 | UI development |
| State | Zustand | Client-side state |

---

### 🔐 API Key Usage (Transparency)

| Variable | Purpose |
|-------|--------|
| `OPENROUTER_API_KEY` | Core AI functionality |
| `EXA_SEARCH_API_KEY` | Research retrieval |
| `DATABASE_URL` | Database connection |
| `NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY` | Authentication |

---

## 🗺️ Roadmap & Future Evolution

### Immediate Improvements
- Full TypeScript migration
- Middleware standardization

### Near-Term Integrations
- Google / Outlook Calendar
- Financial aggregation APIs
- Wearable health data

### Long-Term Vision
- Cross-module intelligence correlation
- Local AI inference for privacy
- Predictive life insights

---

## 📜 License

LifeSync is licensed under the **MIT License**.