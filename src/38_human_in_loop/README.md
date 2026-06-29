# Human-in-the-Loop — Pausing for Human Input

# 👤 Human-in-the-Loop

## What is Human-in-the-Loop?
Pause the graph execution and **wait for human input** before continuing.

## Use Cases
- Approve before executing dangerous actions
- Request clarification when LLM is uncertain
- Review generated code before running
- Manual data entry at specific points

## Implementation: interrupt_before
```python
app = graph.compile(
    checkpointer=checkpointer,
    interrupt_before=['dangerous_tool']  # pause before this node
)
```


## Files
- `notebook.ipynb` — Main notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice
- `quiz.md` — Self-assessment
