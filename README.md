# IMDB Movie Reviews Sentiment Analysis using PyTorch

A Deep Learning project that performs binary sentiment classification on IMDB movie reviews using a Recurrent Neural Network (RNN) implemented with **PyTorch**. The model learns to classify movie reviews as **Positive** or **Negative** based on their textual content.

---

##  Project Overview

This project demonstrates how Recurrent Neural Networks (RNNs) can be applied to Natural Language Processing (NLP) for sentiment analysis. The IMDB Movie Reviews dataset is preprocessed, tokenized, converted into numerical sequences, and used to train an RNN model for binary text classification.

---

## Features

- Binary Sentiment Classification
- Text Preprocessing
- Vocabulary Creation
- Tokenization & Numerical Encoding
- Sequence Padding
- Custom PyTorch Dataset & DataLoader
- RNN Model built with PyTorch
- Model Training & Evaluation
- Sentiment Prediction on New Reviews

---

##  Dataset

**Dataset:** IMDB Movie Reviews Dataset

The dataset contains:

- **Review** – Movie review text
- **Sentiment** – Positive / Negative

Label Encoding:

| Sentiment | Label |
|-----------|------:|
| Negative  | 0 |
| Positive  | 1 |

---

## 🛠️ Tech Stack

- Python
- PyTorch
- TorchText (if used)
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

##  Project Workflow

1. Load IMDB Dataset
2. Preprocess Review Text
3. Encode Sentiment Labels
4. Build Vocabulary
5. Convert Text to Numerical Sequences
6. Pad Sequences
7. Create PyTorch Dataset & DataLoader
8. Build RNN Model
9. Train the Model
10. Evaluate Performance
11. Predict Sentiment for New Reviews

---

##  Project Structure

```
IMDB-Sentiment-Analysis-PyTorch/
│
├── IMDB.ipynb
├── IMDB Dataset.csv
├── .gitignore
├── README.md
```

---

## Model

This project implements a **Recurrent Neural Network (RNN)** using **PyTorch** for binary sentiment classification on IMDB movie reviews.

