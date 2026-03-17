# 📄 Multimodal RAG System (Text + Images + Tables)

## 🔗 Project Repositories

- 🔧 Backend: https://github.com/ShaikhWahid99/backend-rag
- 🎨 Frontend: https://github.com/ShaikhWahid99/RAG-Frontend

## 🚀 Overview

This project is a **Multimodal Retrieval-Augmented Generation (RAG) system** that enables users to query documents using natural language and retrieve answers from:

- 📄 **Text content**
- 🖼️ **Images / Figures**
- 📊 **Tables**

Unlike traditional RAG systems, this implementation supports **cross-modal retrieval**, allowing the system to understand and answer queries related to visual and structured data inside PDFs.

---

## 🎯 Key Features

### 🔍 Semantic Search using Embeddings
Converts document content into vector embeddings for efficient similarity search.

---

### 🧠 Multimodal Understanding

Handles multiple types of queries:

- **Text-based queries** → text retrieval  
- **Image-based queries** → vision model reasoning  
- **Table queries** → structured data interpretation  

---

### ⚡ Low-latency Retrieval with ChromaDB
Uses a vector database for fast and scalable similarity search.

---

### 🤖 LLM Integration (Gemini / GPT / Claude)
Generates context-aware answers strictly grounded in retrieved data.

---

### 📑 PDF Processing Pipeline

- Extracts text, images, and tables  
- Indexes them with metadata  
- Maps figures and tables for accurate retrieval  
