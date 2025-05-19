# 🍽️ CravingBot – Real-Time Food Recommendation using LLMs RAG based

CravingBot is an intelligent food recommendation system that understands your cravings and suggests the most suitable Indian dishes. Powered by LangChain, OpenAI, and FAISS, it uses semantic similarity to match user inputs with a curated dataset of 300+ dishes based on taste, ingredients, and cuisine.

---

## 🚀 Features

- 🧠 **LLM-Powered Recommendations** using OpenAI's GPT model  
- 🧂 **Craving-Based Retrieval** from a dish dataset using FAISS vector database  
- 🍛 **Rich Dish Metadata** including cuisine, type, ingredients, and craving type  
- 🗣️ **Natural Language Queries** like "I want something spicy and crispy"

---

## 🗃️ Dataset

The dataset contains over 300 Indian dishes with the following columns:

- `Dish Name`  
- `Ingredients`  
- `Cuisine`  
- `Type` (e.g., Curry, Appetizer, Snack)  
- `Craving Type` (e.g., Spicy, Rich, Comforting)

These are combined into semantic descriptions used for embedding.

---

## 🛠️ Tech Stack

- 🐍 Python  
- 🦜 LangChain  
- 🤖 OpenAI (GPT-4 or GPT-3.5-Turbo)  
- 🔍 FAISS (Vector Database)  
- 🧠 LLM Embeddings using `OpenAIEmbeddings`  
- 📊 Pandas for data handling

---

## 📦 Installation

```bash
pip install langchain openai faiss-cpu tiktoken pandas
