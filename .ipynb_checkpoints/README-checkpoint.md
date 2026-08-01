#  Sentiment Analysis - IMDB using PyTorch

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


- **Review** –  review text
- **Sentiment** – Positive / Negative

Label Encoding:

| Sentiment | Label |
|-----------|------:|
| Negative  | 0 |
| Positive  | 1 |

---

## Tech Stack

- Python
- PyTorch
- TorchText 
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
Sentiment-Analysis-IMDB/
│
├── IMDB.ipynb
├── IMDB Dataset.csv
├── .gitignore
├── README.md
```

---

## Model

This project implements a **Recurrent Neural Network (RNN)** using **PyTorch** for binary sentiment classification on IMDB.

