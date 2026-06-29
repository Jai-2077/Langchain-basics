# Memory — Giving LLMs a Past

# 🧠 Memory in LangChain

## The Problem: LLMs Are Stateless
Each LLM call is **independent**. The LLM has no memory of previous messages.

```
Call 1: "My name is Alice"  → "Hello Alice!"
Call 2: "What's my name?"   → "I don't know your name."  ← !!
```

## The Solution: Memory
We **manually** manage conversation history and inject it into every prompt.

## Memory Types
| Type | What It Stores | Use Case |
|------|---------------|---------|
| ConversationBufferMemory | Full history | Short conve

## Files
- `notebook.ipynb` — Main notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice
- `quiz.md` — Self-assessment
