# LCEL — LangChain Expression Language

# ⛓️ LCEL — LangChain Expression Language

## What is LCEL?
LCEL is LangChain's **composition syntax** using the pipe `|` operator.

```python
chain = prompt | llm | parser
result = chain.invoke({"topic": "AI"})
```

## Mental Model: Linux Pipes
Linux: `cat file.txt | grep error | wc -l`
- `cat` outputs text
- `grep` filters it
- `wc` counts lines

LCEL: `prompt | llm | parser`
- `prompt` outputs Messages
- `llm` processes Messages → AIMessage
- `parser` extracts AIMessage → string

## Why LCEL 

## Files
- `notebook.ipynb` — Main notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice
- `quiz.md` — Self-assessment
