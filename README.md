# 💳 Credit Card Fraud Detection
### CS591 — Tools & Techniques for Data Science | ITU Lahore | MS Data Science

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![XGBoost](https://img.shields.io/badge/XGBoost-Gradient%20Boosting-green.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)

---

## 🎯 Project Overview

A complete end-to-end machine learning pipeline for detecting fraudulent 
credit card transactions using Python and scikit-learn. This project tackles 
one of the most critical challenges in financial data science — identifying 
fraud in a highly imbalanced dataset — using advanced resampling techniques 
and ensemble methods.

---

## 📊 Dataset

| Property | Value |
|----------|-------|
| Total Transactions | 100,000 |
| Features | 7 |
| Target Variable | IsFraud (Binary: 0=Legitimate, 1=Fraud) |
| Key Challenge | Severely imbalanced classes |
| Solution | SMOTE oversampling |

**Features:** TransactionID · TransactionDate · Amount · 
MerchantID · TransactionType · Location · IsFraud

---

## 🔬 Models Evaluated

| Model | Type |
|-------|------|
| Logistic Regression | Baseline Linear Model |
| Decision Tree | Tree-based Model |
| Random Forest | Ensemble (Bagging) |
| XGBoost | Ensemble (Boosting) ⭐ Best |

---

## 📈 Key Results

- ✅ **XGBoost** achieved the highest performance across all metrics
- ✅ **SMOTE** successfully balanced severely imbalanced fraud/non-fraud classes
- ✅ Ensemble methods significantly outperformed simple linear baseline
- ✅ Transaction amount and temporal features identified as top fraud predictors
- ✅ Geographic patterns showed strong correlation with fraudulent activity
- ✅ 22+ visualizations generated including ROC curves, confusion matrices, 
     and feature importance plots

---

## 📁 Repository Structure
```
CREDIT-CARD-FRAUD-DETECTION/
│
├── Credit_Card_Fraud_Detection.ipynb  # Main notebook — full pipeline
├── MSDS25002_Course_Project.pdf       # Complete project report
├── requirements.txt                   # Dependencies
├── Content/                           # Supporting files
└── .gitignore
```

---

## ⚙️ Installation & Setup
```bash
# Clone the repository
git clone https://github.com/AnwarRazaa/CREDIT-CARD-FRAUD-DETECTION.git
cd CREDIT-CARD-FRAUD-DETECTION

# Install required packages
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn xgboost jupyter
```

---

## 🚀 How to Run
```bash
# Launch Jupyter Notebook
jupyter notebook Credit_Card_Fraud_Detection.ipynb
```

---

## 🔄 Project Pipeline
```
1. Import Libraries & Load Data
        ↓
2. Exploratory Data Analysis (EDA)
   └── Univariate · Bivariate · Correlation Analysis
        ↓
3. Data Preprocessing & Transformation
   └── Encoding · Scaling · SMOTE Balancing
        ↓
4. Model Training
   └── LR · Decision Tree · Random Forest · XGBoost
        ↓
5. Model Evaluation & Comparison
   └── Accuracy · Precision · Recall · F1 · ROC-AUC
        ↓
6. Feature Importance Analysis
        ↓
7. Final Summary & Recommendations
```

---

## 📦 Output Files Generated

- 22+ visualization PNG files
- Model comparison CSV
- Feature importance CSV
- Confusion matrices for all models
- ROC curves for all models

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3.8+ | Core language |
| Pandas | Data manipulation |
| NumPy | Numerical computing |
| Scikit-learn | ML models & preprocessing |
| XGBoost | Gradient boosting |
| Imbalanced-learn | SMOTE resampling |
| Matplotlib / Seaborn | Visualization |
| Jupyter Notebook | Development environment |

---

## 📚 Evaluation Metrics

- **Accuracy** — Overall correctness
- **Precision** — How many flagged transactions were actually fraud
- **Recall** — How many actual frauds were caught
- **F1-Score** — Harmonic mean of Precision and Recall
- **ROC-AUC** — Overall discriminative ability of the model

---

## 👤 Author

**Muhammad Anwar Raza**
MS Data Science — Information Technology University (ITU), Lahore
Roll No: MSDS25002
Course: CS591 — Tools & Techniques for Data Science

[![GitHub](https://img.shields.io/badge/GitHub-AnwarRazaa-black.svg)](https://github.com/AnwarRazaa)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Muhammad%20Anwar%20Raza-blue.svg)](https://www.linkedin.com/in/muhammad-anwar-raza1/)

---

*Last Updated: 2024 | Information Technology University, Lahore, Pakistan*
