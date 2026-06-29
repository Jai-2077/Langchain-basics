# Text Splitters — Chunking Documents

# ✂️ Text Splitters

## Why Split Text?
LLMs have **context window limits** (e.g., 128K tokens).
A 500-page book exceeds any context window.
Solution: **chunk** the document into smaller pieces.

## The Goldilocks Problem
- Too large → exceeds context window, loses important info
- Too small → loses context, fragmented meaning
- Just right → preserves meaning, fits context window

## Chunking Strategy
```
Original Document (10,000 words)
        ↓
Text Splitter
        ↓
[Chunk 1 (200 words), Ch

## Files
- `notebook.ipynb` — Main notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice
- `quiz.md` — Self-assessment
