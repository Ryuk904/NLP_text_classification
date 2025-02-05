# Text Classification and Word Embeddings

This repository contains implementations of text classification models and word embedding exploration using **Naive Bayes**, **Bag of Words (BoW)**, and **Word2Vec**. The project focuses on sentiment analysis and semantic relationships between words.

## **Overview**
This project demonstrates:
1. **Generative Classification** using Naive Bayes for sentiment analysis.
2. **Word2Vec and Word Analogies** to explore semantic relationships between words.
3. **Discriminative Classification** using Bag of Words (BoW) and Word2Vec with Logistic Regression.

The dataset consists of sentences labeled as positive (`1`) or negative (`0`) sentiment. The models are trained on a training set and evaluated on a validation set.

---

## **Features**
- **Naive Bayes Classifier**:
  - Text preprocessing (lowercasing, stopword removal, tokenization).
  - Vocabulary creation with minimum frequency threshold.
  - Laplace smoothing for handling unseen words.
  - Sentiment prediction using log probabilities.

- **Word2Vec and Word Analogies**:
  - Pre-trained Word2Vec embeddings (Google News vectors).
  - Cosine and Euclidean similarity metrics.
  - Word analogies (e.g., "king - man + woman ≈ queen").
  - Word similarity (e.g., finding words similar to "india" or "book").

- **Bag of Words (BoW) Classifier**:
  - Text preprocessing and vocabulary creation.
  - Feature extraction using word counts.
  - Logistic Regression for sentiment classification.

- **Word2Vec Classifier**:
  - Text preprocessing and document vectorization using averaged word embeddings.
  - Logistic Regression for sentiment classification.



