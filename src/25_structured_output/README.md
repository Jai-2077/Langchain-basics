# Structured Output — Getting Reliable JSON from LLMs

# 📊 Structured Output

## The Problem
LLMs return text. Applications need structured data.

## Solutions (in order of reliability)
1. **with_structured_output()** — uses tool calling, most reliable
2. **PydanticOutputParser** — uses format instructions, less reliable
3. **JsonOutputParser** — basic JSON parsing
4. **Manual parsing** — fragile, not recommended

## when to Use
- Extracting structured data from text
- Form filling
- Classification
- Entity extraction


## Files
- `notebook.ipynb` — Main notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice
- `quiz.md` — Self-assessment
