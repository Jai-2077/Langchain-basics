# Output Parsers — Structuring LLM Responses

# 🔧 Output Parsers

## What is an Output Parser?
LLMs return text. You often need **structured data**.

Output parsers transform LLM text output into:
- Plain strings
- JSON/dicts
- Pydantic models
- Lists
- Booleans
- Enums

## Why Parsers?
Raw LLM output: `"The answer is 42, because the universe..."`
Your app needs: `{"answer": 42}`

Parsers bridge this gap.

## Parser Types
| Parser | Output | Use Case |
|--------|--------|----------|
| StrOutputParser | str | Simple text |
| JsonOutputParser

## Files
- `notebook.ipynb` — Main notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice
- `quiz.md` — Self-assessment
