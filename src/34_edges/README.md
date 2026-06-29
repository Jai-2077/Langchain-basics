# LangGraph Edges — Connecting Nodes

# ➡️ LangGraph Edges

## What are Edges?
Edges define the **flow** between nodes.

## Edge Types
| Type | Description | When to Use |
|------|-------------|-------------|
| Normal edge | Always goes A → B | Sequential steps |
| Conditional edge | Routes based on state | Branching logic |
| Entry point | Sets starting node | Required in every graph |

## Edge Routing
```python
graph.add_edge('A', 'B')           # Always: A → B
graph.add_conditional_edges('A',   # Conditional: A → ? 
    routing_f

## Files
- `notebook.ipynb` — Main notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice
- `quiz.md` — Self-assessment
