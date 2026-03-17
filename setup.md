---
layout: step
title: "Setup — Getting Started"
step_number: 0
permalink: /setup/
---

# Setup — Getting Started

Get your workshop environment ready in under 5 minutes. No local installation required.

---

## Prerequisites

- ✅ A **GitHub account**
- ✅ Access to **[GitHub Copilot](https://github.com/features/copilot)** (Free, Pro, or Enterprise)
- ✅ A modern web browser (Chrome, Edge, Firefox, or Safari)

> **That's it!** No local tools, no downloads, no configuration. Everything runs in GitHub Codespaces.

---

## Step 1: Launch Codespaces

Click the button below to open a fully configured development environment:

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/shinyay/getting-started-with-spec-kit-v0.3.0)

The Dev Container automatically installs:
- **Python 3.13** + uv package manager
- **Node.js** LTS
- **Spec Kit CLI** (`specify`) v0.3.0
- **GitHub Copilot** + Copilot Chat extensions
- **GitLens** + Git Graph

---

## Step 2: Verify Your Setup

Once Codespaces is ready, open the terminal and run:

```bash
specify --version
```

You should see `v0.3.0` (or similar). If the command is not found, run:

```bash
pip install specify-cli==0.3.0
```

---

## Step 3: Initialize Spec Kit

In the terminal, initialize Spec Kit with Copilot as the AI backend:

```bash
specify init . --ai copilot
```

This configures your workspace for Spec-Driven Development.

---

## Step 4: Pick a Scenario

Open the **Scenarios** directory and choose one based on your experience level:

| Level | Recommended First Scenario |
|-------|---------------------------|
| ⭐ **Beginner** | [A: QuickRetro](../steps/1/) — Simplest domain, teaches the full workflow |
| ⭐⭐ **Intermediate** | [M: ShortLink](../steps/6/) — API contracts, HTTP semantics |
| ⭐⭐⭐ **Advanced** | [D: Stripe Subscriptions](../steps/11/) — State machines, billing |
| ⭐⭐⭐⭐ **Expert** | [P: OrderFlow Saga](../steps/16/) — Distributed transactions |

---

## Step 5: Follow the SDD Workflow

Every scenario follows the same 6-phase workflow using `/speckit.*` commands in Copilot Chat:

1. **`/speckit.constitution`** — Define project principles and constraints
2. **`/speckit.specify`** — Describe what you want to build
3. **`/speckit.clarify`** — Surface hidden assumptions (run multiple rounds!)
4. **`/speckit.plan`** — Choose architecture and technology
5. **`/speckit.tasks`** — Break down into executable steps
6. **`/speckit.implement`** — Generate code from specifications

> 💡 **Tip:** The **Clarify** phase is where SDD pays off. Run `/speckit.clarify` multiple times — each round surfaces ~5 new questions you didn't think about.

---

## Troubleshooting

| Issue | Solution |
|-------|----------|
| `specify` command not found | Run `pip install specify-cli==0.3.0` |
| Copilot Chat not available | Ensure you have Copilot access and the extension is installed |
| Codespaces won't start | Try creating a new Codespace from the repository page |
| `/speckit.*` commands don't work | Run `specify init . --ai copilot` first |

👉 **Ready?** [Choose a scenario and start building →](../steps/1/)
