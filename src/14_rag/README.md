# RAG — Retrieval Augmented Generation

# 🎯 RAG — Retrieval Augmented Generation

## What is RAG?
**RAG** = give the LLM relevant documents before asking it questions.

Without RAG: LLM uses only its training data (may be outdated or incomplete).
With RAG: LLM uses training data + your specific documents.

## The RAG Pipeline
```
INDEXING (done once):
Documents → Split → Embed → Vector Store

RETRIEVAL (at query time):
Question → Embed → Similarity Search → Top K Docs

GENERATION:
[System Prompt + Retrieved Docs + Question] → LLM → An

## Files
- `notebook.ipynb` — Main notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice
- `quiz.md` — Self-assessment
