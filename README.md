# Word2Vec
The goal of this project is to create word embeddings using the Word2Vec model with Gensim and use these embeddings in machine learning tasks such as text classification, clustering, or sentiment analysis. The project demonstrates how to build word embeddings from a corpus and how to use these embeddings as input to a machine learning model.
# Word Embedding using Word2Vec and Supervised Learning

## Project Description

This project generates word embeddings using the Word2Vec model from Gensim and utilizes these embeddings for supervised learning tasks like text classification. Word2Vec transforms text into meaningful vector representations, which can then be fed into machine learning models to improve their ability to capture semantic relationships between words.

### Objective

The project aims to:
1. Preprocess a corpus of text data.
2. Train a Word2Vec model to generate word embeddings.
3. Use the generated embeddings as input features for a supervised learning model.
4. Evaluate the model's performance on text classification or other tasks.

### Dataset

You can use a text dataset such as:
- **IMDB Movie Reviews** for sentiment analysis (binary classification).
- **20 Newsgroups** for topic classification (multi-class classification).

Ensure the dataset contains labeled text documents for the supervised learning task.

### Project Structure

- **`data/`**: Contains the raw text data.
- **`embeddings/`**: Contains the trained Word2Vec model and saved word vectors.
- **`models/`**: Contains scripts for training the supervised learning model.
- **`notebooks/`**: Jupyter notebooks for interactive data exploration and model training.
- **`src/`**: Source code for text preprocessing, Word2Vec embedding generation, and model training.
- **`requirements.txt`**: Lists dependencies required for the project.
- **`README.md`**: This file.

## Getting Started

### Prerequisites

Ensure the following libraries are installed:

- Python 3.x
- Gensim (for Word2Vec)
- Scikit-learn (for supervised learning models)
- NLTK or SpaCy (for text preprocessing)
- Pandas and NumPy (for data manipulation)

You can install these using:

```bash
pip install -r requirements.txt
