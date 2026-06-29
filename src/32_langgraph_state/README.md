# LangGraph State — Managing Shared Data

# 📦 LangGraph State

## What is State?
State is the **shared data structure** passed between all nodes in a LangGraph graph.

## State Design Principles
1. State should contain EVERYTHING nodes need
2. Use TypedDict for type safety
3. Use Annotated with operators for merge behavior
4. Keep state serializable (for checkpointing)

## Reducer Functions
When multiple nodes update the same field, you need a **reducer**:
```python
messages: Annotated[list, operator.add]  # appends lists
count: int  # 

## Files
- `notebook.ipynb` — Main notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice
- `quiz.md` — Self-assessment
