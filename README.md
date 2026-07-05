# AI Research Paper Search Engine

> An AI-powered Research Paper Search Engine and Research Assistant built using Retrieval-Augmented Generation (RAG), FAISS Vector Database, Sentence Transformers, and Natural Language Processing (NLP).

The system enables semantic search over research papers, recommends similar papers, extracts important keywords and named entities, estimates reading time, performs document analytics, and generates context-aware answers using Large Language Models (LLMs).

---

# Project Overview

Searching research papers using traditional keyword search often misses semantically relevant documents.

This project leverages modern NLP and Retrieval-Augmented Generation (RAG) techniques to build an intelligent research assistant capable of understanding the meaning of user queries instead of matching exact keywords.

The system generates dense vector embeddings for research papers, stores them in a FAISS vector database, retrieves the most relevant documents using semantic similarity, and enhances answers with Large Language Models.

---

# Objectives

- Build an AI-powered semantic search engine
- Improve research paper discovery
- Recommend similar research papers
- Extract valuable information from research papers
- Demonstrate practical applications of Retrieval-Augmented Generation (RAG)

---

# Main Pipeline

The project follows the complete AI pipeline below:

- Load ML ArXiv Papers Dataset
- Data Cleaning & Preprocessing
- Combine Title + Abstract
- Generate Embeddings using Sentence Transformers
- Store Embeddings in FAISS Vector Database
- Semantic Similarity Search
- Similarity Score Calculation
- Keyword Extraction
- Named Entity Recognition (NER)
- Similar Research Paper Recommendation
- Reading Time Estimation
- Abstract Length Analysis
- Word Cloud Visualization
- Retrieval-Augmented Generation (RAG)
- AI-Powered Question Answering

---

# Key Features

- Semantic Search
- Retrieval-Augmented Generation (RAG)
- FAISS Vector Search
- Sentence Transformer Embeddings
- Similar Research Paper Recommendation
- Keyword Extraction
- Named Entity Recognition (NER)
- Reading Time Estimation
- Abstract Length Analysis
- Word Cloud Generation
- AI-powered Research Assistant
- Context-aware Question Answering

---

# Technologies Used

- Python
- Pandas
- NumPy
- Hugging Face Datasets
- Sentence Transformers
- FAISS
- Transformers
- PyTorch
- Scikit-learn
- Matplotlib
- WordCloud
- spaCy
- Jupyter Notebook

---

# Repository Structure

```
ai-research-paper-search-engine/
│
├── README.md
├── requirements.txt
├── notebooks/
│   └── RAISIP.ipynb
│
├── dataset/
│
├── faiss_index/
│
├── images/
│
├── results/
│
└── utils/
```

---

# Example Workflow

User Query

↓

Convert Query into Embedding

↓

Search Similar Papers using FAISS

↓

Retrieve Top Relevant Research Papers

↓

Generate AI Response using RAG

↓

Display Final Answer

---

# Use Cases

- Academic Literature Search
- AI Research Assistant
- Semantic Paper Search
- Research Paper Recommendation
- Knowledge Discovery
- Intelligent Document Retrieval
- Educational Assistant

---

# Future Improvements

- Streamlit Web Application
- PDF Upload Support
- Multi-document Question Answering
- Citation Generation
- Hybrid Search (Keyword + Semantic)
- Research Paper Summarization
- Conversational AI Interface
- Docker Deployment
- Cloud Deployment

---

# Requirements

```
pandas
numpy
datasets
sentence-transformers
faiss-cpu
transformers
torch
scikit-learn
matplotlib
wordcloud
spacy
jupyter
```

---

# Results

The project successfully demonstrates:

- Fast semantic retrieval using FAISS
- Context-aware search instead of keyword matching
- Intelligent research paper recommendation
- Automatic keyword extraction
- Named Entity Recognition
- Reading time estimation
- Abstract analytics
- AI-generated responses using Retrieval-Augmented Generation

---

# Author

**Aditya Kumar Rai**

B.Tech Information Technology

Maharaja Agrasen Institute of Technology (MAIT), Delhi

GitHub: https://github.com/AdityaKumarRai480-bit

---

# License

This project is released for educational and portfolio purposes.
