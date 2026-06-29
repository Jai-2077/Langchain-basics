# Testing LangChain Applications — Cheat Sheet

## Quick Reference
| Component | Import | Usage |
|-----------|--------|-------|
| ChatOpenAI | `from langchain_openai import ChatOpenAI` | `llm = ChatOpenAI(model='gpt-4o-mini')` |
| PromptTemplate | `from langchain_core.prompts import ChatPromptTemplate` | `ChatPromptTemplate.from_template(...)` |
| StrOutputParser | `from langchain_core.output_parsers import StrOutputParser` | `parser = StrOutputParser()` |

## Common Patterns
```python
# Basic chain
chain = prompt | llm | parser
result = chain.invoke({'input': 'value'})

# Streaming
for chunk in chain.stream({'input': 'value'}):
    print(chunk, end='')

# Async
result = await chain.ainvoke({'input': 'value'})
```

## Gotchas
- Always load .env before imports
- Messages are not strings — use .content
- Nodes return PARTIAL state, not full state
