# Async LangChain — Production Performance

# ⚡ Async LangChain

## Why Async?
Synchronous code: one request at a time.
Async code: thousands of requests concurrently.

For production AI apps, async is **essential**.

## LangChain Async API
Every Runnable has async versions:
- `.ainvoke()` → async invoke
- `.astream()` → async streaming
- `.abatch()` → async batch (most efficient)

## FastAPI + LangChain
The most common production pattern:
FastAPI (async web framework) + LangChain (async chains)


## Files
- `notebook.ipynb` — Main notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice
- `quiz.md` — Self-assessment
