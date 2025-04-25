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
````
### 2. Create and activate a virtual environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
````

### 3. Install the dependencies

```bash
pip install -r requirements.txt
````

### 4. Set your Google API key
Create a .env file in the root directory and add:

```bash
GOOGLE_API_KEY=your_google_api_key_here
````
### 5. Run the app
```bash
streamlit run app.py
````
---

## ☁️ Deployment on Hugging Face Spaces
* Push your repo to a Hugging Face Space (select SDK: Streamlit).

* In your Space settings, go to "Secrets" and add:
```makefile
Name: GOOGLE_API_KEY
Value: your_google_api_key_here
````
* Hugging Face automatically injects this as an environment variable.
---

## 📂 Project Structure
```bash
chat-with-pdf-gemini/
│
├── app.py                  # Main Streamlit app
├── requirements.txt        # All dependencies
├── .env                    # Your local API key (not committed)
└── README.md               # This file
````
---

## ⚠️ Notes
* This app creates a local FAISS index (faiss_index/) — it will regenerate each time new PDFs are uploaded.

* Your API key should have access to Gemini Pro (models/gemini-pro).

---

## 💬 Contact

Feel free to reach out to me through any of the following platforms:

- LinkedIn: [https://www.linkedin.com/in/ahmed-amer](https://www.linkedin.com/in/ahmed-amer-03b390244/)
- Gmail: [ahmed.mohammad.amer@gmail.com](mailto:ahmed.mohammad.amer@gmail.com)
---

## ⭐️ Give it a Star!

If you find this project useful, consider giving it a ⭐ on GitHub!

---
