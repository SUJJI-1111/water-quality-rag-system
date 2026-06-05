# Water Quality RAG System

## Overview

This project implements an end-to-end Retrieval-Augmented Generation (RAG) pipeline for environmental and water-quality intelligence.

The system transforms structured environmental datasets into semantically meaningful reports, generates dense vector embeddings, stores them inside a FAISS vector database, retrieves contextually relevant environmental records, and uses Gemini LLM to generate grounded responses.

---

## Technologies Used

* Python
* Google Colab
* LangChain
* Sentence Transformers
* FAISS
* Gemini API
* Pandas
* NumPy

---

## Workflow

### 1. Dataset Preprocessing

* Loaded environmental water-quality dataset
* Inspected schema and missing values
* Cleaned noisy records

### 2. Natural Language Transformation

* Converted structured rows into semantic textual reports

### 3. Text Chunking

* Applied recursive chunking strategy using LangChain

### 4. Embedding Generation

* Generated dense vector embeddings using Sentence Transformers

### 5. Vector Database

* Stored embeddings inside FAISS vector database

### 6. Semantic Retrieval

* Retrieved top relevant chunks using vector similarity search

### 7. Prompt Engineering

* Created grounded prompts to reduce hallucination

### 8. Gemini Integration

* Used Gemini LLM for context-aware response generation

---

## Sample Query

```python
Which locations show poor water quality?
```

---

## Features

* Retrieval-Augmented Generation (RAG)
* Semantic search pipeline
* Environmental intelligence assistant
* Hallucination-controlled prompting
* Lightweight local vector database

---

## Future Improvements

* Streamlit web application
* Real-time IoT integration
* Advanced reranking models
* Multimodal environmental intelligence

---

## Author

Sujji S


