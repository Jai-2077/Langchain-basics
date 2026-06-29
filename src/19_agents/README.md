# Agents — LLMs That Think and Act

# 🤖 Agents

## What is an Agent?
An **agent** is an LLM that:
1. **Thinks** (decides what to do)
2. **Acts** (calls tools)
3. **Observes** (sees tool results)
4. **Repeats** until task complete

## ReAct Pattern (Reason + Act)
```
Thought: I need to find the weather in Paris
Action: get_weather(city="Paris")
Observation: Sunny, 22°C
Thought: I have the weather. I can answer now.
Final Answer: It's sunny and 22°C in Paris.
```

## Agent vs Chain
| Chain | Agent |
|-------|-------|
| Fixed steps |

## Files
- `notebook.ipynb` — Main notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice
- `quiz.md` — Self-assessment
