# Retrievers — Fetching Relevant Documents

# 🔍 Retrievers

## What is a Retriever?
A **Retriever** is an abstraction over vector stores (and other sources) that fetches relevant documents.

```python
retriever.invoke("my question") → List[Document]
```

## Why Retrievers?
Vector stores have many search methods. Retrievers:
- Provide a **uniform interface** (always returns `List[Document]`)
- Can use **multiple strategies** (not just vector similarity)
- Integrate directly with LCEL chains
- Work with ANY document source, not just vector 

## Files
- `notebook.ipynb` — Main notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice
- `quiz.md` — Self-assessment
