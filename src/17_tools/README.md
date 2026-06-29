# Tools — Giving LLMs Superpowers

# 🛠️ Tools

## What are Tools?
**Tools** are Python functions that an LLM can **decide to call**.

LLMs know about the world up to their training cutoff.
Tools let LLMs:
- Search the internet
- Run Python code
- Query databases
- Call APIs
- Read/write files

## Mental Model: Human with Assistants
An executive (LLM) has assistants (tools):
- "Search the web for this" → WebSearch tool
- "Calculate this formula" → Calculator tool
- "Send this email" → Email tool

The executive DECIDES which assist

## Files
- `notebook.ipynb` — Main notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice
- `quiz.md` — Self-assessment
