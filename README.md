<div align="center">

# 💎 LifeSync
### *The Ultimate AI-Powered Ecosystem for Holistic Life Optimization*

[![GitHub stars](https://img.shields.io/github/stars/Aayush1904/life_sync?style=for-the-badge&color=2dd4bf)](https://github.com/Aayush1904/life_sync/stargazers)
[![GitHub license](https://img.shields.io/github/license/Aayush1904/life_sync?style=for-the-badge&color=10b981)](https://github.com/Aayush1904/life_sync/blob/main/LICENSE)
[![Next.js](https://img.shields.io/badge/Next.js-15-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-4.0-38bdf8?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)

---

**LifeSync** is a premium, high-performance intelligence hub that streamlines your **Health, Education, and Finance** into a single, cohesive digital experience. Powered by state-of-the-art AI models, it doesn't just manage your data—it interprets it to help you live a synchronized, optimized life.

[Explore the App](#-installation--setup) • [Core Features](#-features) • [Tech Stack](#-tech-stack) • [Timeline](#-project-timeline-1-month-gantt-chart)

</div>

---

## 📖 Project Overview
LifeSync is designed for the high-achiever who values time and mental clarity. In an era of informational chaos, LifeSync acts as your personal "Chief of Staff," utilizing **Google Gemini** and **OpenRouter** to synthesize complex life data into simple, actionable insights. Whether you are conducting academic research, tracking biological metrics, or optimizing your investment portfolio, LifeSync ensures every piece of data works in your favor.

## ⚠️ Problem Statement
The modern digital life is a collection of silos. Users are forced to juggle:
- **Educational Silos:** Scattered bookmarks and half-finished research notes.
- **Health Silos:** Wearable data that provides numbers but no context.
- **Financial Silos:** Banking apps that show *where* money went, but not *how* to grow it.
- **The Result:** Mental fragmentation and decision fatigue.

## ✨ Solution Description
**LifeSync** bridges these gaps by creating a **Unified Intelligence Layer (UIL)**. By centralizing these domains within a single workspace, the application allows for cross-domain insights. Imagine an AI that suggests educational resources based on your health goals or adjusts your financial savings plan based on your academic costs—that is the future LifeSync is building.

---

## 🛠️ Features

### 🎓 **Intelligent Education & Research**
*   **AI Research Agent:** Multi-step reasoning to crawl, summarize, and report on complex topics.
*   **Semantic Search:** Context-aware search that understands *intent*, not just keywords.
*   **Automated Bibliographies:** Instant source tracking and citation generation.

### � **Clinical Health Intelligence**
*   **Hyper-Personalized Diagnosis:** Input symptoms or markers for AI-driven wellness reports.
*   **Syncable Health Goals:** Track sleep, nutrition, and fitness with intelligent feedback loops.
*   **Preventative Advice:** Real-time insights focused on longevity and peak performance.

### � **Financial Engineering**
*   **Dynamic Budgeting:** Real-time tracking of inflows and outflows with categorical analysis.
*   **Wealth Milestones:** Goal-oriented tracking (e.g., Home, Education, Retirement).
*   **Saving Optimizations:** Tailored expense reduction strategies suggested by AI logic.

### � **Experience Design (UX)**
*   **Aesthetic Dark Mode:** A visual design inspired by deep-space observations for maximum focus.
*   **Glassmorphism UI:** Modern, translucent components following the latest design trends.
*   **Fluid Animations:** Seamless interaction design powered by Framer Motion and Three.js.

---

## 💻 Tech Stack

| Layer | Technologies |
|---|---|
| **Frontend** | ![Next.js](https://img.shields.io/badge/-Next.js-black?logo=next.js) ![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=black) ![Tailwind](https://img.shields.io/badge/-TailwindCSS-38BDF8?logo=tailwind-css&logoColor=white) |
| **Backend** | ![Node.js](https://img.shields.io/badge/-Node.js-339933?logo=node.js&logoColor=white) ![Server Actions](https://img.shields.io/badge/-Server_Actions-black) |
| **AI Engine** | ![Gemini](https://img.shields.io/badge/-Google_Gemini-4285F4?logo=google&logoColor=white) ![OpenAI](https://img.shields.io/badge/-OpenAI_GPT4-412991?logo=openai) ![Vercel AI SDK](https://img.shields.io/badge/-Vercel_AI-black) |
| **Database** | ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?logo=postgresql) ![Prisma](https://img.shields.io/badge/-Prisma-2D3748?logo=prisma) |
| **Auth** | ![Clerk](https://img.shields.io/badge/-Clerk_Auth-6C47FF?logo=clerk&logoColor=white) |
| **Visuals** | ![Framer Motion](https://img.shields.io/badge/-Framer_Motion-0055FF?logo=framer&logoColor=white) ![Three.js](https://img.shields.io/badge/-Three.js-black?logo=three.js) |

---

## 🏗️ System Architecture
LifeSync utilizes a **Type-Safe Full-Stack Architecture**:
1.  **Direct-to-Client Streaming:** AI responses are streamed directly to the frontend using Vercel AI SDK to reduce latency and improve the "human" feel of interactions.
2.  **Contextual Persistence:** A centralized PostgreSQL database ensures that AI insights are persistent and learn from user history over time.
3.  **Encapsulated Logic:** Prisma ORM acts as a robust middle-layer, ensuring that data integrity is maintained across all Health and Finance modules.
4.  **Global Store:** Zustand is used to manage transient states like search queries and UI modes without the overhead of Redux.

---

## ⚙️ Installation & Setup

### 📋 Prerequisites
*   **Node.js** v20+ 
*   **npm** or **pnpm**
*   **PostgreSQL** Instance (Vercel Postgres or Neon.tech recommended)

### 🚀 Quick Start
```bash
# Clone the repository
git clone https://github.com/Aayush1904/life-sync.git

# Enter the directory
cd life_sync

# Install premium dependencies
npm install

# Set up your environment variables
touch .env # Then fill in your keys (see .env.example)

# Sync the database schema
npx prisma generate
npx prisma db push

# Launch the experience
npm run dev
```

---

## 📂 Folder Structure
```text
📦 life_sync
 ┣ 📂 app               # Next.js App Router (Layouts, Pages, APIs)
 ┣ 📂 components        # Design System (UI, Shared, KokonutUI)
 ┣ 📂 lib               # Core Logic (Prisma, Shared Utils)
 ┣ 📂 prisma            # Database Schema & Migrations
 ┣ 📂 public            # Assets (Lottie, SVGs, Next Images)
 ┣ 📂 store             # Zustand States
 ┣ 📂 hooks             # Custom React Lifecycle Hooks
 ┗ 📜 package.json      # Dependencies & Scripts
```

---

## 📅 Project Timeline (1-Month Gantt Chart)

| Task Name | Week 1 | Week 2 | Week 3 | Week 4 | Dependency |
|-----------|:---:|:---:|:---:|:---:|-----------|
| Requirement Analysis | █ | – | – | – | None |
| UI/UX Prototype | █ | ░ | – | – | Design |
| Database Architecture | █ | – | – | – | Prisma |
| Auth System (Clerk) | ░ | █ | – | – | Setup |
| Core Service Logic | ░ | █ | ░ | – | Backend |
| Frontend Dashboard | ░ | █ | █ | – | Components |
| AI Integration (Gemini)| – | ░ | █ | – | API Keys |
| Cross-Module Sync | – | – | █ | – | Testing |
| QA & Bug Squashing | – | – | ░ | █ | Feedback |
| Performance Audit | – | – | – | █ | Optimization |
| Vercel Deployment | – | – | – | █ | Completion |
| Final Documentation | – | – | – | █ | README |

---

## 🚀 Future Enhancements
- [ ] **Biometric API Integration:** Real-time data from Oura, Whoop, and Apple Watch.
- [ ] **AI-Driven Investment Advisor:** Automated portfolio balancing based on risk tolerance.
- [ ] **Knowledge Graphs:** Visual representation of your research topics and their connections.
- [ ] **Voice-Activated LifeSync:** Integration with Siri/Google Assistant for voice logging.

## 🤝 Contributing
1. Open an issue for discussion.
2. Fork the repo and create your feature branch.
3. Submit a PR with detailed change-logs.

## 📄 License
This project is licensed under the **MIT License**.

---
<div align="center">
Built with ❤️ by LifeSync Team. 
</div>
