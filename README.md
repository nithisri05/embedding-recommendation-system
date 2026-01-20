# Embedding-Based Recommendation System

This project demonstrates a **semantic recommendation system** built using **OpenAI embeddings** and **cosine similarity** to recommend news articles based on meaning rather than keyword matching.

Unlike traditional keyword-based systems, this approach converts text into numerical vectors (embeddings) and performs similarity search in vector space.



## Project Overview

Given a news article, the system:
1. Converts article descriptions into vector embeddings
2. Computes semantic similarity using cosine distance
3. Identifies and recommends the most similar articles
4. Uses caching to avoid repeated API calls and rate-limit issues

This project follows best practices inspired by the OpenAI Cookbook and real-world Retrieval-Augmented Generation (RAG) systems.



## Key Concepts Used

- **Text Embeddings**
- **Semantic Similarity**
- **Cosine Distance**
- **Caching with Pickle**
- **Vector-Based Recommendation**
- **Efficient API Usage**



## Architecture Flow

```text
Article Text
     ↓
OpenAI Embedding Model
     ↓
Vector Representation
     ↓
Cosine Similarity
     ↓
Top-K Similar Articles
```
## Tech Stack

- **Python** – core programming language  
- **OpenAI Embeddings (`text-embedding-3-small`)** – semantic vector representation  
- **Pandas** – data handling and preprocessing  
- **NumPy** – vector and numerical operations  
- **Scikit-learn** – cosine similarity computation  
- **Pickle** – persistent embedding caching  
- **Google Colab** – development and experimentation environment  
- **GitHub** – version control and project hosting  





