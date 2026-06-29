# Streaming — Real-Time LLM Responses

# ⚡ Streaming

## What is Streaming?
Instead of waiting for the full LLM response, **stream** tokens as they are generated.

Without streaming: User waits 5-10 seconds. Then sees full response.
With streaming: User sees text appearing word by word. Much better UX!

## Why Streaming Matters
- ChatGPT-like user experience
- Perceived latency is much lower
- Can cancel early if response is wrong

## LCEL + Streaming
All LCEL chains support streaming for free via `.stream()`.


## Files
- `notebook.ipynb` — Main notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice
- `quiz.md` — Self-assessment
