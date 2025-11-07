# 🎥 Movie Review Sentiment Analysis

This project is a **Sentiment Analysis Web App** that classifies movie reviews as **Positive** or **Negative** using Machine Learning and Natural Language Processing (NLP) techniques.  
It is built with **Python**, **Streamlit**, and **scikit-learn**, providing an interactive interface for users to analyze text sentiment in real time.

---

## 🧠 Project Overview

The goal of this project is to analyze the sentiment of movie reviews from a dataset and predict whether a given review expresses a **positive** or **negative** opinion.  
The model is trained using various supervised learning algorithms and text preprocessing methods such as tokenization, stemming, and TF-IDF vectorization.

---

## ⚙️ Technologies & Libraries Used

- **Python 3.x**
- **NumPy**
- **Pandas**
- **scikit-learn**
- **NLTK**
- **Streamlit**
- **Pickle** (for model serialization)

---

## 📚 Models Implemented

The following models were trained and evaluated:
1. **Logistic Regression**
2. **Naive Bayes**
3. **Support Vector Machine (SVM)**
4. **Decision Tree Classifier**
5. **Random Forest Classifier**

Each model’s performance was compared to find the best one for deployment.

---

## 💻 Streamlit Web App

A **Streamlit** interface was created to allow users to enter a movie review and instantly see whether it’s positive or negative.

To run the app locally:

```bash
# 1️⃣ Activate your virtual environment
.\.venv\Scripts\activate

# 2️⃣ Install dependencies
pip install -r requirements.txt

# 3️⃣ Run the Streamlit app
python -m streamlit run app.py
