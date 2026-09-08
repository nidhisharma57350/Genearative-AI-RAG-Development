## Groq RAG Chatbot

A simple Retrieval-Augmented Generation (RAG) chatbot built using LangChain, Groq API, and ChromaDB.

This project allows users to ask questions based on the information available in their documents. The chatbot retrieves relevant information from the stored documents and uses an LLM to generate an answer.

# Features:
Document-based question answering

Semantic search using vector embeddings

ChromaDB for vector storage and retrieval

LangChain for building the RAG pipeline

Groq API for fast LLM responses

Simple question-answering chatbot

# Technologies Used:
Python

LangChain

Groq API

ChromaDB

Hugging Face / Sentence Transformers

Google Colab / Jupyter Notebook

## How RAG Works:

The basic workflow of this project is:

Documents
    ↓
Document Loading
    ↓
Text Splitting
    ↓
Create Embeddings
    ↓
Store in ChromaDB
    ↓
User Question
    ↓
Retrieve Relevant Documents
    ↓
Send Context + Question to LLM
    ↓
Generate Answer

# Basic Usage:

After setting up the documents, embeddings, and ChromaDB, the user can enter a question:

question = input("Ask a question: ")

response = llm.invoke(prompt)

print("\nAnswer:")
print(response.content)

The retrieved document context is provided to the language model so that it can generate a relevant answer.

# Author:

Nidhi Sharma
