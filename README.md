DocuMind: RAG-Based Document Q&A Assistant

Overview
DocuMind is a Retrieval-Augmented Generation (RAG) system designed to answer questions from unstructured documents using semantic search and LLMs.

Tech Stack

Python
LangChain
FAISS
Sentence Transformers
FLAN-T5 / LLM APIs

Features

📄 PDF ingestion and processing
🔍 Semantic search using vector embeddings
🤖 Context-aware answer generation
⚡ Fast retrieval with FAISS

How it works

Documents are split into chunks
Chunks are converted into embeddings
FAISS retrieves relevant chunks
LLM generates answer based on context
