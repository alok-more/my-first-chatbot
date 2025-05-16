# 📚 Gemini PDF Chatbot using Streamlit

This project is a simple **PDF-based chatbot** built with **Streamlit** and **Google Gemini** API.  
It allows users to **upload a PDF**, **ask questions** about its content, and receive **intelligent answers** powered by **Gemini AI** and **FAISS vector search**.

---

## 🚀 Features

- Upload a **PDF document**
- Automatically **extract and split** PDF text into manageable chunks
- **Embed** text using **Google Generative AI Embeddings** (`embedding-001` model)
- Perform **semantic similarity search** using **FAISS**
- Ask **questions** and get **answers** from **Gemini 2.0 Flash** model
- Fast, lightweight, and easy to use with **Streamlit UI**

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit** – for web UI
- **Google Generative AI**  
  - `google-generativeai` – for API access  
  - `langchain-google-genai` – for LLM + Embedding integrations  
- **LangChain** – for chaining LLM tasks  
- **FAISS** – for vector database and similarity search  
- **PyPDF2** – for extracting PDF text  

---

## 📋 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/alok-more/my-first-chatbot.git
cd my-first-chatbot
pip install -r requirements.txt

```
### 2. Add Your Gemini API Key
```bash
GOOGLE_API_KEY = "YOUR GOOGLE GEMINI API KEY"
```

### 3. Run the app
```bash
streamlit run app.py
```