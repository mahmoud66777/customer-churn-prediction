# customer-churn-prediction
Predicting customer churn using Logistic Regression, SVM, and KNN — with EDA and preprocessing.
# 📉 Customer Churn Prediction Project

This project predicts whether a customer is likely to churn based on demographic and service usage features using various ML models.

## 📊 Dataset
- Source: [Kaggle Dataset – Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Format: CSV
- Target column: `Churn` (Yes/No)

## 🔍 Exploratory Data Analysis (EDA)
- Count plots of gender and churn
- Pie chart for contract types
- Histograms for numerical distributions
- Correlation analysis and feature selection

## 🧼 Preprocessing
- Encoding categorical features (gender, contract, internet service, etc.)
- Scaling numerical features using `StandardScaler`
- Handled class imbalance and removed redundant features

## 🧠 Models Used
| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | ~80%     |
| SVM                 | ~78%     |
| KNN (k=5)           | ~77%     |

Each model was:
- Trained on 80% of the data
- Evaluated using accuracy and confusion matrix

## 🧠 Skills Demonstrated
- EDA & visualization with Seaborn/Matplotlib
- Label encoding
- Feature scaling
- Model training and evaluation

---

🔗 **Kaggle notebook:**  
[Customer Churn – Logistic Regression, SVM, KNN](https://www.kaggle.com/code/mahmoudehab6677/customer-churn-logisticregression-svm-knn)
