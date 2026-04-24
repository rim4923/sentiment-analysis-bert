# Sentiment Analysis using BERT vs Logistic Regression

## Overview

This project compares a traditional machine learning model (Logistic Regression) with a transformer-based model (BERT) for sentiment analysis.

The goal is to evaluate how well modern deep learning models outperform classical approaches in understanding text sentiment.

---

## Dataset

* IMDB Movie Reviews dataset
* Binary classification: Positive / Negative
* ~25,000 training and 25,000 testing samples (subset used for efficiency)

---

## Models Implemented

### 1. Logistic Regression (Baseline)

* Feature extraction using TF-IDF
* Fast and efficient
* Limited contextual understanding

### 2. BERT (Transformer Model)

* Pre-trained transformer model fine-tuned for classification
* Captures full sentence context (bidirectional)
* Significantly higher accuracy

---

## Preprocessing

* Lowercasing text
* Tokenization
* TF-IDF (for Logistic Regression)
* BERT tokenizer (for transformer model)

---

## Technologies

* Python
* scikit-learn
* HuggingFace Transformers
* PyTorch
* Jupyter Notebook

---

## Results

| Model               | Accuracy   | F1 Score   |
| ------------------- | ---------- | ---------- |
| Logistic Regression | 0.85       | 0.86       |
| BERT                | **0.9155** | **0.9162** |

### Key Observations

* BERT significantly outperforms Logistic Regression
* Better handling of context, sarcasm, and complex sentences
* Balanced precision and recall

---

## Key Learnings

* Traditional ML models struggle with contextual understanding
* Transformer models (BERT) capture semantic meaning effectively
* Trade-off between performance and computational cost

---

## Project Structure

* `project.ipynb` → main implementation
* `docs/` → project report

---

## Notes

This project was developed as part of coursework at Lebanese American University.
