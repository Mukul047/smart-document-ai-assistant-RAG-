# Smart Document AI Assistant (RAG Based) 🤖📄

## 🚀 Overview

Smart Document AI Assistant is a powerful AI chatbot that allows users to interact with their documents using **Retrieval-Augmented Generation (RAG)**.

It processes documents, converts them into embeddings, and retrieves the most relevant context to generate accurate and meaningful answers using a local Large Language Model.

---

## ✨ Features

* 📄 Chat with PDF and text documents
* 🧠 Context-aware AI responses
* ⚡ Fast retrieval using FAISS vector database
* 🔒 Runs locally using Ollama (no API required)
* 💬 Interactive UI with Streamlit
* 📡 Streaming responses for better experience

---

## 🧠 Tech Stack

* Python
* LangChain
* FAISS (Vector Database)
* Streamlit
* Ollama (Mistral LLM)

---

## ⚙️ How It Works

1. 📥 Load and preprocess document (PDF)
2. ✂️ Split content into smaller chunks
3. 🔢 Convert text into vector embeddings
4. 🗄️ Store embeddings in FAISS database
5. 🔍 Retrieve relevant chunks for query
6. 🤖 Generate answer using LLM

---

## 📂 Project Structure

```bash
.
├── app.py              # Streamlit UI
├── pipeline.py         # RAG pipeline logic
├── retriever.py        # Context retrieval
├── generator.py        # Response generation
├── chunks/             # Processed text chunks
├── vectordb/           # FAISS vector database
├── data/               # Input documents
├── requirements.txt
└── README.md
```

---

## ▶️ Getting Started

### 1. Install dependencies

```bash
pip install -r requirements.txt
```

### 2. Run the application

```bash
streamlit run app.py
```

---

## 📌 Example Queries

* "Summarize the document"
* "What are the key points?"
* "Explain the policies mentioned"
* "Give a quick overview"

---

## 🎯 Use Cases

* Personal document assistant
* Knowledge base chatbot
* AI-powered document search
* Study and research assistant

---

## 🔧 Requirements

* Python 3.8+
* Ollama installed

To install model:

```bash
ollama pull mistral:7b-instruct
```

---

## 📝 Note

This project uses a **local LLM via Ollama**, ensuring privacy and eliminating dependency on paid APIs.

---

## 🔮 Future Improvements

* Multi-document support
* Web deployment (cloud hosting)
* Voice-enabled interaction
* UI enhancements

---

## ⭐ Acknowledgement

Inspired by modern RAG-based AI systems and real-world AI assistants.

---

