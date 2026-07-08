# credit-wise-loan
# 💳 CreditWise Loan Approval Prediction

CreditWise Loan Approval Prediction is a Machine Learning project that predicts whether a loan application is likely to be approved based on applicant information. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and model evaluation using multiple classification algorithms.

---

## 📌 Project Overview

The objective of this project is to build a predictive model that helps determine loan approval decisions based on applicant details such as income, credit score, employment status, loan amount, and other financial attributes.

The project follows a complete machine learning workflow from data cleaning to model evaluation and compares different classification algorithms to identify the best-performing model.

---

## 🚀 Features

- Data Cleaning and Preprocessing
- Missing Value Handling
- Exploratory Data Analysis (EDA)
- Feature Encoding
- Feature Scaling
- Feature Engineering
- Multiple Machine Learning Models
- Model Performance Comparison
- Loan Approval Prediction

---

## 📊 Dataset Features

The dataset contains applicant information such as:

- Applicant Income
- Co-applicant Income
- Credit Score
- Loan Amount
- Loan Term
- Debt-to-Income Ratio
- Education Level
- Employment Status
- Employer Category
- Marital Status
- Gender
- Property Area
- Loan Purpose
- Loan Approval Status (Target)

---

## 🛠 Data Preprocessing

The following preprocessing techniques were applied:

- Handling missing values using SimpleImputer
- Mean imputation for numerical features
- Most frequent imputation for categorical features
- Label Encoding
- One-Hot Encoding
- Removing unnecessary columns
- Feature Scaling using StandardScaler

---

## 📈 Exploratory Data Analysis (EDA)

The project includes visualizations such as:

- Class Distribution
- Income Distribution
- Credit Score Analysis
- Loan Approval Distribution
- Boxplots for Outlier Detection
- Correlation Heatmap
- Feature Relationship Analysis

---

## ⚙️ Machine Learning Models

The following classification models were trained and evaluated:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes

### 🏆 Best Performing Model

**Gaussian Naive Bayes**

Selected based on model precision after evaluation.

---

## 🔧 Feature Engineering

Additional features were created to improve model performance, including:

- Squared Debt-to-Income Ratio
- Squared Credit Score

---

## 📚 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Project Structure

```
CreditWise-Loan/
│
├── credit_wise.ipynb
├── loan_approval_data.csv
├── README.md
├── requirements.txt
└── LICENSE
```

---

## 🔄 Project Workflow

```
Loan Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Missing Value Handling
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Encoding
      │
      ▼
Feature Scaling
      │
      ▼
Feature Engineering
      │
      ▼
Train-Test Split
      │
      ▼
Model Training
      │
      ▼
Logistic Regression
KNN
Gaussian Naive Bayes
      │
      ▼
Model Evaluation
      │
      ▼
Loan Approval Prediction
```

---

## 📈 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Cross-validation
- Model deployment using Flask or Streamlit
- Integration with real-time loan application forms
- Support for explainable AI (SHAP/LIME)

---

## 📜 License

This project is licensed under the MIT License.

---

## 👩‍💻 Author

**Aishwarya Bandgar**

Final Year B.Tech Student | Data Science | Machine Learning | AI Enthusiast

⭐ If you found this project helpful, please consider starring the repository.
