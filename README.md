# Intelligent RAG-Based Customer Support Assistant using LangGraph & HITL

## README.md

````markdown
# 🤖 Intelligent RAG-Based Customer Support Assistant using LangGraph & HITL

<div align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![LangChain](https://img.shields.io/badge/LangChain-RAG-green?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/LangGraph-Workflow-orange?style=for-the-badge)
![ChromaDB](https://img.shields.io/badge/ChromaDB-VectorDB-purple?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-Frontend-red?style=for-the-badge&logo=streamlit)
![Groq](https://img.shields.io/badge/Groq-LLM-black?style=for-the-badge)

</div>

---

## 📌 Overview
# Intelligent RAG-Based Customer Support Assistant using LangGraph & HITL

An AI-powered Retrieval-Augmented Generation (RAG) customer support assistant built using LangChain, LangGraph, ChromaDB, Groq APIs, and Streamlit.

The system processes PDF knowledge bases, performs semantic retrieval using embeddings, generates contextual responses with LLMs, and supports Human-in-the-Loop (HITL) escalation for complex customer queries.

This project demonstrates:
- RAG Pipeline Design
- Vector Databases
- Graph-Based AI Workflows
- Human-in-the-Loop Systems
- LLM Integration
- AI System Architecture
- Semantic Search
- Workflow Orchestration

The system processes PDF knowledge bases, retrieves relevant contextual information using semantic search, and generates intelligent responses using Large Language Models (LLMs). It also supports Human-in-the-Loop (HITL) escalation for complex or low-confidence queries.

---

---

## 🚀 Features

- PDF Knowledge Base Processing
- Semantic Search using Embeddings
- ChromaDB Vector Database
- LangGraph Workflow Orchestration
- Conditional Routing Logic
- Human-in-the-Loop Escalation
- Streamlit Web Interface
- Groq LLM Integration
- Retrieval-Augmented Generation (RAG)

---

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core Programming Language |
| LangChain | RAG Pipeline |
| LangGraph | Workflow Orchestration |
| ChromaDB | Vector Database |
| Sentence Transformers | Embedding Generation |
| Groq API | LLM Inference |
| Streamlit | Frontend UI |
| PyPDF | PDF Processing |

---

---

## 🧠 System Architecture

```text
User Query
    ↓
Streamlit Frontend
    ↓
LangGraph Workflow Engine
    ↓
Retriever
    ↓
ChromaDB Vector Store
    ↓
Semantic Search
    ↓
Relevant Chunks
    ↓
Groq LLM
    ↓
Answer Generation
    ↓
HITL Escalation (if required)
````

---

---

## 📂 Project Structure

```text
rag-customer-support/
│
├── src/
│   ├── __init__.py
│   ├── app.py
│   ├── config.py
│   ├── graph.py
│   ├── hitl.py
│   ├── ingest.py
│   ├── prompts.py
│   ├── retriever.py
│   ├── utils.py
│   └── data/
│       └── support.pdf
│
├── streamlit_app.py
├── requirements.txt
├── .gitignore
└── README.md
```

---

---

## ⚙️ Installation & Setup

## Clone Repository

```bash
git clone https://github.com/yourusername/rag-customer-support.git
cd rag-customer-support
```

---

# Create Virtual Environment

```bash
python3 -m venv venv
source venv/bin/activate
```

---

# Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Add Environment Variables

Create `.env` file:

```env
GROQ_API_KEY=your_api_key_here
```

---

# Run PDF Ingestion

```bash
python3 src/ingest.py
```

---

# Run Streamlit App

```bash
streamlit run streamlit_app.py
```

---

---

## 🔄 Workflow

1. PDF is loaded using PyPDFLoader.
2. Document is split into chunks.
3. Embeddings are generated using Sentence Transformers.
4. Embeddings are stored in ChromaDB.
5. User query is converted into embedding.
6. Semantic similarity search retrieves relevant chunks.
7. LangGraph routes workflow.
8. LLM generates contextual answer.
9. HITL escalation triggers for complex queries.

---

---

## 👨‍💻 Human-in-the-Loop (HITL)

The system escalates queries when:

* Low retrieval confidence
* Missing context
* Sensitive customer complaints
* Complex support requests

---

---

## 📈 Future Enhancements

* Multi-document support
* Conversational memory
* Feedback learning loop
* Docker deployment
* Authentication system
* Multi-user support
* Hybrid search

---

---

## 👨‍💻 Author

Sujay Kokkonda

```

---

# Resume Project Section

## Project Title

Intelligent RAG-Based Customer Support Assistant using LangGraph & HITL

---

## Resume Description (Short Version)

Developed an AI-powered Retrieval-Augmented Generation (RAG) customer support assistant using LangChain, LangGraph, ChromaDB, and Groq LLM APIs. Implemented semantic document retrieval, graph-based workflow orchestration, conditional routing, and Human-in-the-Loop escalation for intelligent customer query handling.

---

## Resume Description (ATS Friendly)

- Built a Retrieval-Augmented Generation (RAG) based AI customer support assistant using Python, LangChain, LangGraph, ChromaDB, and Streamlit.
- Implemented PDF ingestion pipeline, document chunking, semantic embeddings, vector similarity search, and contextual answer generation.
- Designed graph-based workflow orchestration with conditional routing and Human-in-the-Loop (HITL) escalation using LangGraph.
- Integrated Groq LLM APIs and Sentence Transformers for efficient low-latency AI response generation.
- Developed interactive Streamlit frontend and deployed scalable AI workflow architecture.

---

## Skills Used

- Python
- LangChain
- LangGraph
- RAG
- ChromaDB
- Vector Databases
- LLMs
- NLP
- Streamlit
- Prompt Engineering
- Semantic Search
- AI Workflows
- Generative AI

---

## LinkedIn Project Description

Built an Intelligent RAG-Based Customer Support Assistant using LangChain, LangGraph, ChromaDB, and Groq APIs. The system processes PDF knowledge bases, performs semantic retrieval using embeddings, generates contextual responses with LLMs, and supports Human-in-the-Loop escalation for complex customer queries. Implemented graph-based workflow orchestration, conditional routing, and interactive Streamlit deployment.

```
