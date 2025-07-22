# 📰 News Topic Classifier

This project is part of Task 1 and focuses on building a **news topic classification system** using **Natural Language Processing (NLP)** and a **Multinomial Naive Bayes** classifier. The system is designed to predict the category of a news article based on its textual content.

---

## 📌 Objective

To classify news articles into predefined categories (topics) by analyzing their textual content using classic machine learning and NLP techniques.

---

## 📁 Dataset

- Source: The dataset contains labeled news articles.
- Features:
  - `text`: The body/content of the news article.
  - `category`: The target label (news topic).

---

## ⚙️ Technologies & Libraries Used

- Python
- scikit-learn
- pandas
- matplotlib / seaborn (for EDA & visualization)
- nltk (for stopwords and preprocessing)

---

## 🔍 Key Steps

### 1. Data Preprocessing
- Loaded dataset and checked for null values
- Basic EDA to understand the distribution of topics
- Text normalization: lowercasing, punctuation removal
- Stopword removal using NLTK
- Vectorization using **CountVectorizer** (Bag of Words)

### 2. Model Building
- Algorithm: **Multinomial Naive Bayes**
- Trained on vectorized text data
- Evaluated using accuracy, classification report, and confusion matrix

### 3. Evaluation
- Accuracy score calculated
- Confusion matrix plotted
- Classification report with precision, recall, and F1-score

---

## 📈 Results

- ✅ The classifier was able to accurately predict topics on unseen data.
- 📊 Metrics like accuracy, precision, recall, and F1-score were reported.

---

## 🧠 Skills Gained

- Text preprocessing and feature extraction
- Vectorization using CountVectorizer
- Building and evaluating Naive Bayes classifiers
- Interpretation of classification reports and confusion matrices

---
