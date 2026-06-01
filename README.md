# Python Tutor RAG Assistant

A Retrieval-Augmented Generation (RAG) based AI tutoring assistant designed to answer Python-related questions using semantic retrieval and Large Language Models (LLMs).

---

## Overview

This project explores the fundamentals of RAG systems by combining:

- Document preprocessing
- Text chunking
- Embedding generation
- Vector similarity search
- Context-aware LLM response generation

The system retrieves relevant information from stored knowledge before generating responses, helping reduce hallucinations and improve answer accuracy.

---

## Features

- Semantic search for Python-related queries
- Embedding-based document retrieval
- Context-aware answer generation
- Prompt engineering workflows
- Jupyter Notebook implementation

---

## Technologies Used

- Python
- Jupyter Notebook
- NLP
- Large Language Models (LLMs)
- Vector Retrieval
- Embeddings
- RAG Architecture

---

## How It Works

1. Documents are processed and split into chunks.
2. Embeddings are generated for each chunk.
3. User queries are converted into embeddings.
4. Similar chunks are retrieved using vector similarity.
5. Retrieved context is passed to the LLM for grounded response generation.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/python-tutor-rag.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Usage

Open the notebook:

```bash
jupyter notebook
```

Run:

```text
Python_Tutor_RAG.ipynb
```

---

## Future Improvements

- Add a web interface
- Integrate advanced vector databases
- Improve retrieval ranking
- Support multi-document querying
- Deploy as an interactive chatbot
