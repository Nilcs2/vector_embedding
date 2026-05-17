# Semantic Search & Vector Mathematics from Scratch

This repository demonstrates the foundational mechanics behind modern Retrieval-Augmented Generation (RAG) and semantic search engines. It bridges the gap between raw mathematical formulas and applied NLP using pre-trained transformer embeddings.

## Features
- **Mathematical Implementations from Scratch:** Native NumPy implementations of Cosine Similarity and Euclidean Distance.
- **Contextual Embeddings:** Utilizing the `BAAI/bge-base-en-v1.5` transformer model via `sentence-transformers` to encode text into 768-dimensional dense vectors.
- **Mini-Retrieval Engine:** A functional document search script that dynamically ranks text documents based on semantic proximity to an input query.

## Quick Start
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Open `semantic_search_basics.ipynb` and run the cells.