# 📩 SMS Spam Classification using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![NLP](https://img.shields.io/badge/NLP-TF--IDF-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 📌 Project Overview

This project builds an **SMS Spam Classification** system using **Natural Language Processing (NLP)** and **Machine Learning**. The objective is to automatically classify SMS messages as **Spam** or **Ham (Not Spam)**.

The text messages are preprocessed, converted into numerical representations using **TF-IDF Vectorization**, and classified using multiple machine learning algorithms. The models are compared to identify the best-performing classifier for spam detection.

---

## ✨ Features

- Text preprocessing and cleaning
- Stopword removal
- Lemmatization
- TF-IDF Vectorization
- Multiple ML model comparison
- Performance evaluation using classification metrics
- Model serialization using Joblib
- Prediction on unseen SMS messages

---

## 📂 Dataset

**Dataset:** SMS Spam Collection Dataset

**Source:** https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

The dataset contains thousands of real SMS messages labeled as either **Spam** or **Ham**, making it a standard benchmark dataset for text classification tasks.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib

---

## ⚙️ Data Preprocessing

The following preprocessing techniques were applied before model training:

- Removed duplicate records
- Converted text to lowercase
- Removed punctuation and special characters
- Removed stopwords
- Applied lemmatization
- Converted text into TF-IDF feature vectors
- Train-Test Split using stratified sampling

---

## 🤖 Machine Learning Models

The following models were trained and evaluated:

- Multinomial Naive Bayes
- Linear Support Vector Classifier (LinearSVC)

---

## 📊 Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

The **LinearSVC** model achieved the best overall performance and was selected as the final model for spam prediction.

---

## 💾 Saved Models

The trained model and TF-IDF vectorizer were saved using **Joblib** for future inference.

```
models/
│── spam_classifier.pkl
│── tfidf_vectorizer.pkl
```

---

## 📁 Project Structure

```
SMS-Spam-Classification/
│
├── models/
│   ├── spam_classifier.pkl
│   └── tfidf_vectorizer.pkl
│
├── SMS_Spam_Classification.ipynb
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/SMS-Spam-Classification.git
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook SMS_Spam_Classification.ipynb
```

---

## 📈 Workflow

1. Load and explore the dataset
2. Clean and preprocess SMS messages
3. Convert text into TF-IDF vectors
4. Train multiple machine learning models
5. Compare model performance
6. Select the best-performing model
7. Save the trained model and vectorizer

---

## 🔮 Future Improvements

- Hyperparameter tuning
- Deep Learning models (LSTM, GRU)
- Transformer-based models (BERT)
- Real-time SMS spam detection API
- Web application deployment using Flask or Streamlit

---

## 👨‍💻 Author

**Ashit Nayak**

B.Tech CSE (AI & ML)

---

## 📜 License

This project is licensed under the **MIT License**.