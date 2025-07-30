

# NLP Workshop – Vector Representations with Word2Vec and GloVe

## Overview

This repository contains a workshop notebook focused on building a full **NLP pipeline** and exploring word embeddings using both predictive `(Word2Vec)` and count-based `(GloVe)` approaches. The corpus used is domain-specific and customizable depending on the context of the final project (e.g., student services, healthcare, product reviews, etc.).

Each notebook features:
- Step-by-step code for document collection, tokenization, and normalization
- Implementation of Word2Vec using the gensim library
- Implementation of GloVe using the glove-python-binary library
- Markdown explanations of each major concept to support learning and reproducibility

---

## 👥 Team Members

- Babandeep – ID: 9001552  
- Hasyashri Bhatt – ID: 9028501  
- Paula Ramirez – ID: 8963215  

---

## Project Structure
 
- `EmbeddingClusteringVectorizationWorkshop.ipynb`  
  - Builds an NLP pipeline and implements Word2Vec and GloVe models using a custom knowledge corpus

- `data`  
  - Contains the dataset: a collection of FAQs generated using ChatGPT, with questions and answers on various topics

 
---

### Features:

- Build and preprocess a domain-specific corpus (tokenization, stopword removal, stemming)
- Train a Word2Vec model to learn word representations based on context
- Train a GloVe model using co-occurrence statistics and matrix factorization
- Compare output of both models using similarity queries
- Use clean and documented code cells with Markdown to explain each NLP task

---
 

##  Sample Queries Tested

- Retrieve most similar words to a given target (e.g., "student", "data")
- Compare Word2Vec vs. GloVe representations for selected vocabulary
- Visual inspection of vector space dimensions and co-occurrence matrices
- Training models on cleaned and tokenized domain-specific corpus
- Save and reload trained embedding models


## 🚀 Quick Start

```bash
python -m venv venv
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
.\venv\Scripts\activate
pip install -r requirements.txt
```

