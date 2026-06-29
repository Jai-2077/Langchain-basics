# Vector Stores — Storing and Searching Embeddings

# 🗄️ Vector Stores

## What is a Vector Store?
A **vector store** (vector database) stores embeddings and lets you search them by semantic similarity.

Traditional DB: `WHERE name = 'Alice'` (exact match)
Vector DB: `WHERE embedding SIMILAR TO question_embedding` (semantic match)

## Popular Vector Stores
| Store | Type | Best For |
|-------|------|---------|
| FAISS | In-memory | Development, small datasets |
| Chroma | Local disk | Development, medium datasets |
| Pinecone | Cloud | Production

## Files
- `notebook.ipynb` — Main notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice
- `quiz.md` — Self-assessment
