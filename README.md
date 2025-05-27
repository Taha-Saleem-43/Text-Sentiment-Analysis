# 🎬 Task 2: IMDB Sentiment Analysis using Logistic Regression

This project focuses on building a **sentiment analysis model** to classify IMDB movie reviews as either **positive** or **negative** using a **Logistic Regression** classifier.

---

## 📁 Dataset

- **Source**: [IMDB Movie Reviews Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- **Size**: 50,000 labeled reviews
- **Columns**:
  - `review`: The actual movie review (text)
  - `sentiment`: Label — `positive` or `negative`

---

## 🧠 Objective

To develop a binary classification model that can:
- Clean and preprocess raw text data
- Convert text into numerical features using **TF-IDF**
- Train a **Logistic Regression** model
- Predict and evaluate sentiment on test data

---

## 🛠️ Tech Stack

- **Python**
- **Jupyter Notebook**
- **Pandas**, **NumPy**
- **Scikit-learn**
- **NLTK** for NLP
- **Matplotlib** (optional for visualization)

---

## ⚙️ Key Steps

1. **Import libraries & load data**
2. **Text preprocessing**:
   - Lowercasing
   - Removing HTML tags, URLs, and punctuation
   - Tokenization
   - Stopword removal
   - Lemmatization
3. **Label encoding** (`positive` → 1, `negative` → 0)
4. **TF-IDF vectorization**
5. **Train-test split**
6. **Model training with Logistic Regression**
7. **Evaluation using Classification Report**
8. **Custom sentiment prediction function**

---

## 📊 Output

Example prediction:
```python
predict_sentiment("This movie was amazing!")
# Output: Positive
