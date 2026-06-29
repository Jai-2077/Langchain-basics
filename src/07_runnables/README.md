# Runnables — LangChain's Core Interface

# 🏃 Runnables — LangChain's Core Interface

## What is a Runnable?
Every component in LangChain implements the **Runnable** interface.

This means every component has the SAME methods:
- `.invoke(input)` — single call
- `.stream(input)` — streaming
- `.batch(inputs)` — parallel processing
- `.ainvoke(input)` — async invoke
- `.astream(input)` — async streaming
- `.abatch(inputs)` — async batching

## Why This Matters
Since EVERYTHING is a Runnable, you can:
- Swap components freely: `llm_a | par

## Files
- `notebook.ipynb` — Main notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice
- `quiz.md` — Self-assessment
