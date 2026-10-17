# 🤖 Semantic Chatbot

## 💬 What is this?
A simple chatbot that replies based on **meaning**, not exact words.

---

## 🧠 Core Idea
Instead of keyword matching, this bot:
- Converts user input into embeddings  
- Compares it with known responses  
- Picks the closest match using **cosine similarity**  

---

## ⚙️ Engine
- SentenceTransformer (for text embeddings)  
- Cosine Similarity (for matching responses)  

---

## ▶️ Run

```bash
pip install sentence-transformers
python app.py
