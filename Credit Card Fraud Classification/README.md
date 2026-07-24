# 💳 Credit Card Fraud Detection using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![XGBoost](https://img.shields.io/badge/XGBoost-Gradient%20Boosting-red)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 📌 Project Overview

This project develops a **Credit Card Fraud Detection** system using Machine Learning to classify financial transactions as **fraudulent** or **legitimate**. Due to the highly imbalanced nature of fraud datasets, appropriate preprocessing, feature engineering, data balancing, and model evaluation techniques were applied to build an effective fraud detection model.

Multiple machine learning algorithms were trained and compared to identify the best-performing model for fraud detection.

---

## ✨ Features

- Data cleaning and preprocessing
- Feature engineering
- Handling missing values and duplicate records
- Log transformation of skewed numerical features
- Feature scaling using StandardScaler
- Handling class imbalance using SMOTE
- Multiple ML model comparison
- Performance evaluation using various classification metrics
- Model serialization using Joblib

---

## 📂 Dataset

**Dataset:** Fraud Detection Dataset

**Source:** https://www.kaggle.com/datasets/kartik2112/fraud-detection

The dataset contains credit card transaction records with customer, merchant, transaction, and geographical information. The objective is to predict whether a transaction is fraudulent.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- XGBoost
- Matplotlib
- Seaborn
- Joblib

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- Removed duplicate records
- Feature engineering from transaction and customer information
- Converted date columns into useful features
- Log transformation of skewed numerical features
- Frequency/encoded categorical variables
- Feature scaling using StandardScaler
- Train-Test Split
- Applied **SMOTE only on the training data** to handle class imbalance and prevent data leakage

---

## 🤖 Machine Learning Models

The following models were trained and evaluated:

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

---

## 📊 Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix
- Classification Report

The performance of all models was compared, and the **best-performing model** was selected for final predictions.

---

## 💾 Saved Models

The trained model and preprocessing objects were saved using **Joblib**.

```
models/
│── xgboost_credit_card_fraud.pkl
│── scaler.pkl
```

---

## 📁 Project Structure

```
Credit-Card-Fraud-Detection/
│
├── models/
│   ├── xgboost_credit_card_fraud.pkl
│   └── scaler.pkl
│
├── Credit_Card_Fraud_Detection.ipynb
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Credit-Card-Fraud-Detection.git
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook Credit_Card_Fraud_Detection.ipynb
```

---

## 📈 Workflow

1. Load and explore the dataset
2. Perform data cleaning and preprocessing
3. Engineer relevant features
4. Handle class imbalance using SMOTE
5. Scale numerical features
6. Train multiple machine learning models
7. Evaluate model performance
8. Save the best-performing model for future inference

---

## 🔮 Future Improvements

- Hyperparameter tuning using GridSearchCV or Optuna
- Real-time fraud detection pipeline
- Deployment using Flask, FastAPI, or Streamlit
- Explainable AI using SHAP or LIME
- Deep learning-based fraud detection models

---

## 👨‍💻 Author

**Ashit Nayak**

B.Tech CSE (AI & ML)

---

## 📜 License

This project is licensed under the **MIT License**.