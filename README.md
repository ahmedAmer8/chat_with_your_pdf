# 🤖 Chat with Your PDF using Gemini

This is a Streamlit web app that allows you to **upload multiple PDF documents** and **ask questions about their content** using **Google Gemini Pro** (via the Generative AI API). It uses **LangChain** for building the conversational chain and **FAISS** to store and search through PDF text efficiently.

---

## 🚀 Demo

You can try it out live on **[Hugging Face Spaces](https://huggingface.co/spaces/Ahmed-Amer/Chat_with_your_PDFs)**  

---

## 🧠 Features

- 📄 Upload **one or more PDFs**
- 🧩 Automatically extract and chunk text
- 🔎 Build a searchable vector index using FAISS
- 💬 Ask natural language questions about the PDFs
- ⚡ Powered by **Google Gemini** for intelligent answers

---

## 🛠️ Tech Stack

- Python 🐍
- Streamlit 📊
- LangChain 🦜
- FAISS (vector store)
- Google Generative AI (Gemini Pro)
- PyPDF2 (PDF reading)


---

## 🧑‍💻 Local Setup

### 1. Clone the repository

```bash
git clone https://github.com/ahmedAmer8/chat-with-pdf-gemini.git
cd chat-with-pdf-gemini

---

### 2. Create and activate a virtual environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
