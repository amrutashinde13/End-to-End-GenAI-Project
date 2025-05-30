# 🧠 Generative AI-Based Information Retrieval System

This project is an end-to-end Generative AI-powered Information Retrieval System built using LangChain, LLMs, FAISS VectorDB, and Streamlit. It allows users to upload PDF documents and interactively query the content using natural language, receiving accurate, context-aware responses generated by a language model.

## 🚀 Features

- Upload and process PDF documents with ease
- Automatic text extraction and intelligent chunking
- Embedding generation using Google PaLM Embeddings
- Store and retrieve relevant content using FAISS VectorDB
- Real-time query processing and context-aware responses
- Chat-based Q&A system powered by Google PaLM LLM
- Intuitive and interactive UI built with Streamlit
- Supports ongoing conversations with conversation memory

## 🔧 Technologies Used

- **LangChain** – LLM pipeline and orchestration  
- **GooglePalmEmbeddings** – Semantic vector embedding  
- **FAISS** – Fast Approximate Nearest Neighbors Search  
- **GooglePalm** – Large Language Model for query response  
- **PyPDF2** – Text extraction from PDFs  
- **Streamlit** – Interactive frontend (coming soon / optional)  
- **dotenv** – For secure API key management
  
## 📈 Flow Overview

- Upload PDF → Extract content
- Text Chunking → Break into meaningful sections
- Embeddings → Convert chunks into vector form
- FAISS Indexing → Create semantic search index
- Query Input → Convert user question into embedding
- Semantic Search → Retrieve relevant chunks
- LLM Response → Generate and return answer

## 🏥 Use Case
Ideal for healthcare organizations or analysts to semantically explore policy documents, clinical guidelines, or value-based payment models by simply uploading documents and asking questions, saving time and improving document comprehension.
