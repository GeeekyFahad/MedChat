# MedChat
MedChat – AI-Powered Medical Information Chatbot

MedChat is an AI-driven medical chatbot designed to provide accurate, context-aware answers to healthcare-related queries using a Retrieval-Augmented Generation (RAG) approach. Unlike traditional chatbots that rely only on a language model, MedChat retrieves relevant medical information from a knowledge base before generating responses, reducing hallucinations and improving reliability.

Features :
NLP-based understanding of medical queries
Retrieval-Augmented Generation (RAG) pipeline
Semantic search using vector embeddings
Fast and context-aware responses
Modular and scalable architecture
Privacy-focused design (no sensitive data storage)

System Architecture :
MedChat follows a RAG-based architecture:
User submits a query
Query is converted into embeddings
Relevant documents are retrieved using vector similarity search
Retrieved context is injected into the prompt
LLM generates a grounded response
Response is returned to the user

Tech Stack
Programming Language: Python
NLP & AI: Transformer-based embeddings, LLM
Backend: Flask / Streamlit
Vector Database: pinecone

Architecture: Retrieval-Augmented Generation (RAG)
