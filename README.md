# Credit-Card-Fraud-Detection-
# 💳 Credit Card Fraud Detection

A machine learning project for detecting fraudulent credit card transactions using transaction data. The project includes data preprocessing, visualization, feature scaling, and model evaluation using multiple ML algorithms.

---

## 📌 Overview

- Built a fraud detection model using the Credit Card Fraud Detection dataset
- Preprocessed features like `Time` and `Amount` using `RobustScaler`
- Performed data visualization with Seaborn and Matplotlib
- Trained and evaluated multiple models for fraud classification

---

## 🧰 Technologies & Libraries

- Python
- pandas, numpy
- seaborn, matplotlib
- scikit-learn (for ML models and evaluation)
- RobustScaler (for feature normalization)

---

## 📊 Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- Contains 284,807 transactions
- Features `V1` to `V28` are anonymized via PCA
- The `Class` column indicates fraud (1) or genuine (0)

---

## 📈 Workflow

1. Load and explore dataset
2. Feature scaling using `RobustScaler`
3. Visualize relationships between amount and fraud
4. Train-test split for model validation
5. Evaluate models using confusion matrix and classification report

---

## 📝 How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/credit-card-fraud.git
cd credit-card-fraud
