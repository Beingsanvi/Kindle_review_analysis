# 📚 Kindle Review Sentiment Analysis (NLP Project)

## 🚀 Overview
This project focuses on building a Natural Language Processing (NLP) pipeline to classify Kindle reviews as **positive** or **negative**.  
The goal was to understand how raw text data can be cleaned, transformed, and used to train machine learning models effectively.

---

## 🧠 Problem Statement
Text data is unstructured and noisy. This project aims to:
- Clean and preprocess textual data
- Convert text into numerical features
- Train a model to predict sentiment

---

## ⚙️ Workflow

### 1. Data Preprocessing
- Converted text to lowercase
- Removed special characters using regex
- Removed stopwords
- Applied lemmatization

### 2. Feature Extraction
Two techniques were used:
- **Bag of Words (BoW)**
- **TF-IDF Vectorization**

### 3. Model Building
Used:
- **Multinomial Naive Bayes**

> **Reason:** Works well with text data based on word frequency

### 4. Train-Test Split
- 80% Training
- 20% Testing
- Used `random_state=42` for reproducibility

### 5. Evaluation Metrics
- Accuracy Score
- Confusion Matrix

---

## 📊 Key Insights
- TF-IDF performed better than Bag of Words
- MultinomialNB is more suitable for text data compared to GaussianNB
- Proper preprocessing significantly improves model performance

---

## 🛠️ Tech Stack
| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Scikit-learn | ML models & evaluation |
| NLTK | Text preprocessing |

---

## 📂 Project Structure
```
├── kindle_review.ipynb
├── README.md
```

---

## 💡 Future Improvements
- [ ] Try Logistic Regression / SVM
- [ ] Add hyperparameter tuning
- [ ] Use advanced NLP techniques (Word2Vec, BERT)
- [ ] Deploy as a web app

---

## 📌 Conclusion
This project helped in understanding the complete NLP pipeline — from raw text to model prediction.

---

## 🤝 Connect With Me
If you found this interesting or have suggestions, feel free to connect!

⭐ **If you like this project, consider giving it a star!**