# 🤖 Intelligent RAG-Based Customer Support Assistant using LangGraph & HITL

<div align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge\&logo=python)
![LangChain](https://img.shields.io/badge/LangChain-RAG-green?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/LangGraph-Workflow-orange?style=for-the-badge)
![ChromaDB](https://img.shields.io/badge/ChromaDB-VectorDB-purple?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-Frontend-red?style=for-the-badge\&logo=streamlit)
![Groq](https://img.shields.io/badge/Groq-LLM-black?style=for-the-badge)

</div>

---

## 📌 Overview

An AI-powered Retrieval-Augmented Generation (RAG) customer support assistant built using LangChain, LangGraph, ChromaDB, Groq APIs, and Streamlit.

The system processes PDF knowledge bases, performs semantic retrieval using embeddings, generates contextual responses with LLMs, and supports Human-in-the-Loop (HITL) escalation for complex customer queries.

### 🚀 Features

* RAG Pipeline Design
* Semantic Search
* LangGraph Workflow Orchestration
* ChromaDB Vector Database
* Human-in-the-Loop (HITL)
* LLM Integration
* Streamlit Frontend
* AI Workflow Routing

---

## 🛠️ Tech Stack

| Technology            | Purpose                |
| --------------------- | ---------------------- |
| Python                | Core Programming       |
| LangChain             | RAG Pipeline           |
| LangGraph             | Workflow Orchestration |
| ChromaDB              | Vector Database        |
| Sentence Transformers | Embeddings             |
| Groq API              | LLM Inference          |
| Streamlit             | Frontend UI            |

---

## 🧠 System Architecture

```text
User Query
    ↓
Streamlit Frontend
    ↓
LangGraph Workflow
    ↓
Retriever
    ↓
ChromaDB
    ↓
Semantic Search
    ↓
Relevant Chunks
    ↓
Groq LLM
    ↓
Generated Response
    ↓
HITL Escalation (if needed)
```

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
├── README.md
└── .env
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/rag-customer-support.git

cd rag-customer-support
```

---

### Create Virtual Environment

```bash
python3 -m venv venv

source venv/bin/activate
```

---

### Install Requirements

```bash
pip install -r requirements.txt
```

---

### Add API Key

Create `.env` file:

```env
GROQ_API_KEY=your_api_key_here
```

---

### Run PDF Ingestion

```bash
python3 src/ingest.py
```

---

### Run Streamlit App

```bash
streamlit run streamlit_app.py
```

---

## 🔄 Workflow

1. Load PDF documents
2. Split into chunks
3. Generate embeddings
4. Store embeddings in ChromaDB
5. Retrieve relevant chunks
6. Generate contextual response using LLM
7. Route workflow using LangGraph
8. Trigger HITL escalation if needed

---

## 👨‍💻 Human-in-the-Loop (HITL)

Escalation is triggered when:

* Low confidence retrieval
* Missing context
* Sensitive customer issues
* Complex support requests

---

## 📈 Future Enhancements

* Multi-document support
* Conversational memory
* Docker deployment
* Authentication system
* Hybrid search
* Feedback learning loop

---

## 📄 Resume Project Description

Developed an AI-powered Retrieval-Augmented Generation (RAG) customer support assistant using LangChain, LangGraph, ChromaDB, and Groq APIs. Implemented semantic retrieval, vector search, workflow orchestration, conditional routing, and Human-in-the-Loop escalation for intelligent customer query handling.

---

## 🛠️ Skills Used

* Python
* LangChain
* LangGraph
* RAG
* ChromaDB
* Streamlit
* NLP
* LLMs
* Semantic Search
* Vector Databases
* Prompt Engineering
* Generative AI

---

## 👨‍💻 Author

### Sujay Kokkonda

🎓 B.Tech Student | AI/ML Enthusiast | Generative AI Developer

### 🌐 Connect With Me

* GitHub: [https://github.com/kokkondasujay](https://github.com/kokkondasujay)
* Hugging Face: [https://huggingface.co/sujay1234](https://huggingface.co/sujay1234)

---
