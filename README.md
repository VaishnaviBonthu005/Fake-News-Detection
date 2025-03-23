# Fake News Detection

This project aims to detect fake news using machine learning and natural language processing techniques. It uses the LIAR dataset to classify news statements as "True" or "False."

## Features
- Text preprocessing (cleaning, stopword removal, etc.).
- TF-IDF for feature extraction.
- Naive Bayes for classification.
- Model evaluation (accuracy, confusion matrix, classification report).

## Files
- `Fake_News_Detection.ipynb`: Google Colab notebook containing the code.
- `train.tsv`: LIAR dataset used for training.
- `fake_news_model.pkl`: Trained model (optional).
- `tfidf_vectorizer.pkl`: TF-IDF vectorizer (optional).

## How to Run
1. Open the `Fake_News_Detection.ipynb` notebook in Google Colab.
2. Upload the `train.tsv` dataset.
3. Run the cells in the notebook to preprocess the data, train the model, and evaluate its performance.

## Requirements
- Python 3.x
- Libraries: Pandas, NumPy, Scikit-learn, NLTK, Matplotlib, Seaborn
