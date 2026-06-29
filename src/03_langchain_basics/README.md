# LangChain Basics — The Big Picture

# 🔗 LangChain Basics

## What is LangChain?
LangChain is a **framework** (collection of tools) that makes building LLM-powered applications easier.

## The Problem LangChain Solves
Without LangChain, building an AI app looks like this:
```
1. Manually format prompts as strings
2. Call OpenAI API directly
3. Parse the JSON response manually
4. No retry logic, no streaming, no memory
5. Repeat for every feature you need
```

With LangChain:
```
chain = prompt | llm | parser
result = chain.invoke({

## Files
- `notebook.ipynb` — Main notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice
- `quiz.md` — Self-assessment
