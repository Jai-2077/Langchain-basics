# Supervisor Pattern — Hierarchical Agent Control

# 👔 Supervisor Pattern

## What is the Supervisor Pattern?
A **supervisor** agent:
1. Receives the task
2. Decides which specialist to delegate to
3. Reviews results
4. Either delegates again or finishes

## Mental Model: Manager + Team
```
Manager (Supervisor)
├── Programmer (CodeAgent)
├── Researcher (SearchAgent)
└── Designer (UIAgent)
```

Manager understands the big picture.
Specialists are deep experts.


## Files
- `notebook.ipynb` — Main notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice
- `quiz.md` — Self-assessment
