# 🚀 Production RAG Kubernetes Assistant

A production-grade Retrieval-Augmented Generation (RAG) assistant for Kubernetes that helps developers and DevOps engineers troubleshoot clusters, answer operational questions, and retrieve contextual information using modern LLMs.

## ✨ Features

- 🤖 Multi-agent workflow powered by LangGraph
- 📚 Retrieval-Augmented Generation (RAG)
- 🔍 Semantic search with Qdrant
- 🧠 LLM integration via Portkey and Groq
- 🛡️ NeMo Guardrails for input/output safety
- 📄 Intelligent document ingestion and chunking
- ⚡ FastAPI backend
- 📊 Observability with Logfire and LangSmith
- 📈 RAGAS evaluation pipeline
- 🚀 Production-ready, scalable architecture

## 🛠️ Tech Stack

- LangGraph
- LangChain
- FastAPI
- Qdrant
- Groq
- Portkey
- Gemini Embeddings
- FlashRank
- NeMo Guardrails
- Logfire
- LangSmith
- Streamlit

## 📂 Project Structure

```
app/
├── agents/
├── gateway/
├── guardrails/
├── ingestion/
├── services/
└── main.py

ui/
evals/
docs/
DATA/
processed_data/
```

## 🚀 Getting Started

```bash
# Create virtual environment
python -m venv .venv

# Activate environment
.\.venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Start FastAPI
uvicorn app.main:app --reload

# Launch Streamlit
streamlit run ui/app.py
```

## 📌 Highlights

- Enterprise-grade RAG pipeline
- Multi-agent orchestration
- Context-aware retrieval
- Production observability
- Secure AI guardrails
- Scalable API architecture

---

**Built for intelligent Kubernetes troubleshooting and enterprise document intelligence.**
