---
layout: workshop
title: "Getting Started with Spec Kit v0.3.0"
permalink: /
---

# Getting Started with Spec Kit v0.3.0

> **Stop vibe coding. Start specifying.**

A hands-on workshop for [GitHub Spec Kit](https://github.com/github/spec-kit) — **18 scenarios** across 4 difficulty levels that teach you Spec-Driven Development by building real software.

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/shinyay/getting-started-with-spec-kit-v0.3.0)

---

## 💡 What is Spec-Driven Development?

You prompt an AI, get unpredictable code, and spend hours fixing what it guessed wrong.

**Spec-Driven Development (SDD)** flips that. You write a structured specification *first*, then the AI follows it — producing predictable, high-quality output every time.

| Phase | What You Do |
|-------|-------------|
| **1. Constitution** | Define project principles and constraints |
| **2. Specify** | Describe what you want to build |
| **3. Clarify** | Surface hidden assumptions ← *this is where SDD pays off* |
| **4. Plan** | Choose architecture and technology |
| **5. Tasks** | Break down into executable steps |
| **6. Implement** | Generate code from specifications |

The **Clarify** step is where SDD pays off: Spec Kit surfaces the hidden assumptions and edge cases you didn't think about — *before* a single line of code is written.

---

## 🎯 Workshop Scenarios

### ⭐ Beginner — Start Here

No server, no database. Pure frontend or single-file apps. Focus on learning the SDD workflow itself.

| Step | Scenario | What You Build | Duration |
|------|----------|----------------|----------|
| 1 | [QuickRetro](steps/1/) | Team retrospective board | ~90 min |
| 2 | [Pomodoro Timer](steps/2/) | Focus timer + task tracker | ~90 min |
| 3 | [MarkdownPad](steps/3/) | Note-taking app with preview | ~90 min |
| 4 | [RecipeBox](steps/4/) | Recipe collection + meal planner | ~90 min |

### ⭐⭐ Intermediate — Add a Server

Node.js + Express + SQLite. First exposure to server-side APIs, databases, and HTTP contracts.

| Step | Scenario | What You Build | Duration |
|------|----------|----------------|----------|
| 5 | [LogSaw CLI](steps/5/) | Cross-platform log parser | ~100 min |
| 6 | [ShortLink](steps/6/) | URL shortener + analytics | ~100 min |
| 7 | [KanbanFlow](steps/7/) | Task board with drag-and-drop | ~100 min |
| 8 | [MoneyTrail](steps/8/) | CSV importer + spending reports | ~100 min |

### ⭐⭐⭐ Advanced — Production Realism

External services, auth, financial correctness, multi-tenancy, brownfield constraints.

| Step | Scenario | What You Build | Duration |
|------|----------|----------------|----------|
| 9 | [Field Inspection PWA](steps/9/) | Offline-first mobile app | ~120 min |
| 10 | [OIDC SSO + RBAC](steps/10/) | Enterprise auth system | ~120 min |
| 11 | [Stripe Subscriptions](steps/11/) | Billing + dunning flow | ~120 min |
| 12 | [Terraform + GitHub Actions](steps/12/) | Infrastructure-as-Code pipeline | ~120 min |
| 13 | [API Versioning](steps/13/) | v1→v2 migration with compatibility | ~110 min |

### ⭐⭐⭐⭐ Expert — Distributed Systems

Concurrency, real-time, high-throughput, platform extensibility. Explicit failure models required.

| Step | Scenario | What You Build | Duration |
|------|----------|----------------|----------|
| 14 | [Collaborative Whiteboard](steps/14/) | Real-time drawing canvas | ~120 min |
| 15 | [Event Ingestion Pipeline](steps/15/) | IoT data pipeline | ~120 min |
| 16 | [OrderFlow Saga](steps/16/) | Distributed order fulfillment | ~120 min |
| 17 | [PlugKit Runtime](steps/17/) | Plugin sandbox platform | ~120 min |
| 18 | [FlagShip](steps/18/) | Feature flag experimentation | ~120 min |

---

## 📚 Learning Paths

| Path | Duration | Recommended Scenarios |
|------|----------|----------------------|
| **Quick intro** | 90 min | Scenario A (QuickRetro) |
| **Half-day workshop** | 4–5 hours | A → M or N |
| **Full-day workshop** | 8 hours | A → J or K → M → N → one ⭐⭐⭐ |
| **Advanced track** | 8+ hours | M → D → P → R |
| **Team training** | Varies | Everyone does A, then self-selects by level |

---

## 🛠️ Tech Stack

- **Spec Kit** v0.3.0 (pinned for reproducibility)
- **Python 3.13** + uv package manager
- **Node.js** LTS
- **GitHub Copilot** + Copilot Chat
- **GitHub Codespaces** (zero local setup)

👉 [Get Started →](setup/)
