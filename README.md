# Agentic AI

A hands-on journey through building modern LLM applications, autonomous agents, and production AI systems.

---

## Topics

1. **LangChain**
2. **LangGraph**
3. **RAG**
4. **Vectorless RAG**
5. **Deep Agents**
6. **Guardrails**
7. **LLM Evaluation**
8. **LLM Gateways**

---

## 🛠️ Getting Started

### 1. Environment Setup

Using [`uv`](https://docs.astral.sh/uv/) (recommended):
```bash
# Install dependencies and sync virtual environment
uv sync
```

Or using standard `pip`:
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

### 2. Configure API Keys

Create a `.env` file in the root directory:
```bash
cp .env.example .env
```

Add your API credentials:
```env
OPENAI_API_KEY="your-key-here"
GROQ_API_KEY="your-key-here"
GOOGLE_API_KEY="your-key-here"
```

### 3. Running Notebooks

Open the notebooks inside the [`langchain/`](langchain/) directory and select your `.venv` kernel to run the cells.

---
