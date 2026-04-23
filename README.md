---
title: RAG PDF Chatbot
emoji: 📄
colorFrom: purple
colorTo: blue
sdk: streamlit
sdk_version: 1.35.0
app_file: app.py
pinned: false
---

# PDF Q&A Chatbot (RAG-based)

Upload any PDF and ask questions about it.
Powered by LangChain, FAISS, HuggingFace embeddings
and Groq LLaMA 3.3 70B.

## Tech stack
- LangChain — RAG pipeline
- FAISS — vector similarity search
- HuggingFace sentence-transformers — free embeddings
- Groq LLaMA 3.3 70B — free LLM (fast)
- Streamlit — web interface

## How to run locally
pip install -r requirements.txt
streamlit run app.py

## Live demo
[View on Hugging Face Spaces](https://vishnuvardhanreddy12-rag-pdf-chatbot.hf.space)