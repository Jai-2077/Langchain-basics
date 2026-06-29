# 🔗 LangChain & LangGraph Master Course

**The most comprehensive, opinionated LangChain + LangGraph learning resource.**


[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![LangChain](https://img.shields.io/badge/LangChain-Latest-1C3C3C?style=for-the-badge)](https://www.langchain.com/)
[![LangGraph](https://img.shields.io/badge/LangGraph-Latest-4CAF50?style=for-the-badge)](https://www.langchain.com/langgraph)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![OpenAI](https://img.shields.io/badge/OpenAI-API-412991?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com/)

---

## What You'll Learn

| Phase | Topics |
|-------|--------|
| **Foundation** | Python refresh, LLM fundamentals, LangChain basics |
| **Core LangChain** | Messages, prompts, LCEL, runnables, parsers |
| **Data & RAG** | Loaders, splitters, embeddings, vector stores, retrievers, RAG |
| **Intelligence** | Memory, tools, agents, SQL agents |
| **Production** | Streaming, LangSmith, testing, deployment, async |
| **LangGraph** | State, nodes, edges, checkpoints, memory, human-in-the-loop |
| **Advanced Patterns** | Multi-agent, supervisor, reflection, planner-executor |
| **Capstone** | Full production applications |

---

## 🗂️ Repository Structure

```
langchain-mastercourse/
├── README.md
├── requirements.txt
├── .env.example
└── src/
    ├── 01_python_refresh/        ← Start here
    ├── 02_llm_fundamentals/
    ├── 03_langchain_basics/
    ...
    └── 45_capstone_projects/     ← End here
```

Each module contains:
- `notebook.ipynb` — Main learning notebook
- `notes.md` — Study notes
- `cheatsheet.md` — Quick reference
- `exercises.md` — Practice problems
- `quiz.md` — Self-assessment

---

## Quick Start

```bash
# 1. Clone / download this repo
git clone https://github.com/Jai-2077/Langchain-basics.git


# 2. Create virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Set up API keys
cp .env.example .env
# Edit .env and add your OPENAI_API_KEY

# 5. Start with module 01
cd src/01_python_refresh
jupyter notebook notebook.ipynb
```

---

## Modules

### Foundations (Modules 01–08)
- Python patterns used in LangChain
- How LLMs work
- Messages, prompts, LCEL chains
- Output parsers

### Data & RAG (Modules 09–14)
- Document loaders
- Text splitting strategies
- Embeddings and vector stores
- Building RAG pipelines

### Intelligence (Modules 15–25)
- Memory and chat history
- Tools and tool calling
- Agents
- Structured output

### LangGraph (Modules 31–43)
- Graph fundamentals
- State management
- Multi-agent systems
- Production patterns

### Production (Modules 26–30, 44–45)
- Async, testing, deployment
- Guardrails, monitoring
- Capstone projects

---

Every concept is explained with:
1. **WHAT** it is (plain English first)
2. **WHY** it exists (motivation)
3. **WHAT problem** it solves
4. **HOW** it works internally
5. **Input/Output** contracts
6. **Common mistakes**
7. **Interview questions**
8. **Production usage**

---

## Prerequisites

- Python basics (variables, functions, loops, classes)
- Basic command line usage

---

## Key Dependencies

| Package | Purpose |
|---------|---------|
| `langchain` | Core framework |
| `langchain-openai` | OpenAI integration |
| `langgraph` | Stateful agent workflows |
| `langchain-community` | Community integrations |
| `faiss-cpu` | Local vector store |
| `langsmith` | Observability |

---

## Contributing

Found an error? Have a better explanation?
Open an issue or PR.


