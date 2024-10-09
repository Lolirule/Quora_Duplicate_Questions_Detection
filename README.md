# Quora Duplicate Questions Pair Detection

This project focuses on identifying duplicate question pairs in the Quora dataset. The goal is to determine whether two given questions have the same intent, which can help reduce redundant content and improve user experience on platforms like Quora.

The project consists of two main Jupyter notebooks:

### 1. Duplicate Questions Features Notebook
This notebook is dedicated to feature extraction and basic data processing. It includes:
- Preprocessing of text data, including cleaning and normalization.
- Feature extraction, such as:
  - Word count, character count, and tokenization.
  - Common words between two questions.
  - Cosine similarity and other text similarity measures.

These features are used to train machine learning models that classify question pairs as duplicates or non-duplicates.

### 2. Duplicate Questions Advanced Features Notebook
This notebook expands upon the basic feature extraction by introducing more advanced techniques. It includes:
- Deep learning-based feature extraction methods like word embeddings.
- Advanced NLP techniques, such as:
  - Sentence similarity using pre-trained models like Word2Vec or GloVe.
  - Use of TF-IDF and other vectorization techniques for more nuanced text representation.
- Implementation of advanced machine learning algorithms like XGBoost, Random Forests, etc.

Both notebooks offer insights into different approaches to tackle the problem, ranging from simple to more advanced feature engineering and modeling techniques.
