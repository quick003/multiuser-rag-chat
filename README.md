# 🤖 RAGBot Session – Multi-user Document Q&A Chatbot with Ollama

**RAGBot Session** is a lightweight, session-isolated RAG (Retrieval-Augmented Generation) chatbot that lets **each user upload their own documents** and interact with a private, context-aware AI assistant — all powered locally with [Ollama](https://ollama.com/).

---

### 🚀 Features

- 📁 Per-user document upload and isolated knowledgebase
- 🤖 Chat interface powered by local LLM (e.g., Mistral) via Ollama
- 📄 Supports multiple formats: PDF, DOCX, TXT, CSV, and Markdown
- 💬 Gradio web UI with real-time updates and session memory
- 🔐 Safe prompt: model answers only from document context
- 🧠 Embedding model: `nomic-embed-text` via Ollama

---

### 📓 Run It Instantly on Colab

Try it in your browser (GPU recommended):  
👉 [Open in Colab](https://colab.research.google.com/drive/1GwU-U46PQs0raLykUhWgkVUffY4VJaOl?usp=sharing)

---

### 📂 Supported File Types

| Type | Extension |
|------|-----------|
| PDF  | `.pdf`    |
| Word | `.docx`   |
| Text | `.txt`    |
| CSV  | `.csv`    |
| Markdown | `.md` |

---

### 🛠 Tech Stack

- **LLM backend**: [Ollama](https://ollama.com/)
- **Embeddings**: `nomic-embed-text`
- **Vector DB**: Chroma
- **Framework**: LangChain
- **UI**: Gradio
- **Runtime**: Google Colab / Local

---

### 💡 Use Cases

- Product document chatbot per user
- Multi-user document Q&A systems
- Custom knowledge assistants for teams
- Private, offline RAG-powered helpdesk

---

### 📌 How It Works

1. Each user uploads their documents (multi-format)
2. App indexes documents and creates an isolated vector DB
3. Questions are answered strictly from the relevant content
4. No cross-user data mixing — each session is sandboxed

---

### 📄 License

MIT — Free to use, modify, and distribute.

---

### 🙋‍♂️ Author

Built with ![AI](https://img.shields.io/badge/-AI%20Power-6f42c1?style=flat&logo=openai&logoColor=white) by [ritik-dev](https://github.com/ritik-dev)
