# Tool Calling — LLMs Executing Functions

# ⚙️ Tool Calling

## What is Tool Calling?
**Tool calling** = the process by which an LLM decides to call a tool, and we execute it.

## The Tool Calling Loop
```
User: "What is 25 * 4?"
   ↓
LLM: "I'll use the calculator tool"
   → tool_calls: [{name: "calculate", args: {"expression": "25 * 4"}}]
   ↓
We execute calculate("25 * 4") → "100"
   ↓
LLM: "The answer is 100"
```

## Key Insight
The LLM does NOT directly execute code.
The LLM **requests** a tool call.
**Our code** executes it and ret

## Files
- `notebook.ipynb` — Main notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice
- `quiz.md` — Self-assessment
