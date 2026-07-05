# 🏛️ Meridian — AI-Powered Board Management Module
### Pre-Internship Product Assignment | Getway AI
**Submitted by:** Devguru Tiwari

---

## 🔗 Live Demo

> **[▶ View Interactive Prototype](https://devguru-codes.github.io/meridian_pre_intern_work/)**

> **[🎥 Watch Demo Video](https://drive.google.com/file/d/1pQp-cEh_uGtGRS6SxAJQxjv31sh0vKFX/view?usp=sharing)**

Interactive high-fidelity prototype built to validate the proposed user experience. The prototype focuses on product workflows and UI rather than backend implementation.

---

## 📋 Assignment Overview

This repository contains all deliverables for the Getway AI pre-internship PM assignment focused on designing a **Board Management module** for Meridian — an AI-first operating system for startups.

The objective was to evaluate whether Meridian should build a Board Management module, identify the highest-value founder problems, define an MVP, and validate the proposed experience through an interactive prototype.

---

## 📁 Deliverables

| # | Deliverable | File | Description |
|---|-------------|------|-------------|
| 1 | **Product Thesis** | [`Product thesis.docx`](./Product%20thesis.docx) | Core problem framing — why board management is broken and Meridian's unique position |
| 2 | **Market & User Research** | [`Research 1 - Market, Users & Pain Points.docx`](./Research%201%20-%20Market%2C%20Users%20%26%20Pain%20Points.docx) | Deep-dive into startup board governance, user segments, and validated pain points |
| 3 | **Competitive & GTM Research** | [`Research 2 - Product, Competition & GTM.docx`](./Research%202%20-%20Product%2C%20Competition%20%26%20GTM.docx) | Competitive landscape (Diligent, BoardPro, Carta, Visible.vc) + go-to-market strategy |
| 4 | **Competitor Analysis (Deep)** | [`Competitor analysis (Deep).docx`](./Competitor%20analysis%20%28Deep%29.docx) | In-depth teardown of key competitors — feature gaps, positioning, and differentiation opportunities |
| 5 | **Pain Points Analysis** | [`Pain Points.docx`](./Pain%20Points.docx) | Structured pain point matrix with evidence, root causes, and Meridian opportunities |
| 6 | **High Value Use Cases** | [`High Value Use Cases_Final.docx`](./High%20Value%20Use%20Cases_Final.docx) | 8 high-impact use cases mapped across the full board lifecycle |
| 7 | **Prioritization Matrix** | [`Prioritization Matrix.docx`](./Prioritization%20Matrix.docx) | Impact vs. Engineering Effort framework — P1/P2/P3 feature prioritization |
| 8 | **User Journey** | [`User Journey.docx`](./User%20Journey.docx) | End-to-end founder journey from scheduling a meeting to follow-up, surfacing every pain point |
| 9 | **Product Roadmap (V1/V2/V3)** | [`Roadmap (V1,V2,V3).docx`](./Roadmap%20%28V1%2CV2%2CV3%29.docx) | Phased roadmap: Foundation → Execution → Strategic AI |
| 10 | **PRD for V1 (MVP)** | [`PRD.docx`](./PRD.docx) | Full product requirements — problem, goals, user stories, functional/non-functional requirements, success metrics |
| 11 | **Build vs. Buy Analysis** | [`Build vs Buy.docx`](./Build%20vs%20Buy.docx) | Reuse / Build / Integrate strategy leveraging Meridian's shared context layer |
| 12 | **UI Prototype** | [`Meridian_prototype/`](./Meridian_prototype/) | Interactive high-fidelity prototype — live on GitHub Pages |
| 13 | **Demo Video** | [▶ Google Drive](https://drive.google.com/file/d/1pQp-cEh_uGtGRS6SxAJQxjv31sh0vKFX/view?usp=sharing) | Walkthrough recording of the full prototype flow |

---

## 🧠 The Core Problem

> *"Founders don't struggle with conducting board meetings — they struggle with preserving, retrieving, and acting on board knowledge over time."*

Early-stage startups manage board operations through a fragmented DIY stack: **Google Drive + Email + Notion + Slack + Zoom + DocuSign**. While these tools work initially, they break down as companies grow:

- Documents become scattered across multiple tools
- Decisions disappear into email threads
- Action items are forgotten post-meeting
- Founders spend **15–20 hours** reconstructing context before each meeting
- No institutional memory — "Why did we reject this pricing model?" becomes unanswerable

**Board management is not a meeting problem — it is a workflow continuity problem.**

---

## 🎯 High-Value Use Cases

### Before Meeting
| Use Case | Priority | What It Does |
|----------|----------|--------------|
| **AI Board Preparation** | P1 — V1 | Auto-generates board packs from company context, past decisions, KPIs |
| **AI Agenda Builder** | P1 — V1 | Suggests agenda based on unresolved actions and pending approvals |
| **Board Pack Review** | P1 — V1 | Detects missing data, outdated docs, and information overload |

### During Meeting
| Use Case | Priority | What It Does |
|----------|----------|--------------|
| **Live Board Intelligence** | P1 — V1 | Instantly answers investor questions using historical context |
| **Live Decision Capture** | P1 — V1 | Auto-records decisions, assigns owners, creates tasks |

### After Meeting
| Use Case | Priority | What It Does |
|----------|----------|--------------|
| **Resolution Management** | P2 — V2 | E-signature approvals, voting, immutable records |
| **AI Follow-up** | P2 — V2 | Tracks action items, deadlines, and reminders automatically |
| **Decision-to-Execution Bridge** | P2 — V2 | Routes decisions to HR, Finance, Product teams |

### Between Meetings
| Use Case | Priority | What It Does |
|----------|----------|--------------|
| **Institutional Memory** | P1 — V1 | Persistent decision timeline with context, rationale, stakeholders |
| **Board Knowledge Search** | P3 — V3 | Semantic search across all meetings, decisions, and documents |

---

## 🗺️ Product Roadmap

```
V1 — Build the Foundation (MVP)
├── AI Board Preparation
├── AI Agenda Builder
├── Board Pack Review
├── Live Board Intelligence
├── Live Decision Capture
└── Institutional Memory
    Success: Founders prep in <30 min | 80% reduction in manual effort

V2 — Connect Decisions to Execution
├── Resolution Management (e-signatures, voting)
├── AI Follow-up & Reminders
└── Decision-to-Execution Bridge (HR, Finance, Product routing)
    Success: 100% decisions assigned to owner | Zero forgotten actions

V3 — Intelligent Board Operating System
├── Board Knowledge Search (semantic, natural language)
├── Predictive Insights
├── AI Recommendations
└── Cross-module Intelligence (board + finance + hiring + product)
    Success: AI proactively surfaces strategic risks before meetings
```

---

## 🔨 Build vs. Buy Strategy

| Category | Examples | Decision |
|----------|----------|----------|
| **Reuse (Meridian Core)** | Auth, Notifications, Search, User Profiles, Shared Context Layer | ♻️ Reuse — minimize engineering effort |
| **Build New** | Board Workspace, Meeting Engine, Decision Engine, Institutional Memory, Board Permissions | 🔨 Build — core differentiators |
| **Integrate / Buy** | Calendar API, Email, E-signature, Video Meeting API, Slack/Teams, LLM Inference | 🔗 Integrate — avoid reinventing mature infrastructure |

---

## 📐 PRD Summary (V1 MVP)

**Target Users:** Startup founders (pre-seed → Series B), CEOs, Chief of Staff, Board Members, Investors

**Key Goals:**
- Single source of truth for all board operations
- < 30 minutes to prepare any board meeting
- Persistent institutional memory — no decision ever lost
- Automatic execution tracking post-meeting

**Success Metrics:**
- 80% reduction in manual prep effort
- 100% board documents stored centrally
- Historical decisions retrieved in < 10 seconds
- 40% of founders use Meridian as primary board workspace within 3 months of onboarding

**Out of Scope (MVP):** Enterprise governance, Carta-style equity management, compliance reporting, public company features

---

## 🖥️ Interactive Prototype

The live prototype demonstrates:
- **Board Dashboard** — Meeting overview and upcoming board packs
- **AI Agenda Builder** — Smart agenda generation UI
- **Board Pack View** — Document management and review flows
- **Decision Capture** — Live meeting decision recording
- **Institutional Memory** — Decision timeline and search interface

> Built for UI/UX validation only. No backend or real data.

---

## 👤 About

**Pre-Internship Product Assignment**

Getway AI

**Author:** Devguru Tiwari

*All documents represent original PM work including market research, competitive analysis, user journey mapping, prioritization, PRD writing, roadmap design, and prototype development.*
