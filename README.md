# Credit Card Fraud Detection - CS 591 Course Project

**Student**: Muhammad Anwar Raza  
**Roll Number**: MSDS25002  
**Institution**: Information Technology University (ITU) Pakistan  
**Course**: CS 591 - Tools & Techniques for Data Science

---

## 📋 Project Overview

This project implements a complete machine learning pipeline for detecting fraudulent credit card transactions using Python, scikit-learn, and XGBoost.

### Dataset Information

-   **Total Transactions**: 100,000
-   **Features**: 7 (TransactionID, TransactionDate, Amount, MerchantID, TransactionType, Location, IsFraud)
-   **Target**: IsFraud (Binary: 0=Legitimate, 1=Fraud)
-   **Challenge**: Imbalanced dataset

---

## ⚙️ Installation

```bash
# Install required packages
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn xgboost jupyter
```

---

## 🚀 Quick Start

```bash
# Run Jupyter Notebook
jupyter notebook Credit_Card_Fraud_Detection.ipynb
```

---

## 📊 Project Structure

Following the required pattern:

1. **Import Modules** - All necessary libraries
2. **Data Analysis** - Loading, inspection, missing values
3. **Data Transformation** - Encoding, scaling, SMOTE
4. **EDA** - Univariate, bivariate, correlation analysis
5. **Model Training** - 4 models (LR, DT, RF, XGBoost)
6. **Model Evaluation** - Comparison and best model selection
7. **Feature Importance** - Top predictors identification
8. **Final Summary** - Results and recommendations

---

## 📈 Models Evaluated

1. Logistic Regression (Baseline)
2. Decision Tree Classifier
3. Random Forest Classifier
4. XGBoost Classifier

**Metrics**: Accuracy, Precision, Recall, F1-Score, ROC-AUC

---

## 📁 Outputs Generated

-   22+ visualization PNG files
-   Model comparison CSV
-   Feature importance CSV
-   Confusion matrices
-   ROC curves

---

## 🎯 Key Findings

-   SMOTE successfully handles class imbalance
-   Ensemble methods outperform simple models
-   Transaction amount and temporal features are key predictors
-   Geographic patterns correlate with fraud

---

## 🔧 Technologies Used

-   **Python 3.8+**
-   **pandas** - Data manipulation
-   **scikit-learn** - ML models
-   **XGBoost** - Gradient boosting
-   **imbalanced-learn** - SMOTE
-   **matplotlib/seaborn** - Visualization

---

## 📝 Git Commands Used

```bash
git init
git add .
git commit -m "Initial commit: Project setup"
git commit -m "Add: EDA and visualizations"
git commit -m "Add: Model training and evaluation"
git commit -m "Final: Complete project with documentation"
```

---

## 👤 Author

Muhammad Anwar Raza (MSDS25002)  
Information Technology University Pakistan

---

**Last Updated**: December 2024
