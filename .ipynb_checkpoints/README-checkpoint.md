# IMDB Sentiment Analysis

## Overview

Sentiment analysis of IMDB movie reviews using an RNN model implemented with PyTorch.

## RNN Architecture

```
                +----------------------+
                |     Load Dataset     |
                | (Reviews, Labels)    |
                +----------+-----------+
                           |
                           v
                +----------------------+
                | Text Preprocessing   |
                | Lowercase            |
                | Remove Punctuation   |
                | Remove Urls, HTML    |
                | Stopwords(a,an,the)  |
                | Stemming             |
                | Tokenization         |
                | Vectoization (TF-IDF)|
                | Padding              |
                +----------+-----------+
                           |
                           v
                +----------------------+
                | Tensor Conversion    |
                | Dataset              |
                | DataLoader           |
                +----------+-----------+
                           |
                           v
                +----------------------+
                |      RNN Model       |
                | Embedding Layer      |
                | RNN Layer            |
                | Fully Connected      |
                | Sigmoid Output       |
                +----------+-----------+
                           |
               +-----------+-----------+
               |                       |
               v                       v
      +----------------+      +----------------+
      |     Train      |      |    Evaluate    |
      | Forward Pass   |      | Accuracy       |
      | Loss           |      | Precision      |
      | Backpropagation|      | Recall, F1     |
      +--------+-------+      +----------------+
               |
               v
      +------------------------+
      |  New Review Prediction |
      +-----------+------------+
                  |
          +-------+-------+
          |               |
          v               v
     Positive (1)    Negative (0)
```



## Technologies

- Pandas
- NumPy
- re
- NLTK
  - word_tokenize
  - stopwords
  - PorterStemmer
- Scikit-learn
  - LabelEncoder
  - TfidfVectorizer
  - train_test_split
- PyTorch
  - TensorDataset
  - DataLoader
  - nn
  - optim

## Dataset

* IMDB Movie Reviews
* 50,000 reviews
* 49,582 reviews after duplicate removal
* Classes: Positive, Negative

## Model

* Framework: PyTorch
* Architecture: RNN
* Hidden Size: 128
* Optimizer: Adam
* Loss Function: Binary Cross Entropy
* Epochs: 10
  
## Result

The RNN model was trained to classify IMDB reviews into Positive and Negative sentiment categories.
