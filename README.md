# 📊 Commercial Law Semantic Search

A Retrieval-Augmented Generation (RAG) based system for semantic search over Saudi commercial law documents.

This project enables users to query legal texts in Arabic and retrieve the most relevant sections using modern NLP techniques such as embeddings and vector search.

---

## 🚀 Overview

Legal documents are often long and difficult to navigate. This project aims to simplify access to commercial law by allowing users to ask natural language questions and receive relevant answers from the official text.

The system is designed to:
- Improve legal information accessibility
- Enable semantic understanding of queries (not just keyword matching)
- Support Arabic language processing

---

## 🧠 How It Works

1. **Data Source**
   - Saudi Commercial Register Law (Arabic & English)

2. **Text Processing**
   - The document is split into smaller chunks for better retrieval

3. **Embeddings**
   - Each chunk is converted into vector representations using Sentence Transformers

4. **Indexing**
   - FAISS is used to store and search embeddings efficiently

5. **Search**
   - User queries are converted into embeddings and matched with the most relevant text chunks

---

## ⚙️ Tech Stack

- Python
- Sentence Transformers
- FAISS (Facebook AI Similarity Search)
- Google Colab
- Arabic NLP

---

## 🔍 Example Queries

- What are the penalties for violations?
- When is a commercial registration suspended?
- Is the trader responsible for incorrect data?

---

## 📌 Features

- Semantic search (not keyword-based only)
- Supports Arabic legal text
- Fast retrieval using FAISS
- Clean and simple interface in Google Colab

---

## 🎯 Use Cases

- Legal research
- Students studying commercial law
- Quick access to regulations
- AI-powered legal assistants

---

## 🏁 Future Improvements

- Add answer generation (LLM integration)
- Build a web interface
- Support more legal documents
- Improve Arabic language understanding

---

## 📜 License

This project is for educational purposes.
