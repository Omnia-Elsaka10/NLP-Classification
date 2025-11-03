# 🧠 Twitter Sentiment Analysis

A Machine Learning project that classifies tweets into **Positive**, **Negative**, **Neutral**, and **Irrelevant** sentiments using both text and topic features.

---

## 📊 Project Overview

This project aims to analyze the sentiment of tweets using traditional Machine Learning models.  
It includes text preprocessing, feature extraction, and model training with evaluation.

---

## 🧹 Data Preprocessing

Steps applied to the dataset:
- Removed missing or duplicate entries  
- Cleaned text (lowercasing, removing URLs, mentions, and special characters)  
- Applied **TF-IDF Vectorization** on tweet text  
- Applied **One-Hot Encoding** on the `topic` column  
- Combined both features for model training  

---

## ⚙️ Models Used

The following machine learning models were trained and compared:
1. **Logistic Regression**
2. **Naive Bayes**
3. **Random Forest Classifier**

---

## 🏆 Model Performance

| Model | Accuracy | Key Notes |
|--------|-----------|------------|
| Logistic Regression | ~78% | Balanced baseline performance |
| Naive Bayes | ~68% | Fast but less accurate |
| Random Forest (Tuned) | **~96%** | Best performance after tuning |

---

## 🔍 Insights & Conclusion

- The **Random Forest** model achieved the highest accuracy (~96%) after hyperparameter tuning.  
- Including both text and topic features improved performance.  
- Future improvements:
  - Try **XGBoost**, **LightGBM**, or **BERT** for more advanced results.  
  - Use **cross-validation** and **grid search** for deeper model optimization.

---

## 💻 Tech Stack

- Python  
- Scikit-learn  
- Pandas & NumPy  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---


## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Omnia-Elsaka10/NLP-Classification.git

