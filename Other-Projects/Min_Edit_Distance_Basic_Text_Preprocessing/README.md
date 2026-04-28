# Minimum Edit Distance & Basic Text Preprocessing

This project explores foundational Natural Language Processing (NLP) techniques for text normalization and preprocessing using the powerful NLTK library in Python.

## 📝 Overview

The Jupyter Notebook included in this directory walks through essential steps needed to prepare raw text data for advanced text analysis and machine learning models.

### Key Concepts Covered:
* **Tokenization:** Breaking down text into sentences and words using various tokenizers (`word_tokenize`, `wordpunct_tokenize`, and customized `regexp_tokenize`).
* **Stemming:** Normalizing words to their root forms using different stemmers (LancasterStemmer, PorterStemmer, SnowballStemmer) to understand their trade-offs.
* **Lemmatization:** A more robust, context-aware normalization using `WordNetLemmatizer`.
* **Stop Word Removal:** Filtering out common, non-informative words using predefined NLTK stop word lists to reduce noise in the data.
* **Minimum Edit Distance & Spelling Correction:** Basic spelling correction implementations using dictionary lookups and editing algorithms.

## 🚀 How to Run

1. Open `Min_Edit_Distance_Basic_Text_Preprocessing.ipynb` on Google Colab or your local Jupyter environment.
2. Ensure you have the `nltk` library installed (`pip install nltk`).
3. Run the cells sequentially to download necessary NLTK data packages (like `punkt`, `wordnet`, `stopwords`) and execute the preprocessing pipeline.
