# Conversational RAG with PDF Uploads & Chat History

This project implements a **Conversational Retrieval-Augmented Generation (RAG)** system where users can:

- Upload PDFs 📄  
- Chat over the PDF content 💬  
- Maintain multi-turn conversation context using chat history 🧠  
- Use **Groq LLMs (Gemma 2)** for fast & efficient responses ⚡  
- Use Hugging Face Embeddings (`all-MiniLM-L6-v2`) for semantic search 🔎

---

## 🚀 Features

- ✅ Multiple PDF uploads
- ✅ Document chunking & embedding via `HuggingFaceEmbeddings`
- ✅ Vector storage using ChromaDB
- ✅ Contextual question reformulation using LangChain's `create_history_aware_retriever()`
- ✅ Stateless / Stateful multi-turn conversations
- ✅ Powered by **Groq Gemma2-9b-It** model
- ✅ Built using **Streamlit** UI

---

## 🔧 Setup Instructions

### 1️⃣ Install Requirements


pip install -r requirements.txt

### 2️⃣ Get Groq API Key
Sign up or log in to Groq:
👉 https://console.groq.com/

Go to:
👉 https://console.groq.com/keys

Click "Create API Key" and copy your key.
### 🛠Tech Stack
Python 3.10

Streamlit

LangChain

Chroma

Hugging Face Embeddings

Groq LLM (Gemma2-9b-It)

PyPDFLoader

sentence-transformers

dotenv
