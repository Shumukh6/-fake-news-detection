# 📰 Fake News Detection using NLP & Logistic Regression

This project aims to build a machine learning model that can classify whether a news article is **fake or real** using natural language processing techniques.

## 📁 Dataset
The dataset consists of two CSV files:
- `Fake.csv`: Fake news articles
- `True.csv`: Real news articles

Total combined records after preprocessing: **~43,987**

## 🧠 Techniques Used
- **Data Cleaning**: Removing short articles, duplicates, and missing values
- **Text Preprocessing**:
  - Stopword removal
  - Stemming using PorterStemmer
  - Combining title and subject for richer features
- **Feature Extraction**: TF-IDF Vectorization
- **Model Used**: Logistic Regression
- **Accuracy**:
  - Training accuracy: **99.99%**
  - Testing accuracy: **99.89%**

## 🛠 Tools & Libraries
- Python
- Pandas, NumPy
- NLTK
- Scikit-learn

## 📌 Output
A trained binary classification model that can predict whether a news article is **real or fake**.

## 📂 File
- `Fake_news_prediction.ipynb` — Jupyter notebook containing the full implementation.


