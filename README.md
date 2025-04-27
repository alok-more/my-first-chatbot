# 📚 Gemini PDF Chatbot using Streamlit

This project is a simple **PDF-based chatbot** built with **Streamlit** and **Google Gemini** API.  
It allows users to **upload a PDF**, **ask questions** about its content, and receive **intelligent answers** powered by **Gemini AI** and **FAISS vector search**.

---

## 🚀 Features
- Upload a **PDF document**.
- Automatically **extract and split** PDF text into manageable chunks.
- **Embed** text using **Google Generative AI Embeddings** (`embedding-001` model).
- Perform **semantic similarity search** using **FAISS**.
- Ask **questions** and get **answers** from **Gemini 2.0 Flash** model.
- Fast, lightweight, and easy to use with **Streamlit UI**.

---

## 🛠️ Tech Stack
- **Python**
- **Streamlit** – for web UI
- **Google Generative AI** (`google.generativeai`, `langchain_google_genai`) – for embeddings and chatbot responses
- **FAISS** – for vector storage and similarity search
- **PyPDF2** – for reading PDF content
- **LangChain** – for chaining LLM calls

---

## 📋 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/alok-more/my-first-chatbot.git
cd my-first-chatbot
