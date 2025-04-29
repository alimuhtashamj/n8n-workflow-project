# 🤖 n8n Workflow: AI Agent with Tools, Memory, and Vector Store

This repository contains a generalized **n8n workflow** designed to build a smart, context-aware chatbot system using large language models (LLMs), memory, vector search, and optional tools like Wikipedia and a calculator.

---

## 📌 Overview

**Workflow Type**: AI Agent with Retrieval-Augmented Generation (RAG)  
**Purpose**: Responds to user messages by retrieving contextually relevant information from a vector store and generating responses using LLMs.  
**Trigger**: When a chat message is received.

---

## 🔧 Features

- 🧠 **Memory-Aware Agent**: Maintains chat history with a window buffer or similar memory store
- 🧾 **RAG Pipeline**: Integrates a vector store (e.g., Pinecone, Weaviate, FAISS) for semantic search
- 💬 **LLM-Backed Generation**: Uses LLMs (e.g., OpenAI GPT, Google Gemini) to generate accurate, grounded answers
- 🛠️ **Tool-Enhanced Reasoning**: Optional tools like Wikipedia and Calculator for extended capabilities
- 🧱 **Embeddings Model Integration**: Transforms input text into embeddings (e.g., with Cohere, OpenAI, Hugging Face)
