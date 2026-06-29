# Messages — The Language of LLMs

# 💬 Messages — The Language of LLMs

## What Are Messages?
Modern LLMs (GPT-4, Claude, Gemini) don't take a single string as input.
They take a **list of structured messages**, each with a role.

## Why Roles?
The LLM needs to know WHO said what:
- **System** → Instructions, persona, rules (from the developer)
- **Human** → User's input
- **AI** → Previous LLM responses (for multi-turn conversations)
- **Tool** → Results from tool/function calls

## Mental Model: Email Thread
```
SystemMessage  

## Files
- `notebook.ipynb` — Main notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice
- `quiz.md` — Self-assessment
