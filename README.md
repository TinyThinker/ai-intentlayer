# 🧠 ai-intentlayer

A modular, composable framework for customizing AI behavior in GitHub Copilot, ChatGPT, and similar tools.

This repo helps developers treat AI tools not just as assistants, but as **context-aware collaborators**. Define personas, adjust behavioral parameters, and inject consistent expectations into every session.

---

## 🚀 Features

- ✅ Persona-based prompt presets for Copilot Chat and ChatGPT
- 🎭 Tunable attributes like praise threshold, reasoning depth, tone, etc.
- 🔁 Clone, extend, and compare personas like objects or config profiles
- 🤝 Role-aware (senior, junior, peer) AI behavior expectations
- 🧪 Markdown + JSON hybrid format for maximum portability
- 🛠️ CLI tooling (planned) for persona injection and manipulation

---

## 📂 Repo Structure

```
/docs             → Human-readable guide to personas and design philosophy
/personas         → JSON + Markdown persona configurations
/tools (planned)  → CLI for managing, cloning, and injecting personas
```

---

## 📘 Included Personas

- `mvp`
- `functional_correctness`
- `production_robustness`
- `experimental`
- `fun_coding`
- `interview_preparation`

Each persona defines expected AI behavior across:
- Praise frequency
- Feedback tone
- Reasoning visibility
- Testability/security awareness
- Dialogue and learning balance

---

## 💡 Why This Exists

Prompt engineering is powerful — but often ad-hoc and inconsistent. This project formalizes AI tuning so that:
- Your tools align with your project values
- Pair programming with AI feels thoughtful, not chaotic
- You can grow your thinking by reflecting on how tools should behave

---

## 📦 Getting Started

1. Browse `/personas` or `/docs` to pick a persona.
2. Copy the persona markdown into your Copilot Chat session or ChatGPT system prompt.
3. Adjust as needed for your project.
4. (Optional) Contribute your own personas or behavioral extensions!

---

## 🧠 Inspired By

- `.eslintrc` and `.editorconfig`
- Thoughtful prompt engineering
- Design systems for developer experience

