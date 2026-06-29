# Callbacks — Observing LangChain Execution

# 📡 Callbacks

## What are Callbacks?
Callbacks let you **hook into** LangChain's execution to observe what's happening.

## Use Cases
- Logging (track every LLM call)
- Monitoring (latency, token usage)
- Streaming (send chunks to UI)
- Caching (save API costs)
- Debugging

## Callback Events
- `on_chain_start` / `on_chain_end`
- `on_llm_start` / `on_llm_end`
- `on_tool_start` / `on_tool_end`
- `on_chat_model_start`
- `on_llm_error` / `on_chain_error`


## Files
- `notebook.ipynb` — Main notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice
- `quiz.md` — Self-assessment
