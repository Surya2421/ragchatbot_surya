# 🤖 RAG Chatbot — Retrieval-Augmented Generation with LangChain & Google Gemini

A RAG (Retrieval-Augmented Generation) chatbot built from scratch using **LangChain**, **Google Gemini API**, and **Vector Search** — running entirely in Google Colab.

Ask any question about your documents and get accurate, grounded answers — no hallucination! ✅

---

## 🚀 Demo

> **Query:** `what does Codex do?`
>
> **Answer:** Codex is an autonomous agent for coding. Specifically:
> - It runs autonomously for hours or days to reach a defined outcome and success criteria, especially in its "Goal Mode."
> - It can take live app windows and screenshots directly into its threads to get richer visual context.
> - It can run from a locked Mac, controlled remotely from a phone with the screen off, allowing for long agentic sessions.

---

## 🧠 How It Works

```
Your Document
     │
     ▼
  Chunking & Embedding
     │
     ▼
  Vector Index (Semantic Search)
     │
     ▼
  Retrieve Relevant Chunks
     │
     ▼
  Google Gemini LLM
     │
     ▼
  Accurate Answer ✅
```

Standard LLMs hallucinate because they're limited to their training data. RAG fixes this by combining **vector-based document retrieval** with **LLM-powered generation** — giving answers grounded in YOUR data.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| 🐍 Python | Core language |
| 🦜 LangChain | RAG pipeline (`RetrievalQA`) |
| 🤖 Google Gemini API | LLM backbone |
| 📦 Vector Index | Semantic document retrieval |
| ☁️ Google Colab | Development environment |

---

## 📂 Project Structure

```
Surya's RAG.ipynb        ← Main Colab notebook
README.md                ← You are here
```

---

## ⚡ Quick Start

### 1. Open in Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1HBt3k0elr8UIeqTFi6uNoQXKkcCE1v4S?usp=sharing)

### 2. Set up Google Gemini API Key

Get your free API key from [Google AI Studio](https://aistudio.google.com/app/apikey) and add it when prompted.

### 3. Install Dependencies

```python
pip install langchain langchain-google-genai google-generativeai faiss-cpu
```

### 4. Run All Cells

Upload your document → Run all cells → Start asking questions!

---

## 💡 Features

- ✅ Upload any document (PDF, TXT, etc.)
- ✅ Ask questions in plain English
- ✅ Accurate answers pulled directly from your data
- ✅ Powered by Google Gemini + LangChain RetrievalQA
- ✅ Zero hallucination — answers grounded in source documents
- ✅ Completely free to run on Google Colab

---

## 📸 Screenshot

![RAG Chatbot Demo](screenshot.png)

---

## 🙋‍♂️ Author

**Surya** — building AI projects one notebook at a time 🚀

- 🔗 [LinkedIn](https://www.linkedin.com/in/)
- ⭐ Star this repo if you found it helpful!

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
