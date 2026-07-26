# 🎬 Movie Genre Classification using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![NLP](https://img.shields.io/badge/NLP-TF--IDF-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 📌 Project Overview

This project builds a **Movie Genre Classification** system using **Natural Language Processing (NLP)** and **Machine Learning**. The objective is to predict the genre of a movie based on its plot description.

The movie descriptions are cleaned and transformed into numerical features using **TF-IDF Vectorization**. Multiple machine learning algorithms are trained and evaluated to identify the best-performing model for genre prediction.

---

## ✨ Features

- Text preprocessing and cleaning
- Stopword removal
- Lemmatization
- TF-IDF Vectorization
- Multiple ML model comparison
- Performance evaluation using classification metrics
- Model serialization using Joblib
- Prediction on unseen movie descriptions

---

## 📂 Dataset

**Dataset:** IMDb Genre Classification Dataset

**Source:** https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb

The dataset contains movie plot summaries along with their corresponding genres and is used to train and evaluate the classification models.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- Joblib

---

## ⚙️ Data Preprocessing

The following preprocessing techniques were applied before model training:

- Converted text to lowercase
- Removed punctuation and special characters
- Removed stopwords
- Applied lemmatization
- Converted text into TF-IDF feature vectors

---

## 🤖 Machine Learning Models

The following models were trained and evaluated:

- Logistic Regression
- Linear Support Vector Classifier (LinearSVC)
- Random Forest Classifier
- Multinomial Naive Bayes

---

## 📊 Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report

The best-performing model was selected and saved for future predictions.

---

## 💾 Saved Models

The trained model and TF-IDF vectorizer are saved using **Joblib** for inference on unseen movie descriptions.

```
models/
│── movie_genre_model.pkl
│── tfidf_vectorizer.pkl
```

---

## 📁 Project Structure

```
Movie-Genre-Classification/
│
├── models/
│   ├── movie_genre_model.pkl
│   └── tfidf_vectorizer.pkl
│
├── Movie_Genre_Classification.ipynb
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Movie-Genre-Classification.git
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook Movie_Genre_Classification.ipynb
```

---

## 🔮 Future Improvements

- Deep Learning models (LSTM, GRU)
- Transformer-based models (BERT, DistilBERT)
- Hyperparameter tuning
- Web application deployment using Flask or Streamlit
- Multi-label genre classification

---

## 👨‍💻 Author

**Ashit Nayak**

B.Tech CSE (AI & ML)

---

## 📜 License

This project is licensed under the **MIT License**.