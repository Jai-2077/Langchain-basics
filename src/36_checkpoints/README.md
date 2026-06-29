# Checkpoints — Saving and Resuming State

# 💾 Checkpoints

## What are Checkpoints?
Checkpoints **save graph state** at each step.

This enables:
- **Resume** interrupted workflows
- **Time travel** — go back to any previous state
- **Human-in-the-loop** — pause and wait for human input
- **Debugging** — inspect state at any step

## Checkpoint Backends
| Backend | Storage | Use Case |
|---------|---------|---------|
| MemorySaver | RAM | Development |
| SqliteSaver | SQLite file | Small production |
| PostgresSaver | PostgreSQL | Large

## Files
- `notebook.ipynb` — Main notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice
- `quiz.md` — Self-assessment
