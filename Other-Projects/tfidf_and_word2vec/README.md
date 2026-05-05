# TF-IDF and Word2Vec Exploration

This project explores two major techniques for text vectorization in Natural Language Processing: **TF-IDF** (Term Frequency-Inverse Document Frequency) and **Word2Vec** (Word Embeddings).

## 🚀 Overview
Text data must be converted into numerical vectors before being processed by machine learning algorithms. This repository demonstrates:
- **Manual TF-IDF Implementation**: A step-by-step calculation of TF and IDF scores using pure Python and `math`.
- **Scikit-learn Integration**: Using `TfidfVectorizer` to quickly transform documents into a weighted document-term matrix.
- **Word2Vec Intro**: Concept of semantic word embeddings using `gensim` and NLTK corpora.

## 🛠️ Key Concepts
- **Bag of Words (BoW)**: The foundational approach of counting word occurrences.
- **Term Frequency (TF)**: Measuring how frequently a term occurs in a document.
- **Inverse Document Frequency (IDF)**: Reducing the weight of common words and increasing the weight of rare, meaningful words.
- **Word Embeddings**: Mapping words to dense vector spaces where semantic similarity is captured by vector distance.

## 📈 Tools Used
- **Python** (math, pandas)
- **NLTK** (Corpus handling)
- **Scikit-learn** (Efficient vectorization)
- **Gensim** (Word2Vec implementation)
