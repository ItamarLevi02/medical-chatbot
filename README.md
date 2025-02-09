# 🏥 Medical Chatbot - AI-Powered Medical Q&A  

This repository contains a **Medical Chatbot** that leverages **OpenAI embeddings** and a **Large Language Model (LLM)** to provide real-time answers to medical questions. The chatbot is designed to efficiently retrieve and generate responses based on a preprocessed medical dataset, utilizing **semantic search** and **vector embeddings** stored in a **ChromaDB vector database**.

## 🚀 Features  

- ✅ **Real-Time Medical Q&A** – Instantly responds to user queries with relevant medical information.  
- ✅ **Semantic Search** – Uses OpenAI embeddings to find the most relevant medical data.  
- ✅ **Efficient Vector Database** – Stores parsed and embedded medical knowledge in ChromaDB.  
- ✅ **LLM-Powered Answers** – Generates context-aware responses using OpenAI’s language model.  
- ✅ **Flask Deployment** – Lightweight and scalable backend with Flask.  

## 🛠️ Tech Stack  

- **Python** – Core programming language  
- **Flask** – Backend API framework  
- **ChromaDB** – Vector database for storing and retrieving embeddings  
- **OpenAI Embeddings** – Converts medical data into vector representations  
- **OpenAI LLM** – Processes user queries and formulates responses  

## 🏗️ How It Works  

1. **Medical Data Processing**  
   - The provided medical dataset is **parsed, embedded**, and stored in **ChromaDB**.  

2. **User Query Handling**  
   - The chatbot takes a **user’s medical question** and performs a **semantic search** across the vector database.  

3. **LLM-Generated Response**  
   - The relevant medical context is retrieved, and the **LLM** formulates an accurate response.  

4. **Flask API**  
   - The backend is built using **Flask**, which exposes an API to handle user queries and return responses.  

## 🛠️ Installation & Setup  

### 🔹 Prerequisites  

Ensure you have the following installed:  
- Python 3.x  
- OpenAI API key  
- ChromaDB installed  

### 🔹 Installation  

```bash
# Clone the repository
git clone https://github.com/yourusername/medical-chatbot.git
cd medical-chatbot

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt
```

### Environment Variables

Create a .env file in the root directory and add the following information:

OPENAI_API_KEY=your_openai_api_key

### 🔹 Running the Chatbot
python app.py





