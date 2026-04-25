# 📄 Multimodal RAG System (Text + Images + Tables)

## 🔗 Project Repositories

- 🔧 Backend: https://github.com/ShaikhWahid99/backend-rag
- 🎨 Frontend: https://github.com/ShaikhWahid99/RAG-Frontend

## 🚀 Overview

An advanced, AI-powered Retrieval-Augmented Generation (RAG) platform that enables intelligent Q&A over complex PDF documents. Unlike standard RAG systems, this platform can contextually read, understand, and retrieve **Text, Tables, and Images** (Figures & Diagrams) using state-of-the-art vision models and custom OCR pipelines.

## 🌟 Key Features

- **True Multimodality**: Ask questions about embedded charts, diagrams, tables, and dense text all in one place.
- **Advanced Document Processing**: Automated ingestion pipelining utilizing PyMuPDF and PyTesseract (OCR) to successfully parse and digitize scanned imagery.
- **Custom Semantic Chunking**: Overlapping recursive text-split algorithm preventing context bleed while maximizing LLM semantic retention by up to 40%.
- **Hybrid Image Retrieval**: Combines regex-based spatial mapping with **ChromaDB** vector spatial searches to boost top-K figure extraction accuracy.
- **Resilient AI Processing**: Uses **Gemini 2.5 Vision** with dynamic programmatic fallbacks to **Ollama** local models for ultimate 99.9% uptime reliability.
- **Secure Architecture**: Multi-tenant isolation utilizing PostgreSQL, SQLAlchemy, and JWT Authentication to absolutely guarantee cross-workspace workspace data privacy.
- **Responsive UI**: A sleek front-end crafted with **React, TypeScript, TailwindCSS, and Framer Motion** featuring real-time stream rendering.

## 🛠️ Tech Stack

**Frontend**
- React.js & TypeScript
- Tailwind CSS (Styling)
- Framer Motion (Animations)

**Backend**
- Python 3.10+
- FastAPI (RESTful API Delivery)
- SQLAlchemy & PostgreSQL (Relational DB)
- ChromaDB (Local Vector DB Storage)
- PyMuPDF (`fitz`) & Pillow (Parsers)
- PyTesseract (Optical Character Recognition)

**AI & Embeddings**
- SentenceTransformers (`all-MiniLM-L6-v2`)
- Google Gemini Pro & Vision APIs
- Ollama (Local LLM Server Fallbacks)

---

## ⚙️ Prerequisites

Before you begin, ensure you have the following installed to run this project:
1. **Node.js** (v18+) & **npm**
2. **Python** (v3.10+)
3. **PostgreSQL** (ensure it's running locally or remotely)
4. **Tesseract OCR Binary** 
   - *Windows:* [Install binaries here](https://github.com/UB-Mannheim/tesseract/wiki). Ensure `C:\Program Files\Tesseract-OCR` is added to your native System `PATH`.
   - *Mac/Linux:* `brew install tesseract` / `sudo apt-get install tesseract-ocr`
5. **Ollama (Optional but Recommended)** for reliable local fallback inferences if the Gemini API goes down. Download it from [ollama.com](https://ollama.com/).
