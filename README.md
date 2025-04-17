# 🏦 Bank Customer Churn Prediction

This machine learning project predicts whether a bank customer will churn (leave the bank) based on various features like age, balance, tenure, and activity status.

## 📁 Files Included

- `Bank Customer Churn Prediction.ipynb` – Full analysis & modeling notebook
- `churn.csv` – Raw dataset used for training
- `README.md` – Project overview

## 📊 Dataset Overview

The dataset contains 10,000 records with 14 columns, including:

- `CreditScore`
- `Geography`
- `Gender`
- `Age`
- `Tenure`
- `Balance`
- `NumOfProducts`
- `IsActiveMember`
- `EstimatedSalary`
- `Exited` (Target column)

## 🧠 ML Models Used

- Decision Tree Classifier (with GridSearchCV)
- Random Forest Classifier (with GridSearchCV)

## ✅ Performance

| Metric              | Decision Tree | Random Forest |
|---------------------|---------------|---------------|
| Accuracy            | 86.1%         | 86.8%         |
| Recall (Churn)      | 40% approx    | 41% approx    |
| F1 Score (Churn)    | 54% approx    | 55% approx    |

## 🔍 Key Insights

- **Churn Rate**: Only **20.4%** of customers churned, indicating class imbalance that affects model sensitivity.
- **Age Factor**: Customers aged **40–60** are more likely to churn.
- **Geography Impact**: **Germany-based** customers show a notably higher churn rate.
- **Tenure Influence**: Customers with **1–2 years** of tenure are more likely to leave.
- **Balance Correlation**: High account balances are common among churned customers.
- **Activity Level**: **Inactive members** are significantly more prone to churn.
- **Product Count**: Customers with **3 or more products** are likelier to churn — suggesting complexity or dissatisfaction.

---

## 📌 Conclusion

This project successfully identified the top factors contributing to customer churn using exploratory data analysis and classification modeling.  
- Both Decision Tree and Random Forest classifiers performed well, but **Random Forest** slightly outperformed with better **recall and F1-score for churn prediction**.
- These insights can help banks focus on **early tenure**, **high-value**, and **inactive** customers to reduce churn through personalized engagement and retention strategies.

## 🔧 Tools Used

- Python
- Pandas, NumPy, Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## 📬 Contact

Feel free to connect or collaborate:

- GitHub: Swapnil718 https://github.com/Swapnil718
- LinkedIn: Swapnil Yadav https://www.linkedin.com/in/swapnil-yadav-dataanalyst/

