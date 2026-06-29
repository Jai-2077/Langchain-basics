# Document Loaders — Ingesting Data into LangChain

# 📄 Document Loaders

## What are Document Loaders?
Document Loaders **read data** from various sources and convert it into LangChain `Document` objects.

## The Document Object
```python
Document(
    page_content="The actual text content...",
    metadata={"source": "file.pdf", "page": 1}
)
```

## Why Document Loaders?
Your AI app needs to process:
- PDFs, Word docs, PowerPoints
- Websites, Notion, Confluence
- CSV, JSON, Excel files
- GitHub repos, YouTube transcripts
- SQL databases

Each s

## Files
- `notebook.ipynb` — Main notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice
- `quiz.md` — Self-assessment
