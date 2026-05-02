# Movie-Intelligence-Character-Rag
# 🎬 Movie Plot & Character Intelligence using RAG

This project implements a Retrieval-Augmented Generation (RAG) system to analyze movie plots, character motivations, and themes. The system answers deep reasoning questions using real movie data instead of relying only on model knowledge.

---

## 🚀 Project Overview

Traditional language models often generate generic or incorrect answers due to lack of grounding.  
This project solves that problem by combining:

- 🔍 Retrieval (from movie dataset)
- 🤖 Generation (using LLMs)

This results in more accurate, context-aware, and meaningful responses.

---

## 🧠 Features

- Deep reasoning on movie plots and characters  
- Emotion-aware question answering  
- Reduced hallucination using RAG  
- Comparison of multiple LLMs  
- Works with real-world movie data  

---

## 📂 Dataset

We created a custom dataset using 5 movies:

- The Dark Knight  
- Joker  
- Interstellar  
- Iron Man  
- Inception  

Data includes:
- Plot summaries  
- Character analysis  
- Themes  
- Dialogues  

---

## ❓ Sample Questions

- Why did Joker become a villain?  
- What motivates Tony Stark?  
- What is the theme of Interstellar?  
- How does guilt affect Cobb in Inception?  
- Why did Harvey Dent become Two-Face?  

---

## ⚙️ System Architecture

Pipeline:

Data → Chunking → Embeddings → FAISS → Retrieval → LLM → Answer  

---

## 🛠️ Technologies Used

- Python  
- LangChain  
- FAISS  
- HuggingFace (Embeddings)  
- Ollama (LLMs)  

---

## 🤖 Models Used

- LLaMA 3  
- Mistral  
- Phi-3  

---

## 📊 Evaluation Metrics

- Accuracy  
- Reasoning  
- Emotion Understanding  
- Hallucination  

---

## 📈 Results Summary

| Model   | Accuracy | Reasoning | Emotion | Hallucination |
|--------|---------|----------|--------|--------------|
| LLaMA  | 3.0     | 4.0      | 4.0    | 2.0          |
| Mistral| 2.8     | 4.0      | 3.8    | 2.0          |
| Phi-3  | 3.2     | 4.0      | 4.0    | 2.0          |

👉 **Best Model: Phi-3**

---

## 🧪 How to Run

1. Install dependencies:
```bash
pip install langchain langchain-community langchain-text-splitters faiss-cpu sentence-transformers
