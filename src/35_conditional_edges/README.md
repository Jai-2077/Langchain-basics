# Conditional Edges — Dynamic Routing

# 🔀 Conditional Edges

## What are Conditional Edges?
Conditional edges route the graph to different nodes based on **state**.

```
if state has tool_calls → go to tools node
else → go to END
```

This enables:
- Agent loops (keep reasoning until done)
- Error recovery (retry on failure)
- Multi-step workflows (branch based on results)


## Files
- `notebook.ipynb` — Main notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice
- `quiz.md` — Self-assessment
