# 📄💬 AskYourDocs

**AskYourDocs** is a private, open-source GenAI assistant that lets you securely chat with your internal documents (PDFs, DOCX) using powerful language models. Designed with enterprise use in mind, the app can be deployed easily via HuggingFace Spaces with minimal setup and zero vendor lock-in.

---

## 🚀 Features

- ✅ Upload and chat with your **PDF** or **Word (DOCX)** documents
- 🔍 Uses **RAG (Retrieval-Augmented Generation)** to give accurate, document-grounded answers
- 🧠 Powered by **HuggingFace-hosted models** or **local language models**
- 💻 Built with **Streamlit** for a clean, responsive UI
- 🐳 Easily **containerized with Docker** for scalable deployment
- 🔐 Keeps everything open-source and avoids dependency on proprietary infrastructure

---

## 📊 Use Cases

- Internal knowledge base access (HR, Legal, IT)
- Enterprise document Q&A system
- Personal document assistant (resumes, research papers, contracts)

---

## 🏗️ Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python
- **LLM**: HuggingFace Transformers (or Ollama for local models)
- **Vector Store**: ChromaDB or Qdrant
- **Deployment**: HuggingFace Spaces + Docker (optional)
- **Document Parsing**: PyMuPDF, pdfplumber, python-docx

---

## 🧰 Local Development Setup

1. **Clone the repo**
   ```bash
   git clone https://github.com/your-username/AskYourDocs.git
   cd AskYourDocs
