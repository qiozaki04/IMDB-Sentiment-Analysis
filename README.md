# Sentiment Analysis using Bidirectional LSTM

## 📌 What are you making?

This project is a **binary sentiment classification model** that analyzes textual input (e.g. movie reviews) and predicts whether the sentiment is **positive** or **negative**.
The model is trained using a labeled dataset from IMDb, making it suitable for natural language understanding tasks in NLP.

## 🧠 What architecture you use?

We use a deep learning architecture that combines **embedding layers**, **Bidirectional LSTM**, and **dense layers** with dropout and regularization:

- `Embedding Layer` to map input tokens into dense vector space.
- `Bidirectional LSTM Layer` to capture both forward and backward context.
- `Dense Layers` with ELU activations and L2 regularization.
- `Dropout Layers` to reduce overfitting.
- `Sigmoid Output Layer` for binary classification.

## 📚 What libraries you use?

- TensorFlow
- os
- string
- seaborn
- tqdm
- bs 4
- nltk
- NumPy
- Pandas
- Matplotlib (optional)
- scikit-learn (optional)

## 🚀 How to run your model

1. Upload `kaggle.json`
2. Download dataset
3. Install dependencies
4. Ubah sentimen yang awalnya berbentuk string menjadi bentuk angka (0 dan 1)
5. Visualisasikan data yang telah diubah
6. Bersihkan k
4. Jalankan `model.fit(...)`

## 📂 Dataset Reference

- [IMDb Sentiment Dataset on Kaggle](https://www.kaggle.com/datasets/guglielmocerri/imdb-sentiment-analysis)

## 📄 Paper / Research Reference

- Maas, A.L. et al., ACL 2011 — Learning word vectors for sentiment analysis.
- Zhou, P. et al., ACL 2016 — Attention-Based BiLSTM for Relation Classification.
"""
