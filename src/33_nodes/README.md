# LangGraph Nodes — Processing Units

# 🔵 LangGraph Nodes

## What is a Node?
A **node** is a Python function (or Runnable) that:
1. Takes the current state as input
2. Performs computation
3. Returns updated state (partial or full)

## Node Rules
- Input: current state (TypedDict)
- Output: dict with updated fields
- Must be deterministic (same input → same output) for reproducibility
- Can call LLMs, tools, APIs, or any Python code


## Files
- `notebook.ipynb` — Main notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice
- `quiz.md` — Self-assessment
