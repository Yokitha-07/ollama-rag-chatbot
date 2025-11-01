# 🧠 Ollama RAG Chatbot

A lightweight **Retrieval-Augmented Generation (RAG)** chatbot built with Ollama, capable of retrieving relevant information from a local text dataset and generating intelligent responses using open-source LLMs.

---

## 🚀 Features

- Uses **local embeddings** via Ollama for semantic retrieval  
- Implements **cosine similarity** for ranking relevant chunks  
- Uses **retrieval-augmented generation (RAG)** to ground chatbot answers  
- Simple and easy to customize for any dataset  
- 100% **offline-capable** (no OpenAI API required)

---

## 🧩 Tech Stack

- **Python 3.12**
- **Ollama** (for embedding + LLM)
- **Llama 3.2 1B Instruct** model for chat
- **BGE Base EN v1.5** model for embeddings

---

## How It Works

- Load Dataset: Reads all lines from your text file.
- Embed Chunks: Generates embeddings for each chunk using the embedding model.
- Retrieve: Computes cosine similarity between query and chunks.
- Generate: Passes top results as context to the LLM to generate an informed response.

## Author: 
Yokitha.R
