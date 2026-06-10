# Customer Churn Prediction

## 📌 Project Overview

Customer Churn Prediction is a Machine Learning project that predicts whether a customer is likely to leave a company's service or not. The goal is to help businesses identify at-risk customers and take proactive actions to improve customer retention.

This project uses the IBM Telco Customer Churn dataset and applies Logistic Regression to classify customers into two categories:

- Churn = Yes (Customer will leave)
- Churn = No (Customer will stay)

---

## 🎯 Objective

To build a machine learning model that can predict customer churn based on customer demographics, account information, and service usage patterns.

---

## 📊 Dataset

Dataset: IBM Telco Customer Churn Dataset

Features include:

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Monthly Charges
- Total Charges
- Contract Type
- Payment Method
- Internet Service
- Churn (Target Variable)

Target Variable:

```text
Churn
0 = Customer Stays
1 = Customer Leaves
```

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## 🔍 Project Workflow

### 1. Data Collection
Loaded the Telco Customer Churn dataset.

### 2. Data Preprocessing
- Handled missing values
- Converted TotalCharges to numeric format
- Converted target variable into binary values
- Selected important features

### 3. Exploratory Data Analysis (EDA)
- Analyzed customer behavior
- Studied churn distribution
- Identified important features affecting churn

### 4. Model Building
Implemented Logistic Regression for customer churn classification.

### 5. Model Evaluation
Evaluated model performance using:
- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 🤖 Machine Learning Model

Algorithm Used:

- Logistic Regression

Reason:
- Simple and interpretable classification algorithm
- Effective baseline model for binary classification problems

---

## 📈 Results

The model successfully predicts customer churn based on customer account and usage information.

Evaluation Metrics:
- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 📂 Project Structure

```text
Customer-Churn-Prediction/
│
├── churn_prediction.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/customer-churn-prediction.git
```

2. Install dependencies

```bash
pip install pandas numpy matplotlib scikit-learn
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Run all cells in:

```text
churn_prediction.ipynb
```

---

## 💼 Business Impact

Customer churn prediction helps companies:

- Improve customer retention
- Reduce revenue loss
- Identify high-risk customers
- Design targeted marketing campaigns
- Increase customer satisfaction

---

## 🔮 Future Improvements

- Random Forest Classifier
- XGBoost Classifier
- Hyperparameter Tuning
- Feature Engineering
- Streamlit Web Application Deployment

---

## 👨‍💻 Author

Prabhash Verma

M.Tech (Data Science)

Machine Learning | Data Science | AI Enthusiast
