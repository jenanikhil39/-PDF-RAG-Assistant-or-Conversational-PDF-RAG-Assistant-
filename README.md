# 📚 Interactive PDF RAG Assistant
An open-weight Retrieval-Augmented Generation (RAG) assistant built with LangChain, ChromaDB/FAISS, Hugging Face embeddings, and Groq (Qwen/LLaMA) to chat with PDF documents using page-level citations.


An interactive document question-answering tool built with **LangChain**, **FAISS / ChromaDB**, and **Gradio**. This project enables users to upload PDF documents, automatically index semantic chunks into vector embeddings, and query them using state-of-the-art LLMs with verifiable page citations.

---

## ⚡ Features

- **Document Ingestion**: Flexible parsing of complex PDF structures using `PyPDFLoader` and `Unstructured`.
- **Semantic Chunking**: Context-aware splitting with `RecursiveCharacterTextSplitter`.
- **Vector Search**: Dense retrieval backed by `FAISS` and `ChromaDB` embeddings.
- **Multi-Model Support**: Supports Groq-hosted open weights (e.g., Qwen/LLaMA) and OpenAI models.
- **Interactive UI**: Clean two-panel layout built with Gradio for drag-and-drop ingestion and chat.

---

## 🛠️ Tech Stack

- **Framework**: LangChain
- **Vector Store**: FAISS, ChromaDB
- **Models**: Groq ChatGroq (`qwen/qwen3.8-27b`), OpenAI (`gpt-4o-mini`)
- **Embeddings**: HuggingFace (`sentence-transformers`), OpenAI (`text-embedding-3-small`)
- **UI**: Gradio

---

## 🚀 Getting Started

