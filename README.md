# **Pinecone Hybrid Search with BM25 and HuggingFace Embeddings**

This project demonstrates how to build a **hybrid search system** using Pinecone's vector database, BM25 for sparse retrieval, and HuggingFace embeddings for dense retrieval. It processes a folder of `.txt` files, encodes them for sparse and dense vectors, and enables efficient search and retrieval.

---

## **Features**
- Integrates **BM25 sparse retrieval** with **dense embeddings** from HuggingFace.
- Processes and indexes `.txt` files from a folder.
- Supports hybrid search using **PineconeHybridSearchRetriever**.
- Handles preprocessing and validation for clean and meaningful inputs.

---

## **Prerequisites**
1. Python 3.8 or later.
2. Required libraries:
   - `pinecone-client`
   - `langchain`
   - `langchain-community`
   - `pinecone-text`
3. A Pinecone API key.
4. A HuggingFace API token.

---

## **Setup Instructions**

### 1. Install Dependencies
Install the required Python libraries:
```bash
pip install pinecone-client langchain langchain-community pinecone-text
