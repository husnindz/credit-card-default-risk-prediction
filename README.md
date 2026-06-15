# 💳 Credit Card Default Risk Prediction (Multi-Model Comparison)

This project focuses on predicting whether a credit card customer will default on their next payment using a comparative multi-model classification approach.

Multiple machine learning algorithms are implemented and evaluated to identify the best-performing model for credit risk prediction. The evaluation includes classification metrics, confusion matrix analysis, and ROC-AUC comparison.

The goal is to support **credit risk assessment** and provide insights into factors associated with customer default behavior.

---

## 📊 Dataset

* Source: UCI Machine Learning Repository – Default of Credit Card Clients Dataset
* Type: Tabular dataset
* Target: `default.payment.next.month`

  * 0 = Non-default
  * 1 = Default

### Characteristics:

* Customer demographic information
* Credit limit information
* Historical repayment records
* Billing statement history
* Previous payment history

### Key Feature Groups:

* **Customer Information**

  * `SEX`
  * `EDUCATION`
  * `MARRIAGE`
  * `AGE`

* **Credit Information**

  * `LIMIT_BAL`

* **Repayment History**

  * `PAY_0` to `PAY_6`

* **Billing Statement History**

  * `BILL_AMT1` to `BILL_AMT6`

* **Previous Payment Records**

  * `PAY_AMT1` to `PAY_AMT6`

---

## ⚙️ Project Workflow

### 1. Data Understanding

* Explore dataset structure, feature types, and summary statistics
* Analyze target class distribution
* Check missing values and data consistency

### 2. Exploratory Data Analysis (EDA)

* Distribution analysis of numerical features
* Correlation analysis using heatmap
* Default behavior visualization across customer and repayment characteristics

### 3. Data Preprocessing

* Feature-target separation
* Train-test split
* Feature scaling where required by the model
* Data preparation for classification modeling

### 4. Modeling (Multi-Model)

Implemented multiple classification models:

* Logistic Regression
* Decision Tree
* Random Forest
* K-Nearest Neighbors (KNN)
* Support Vector Machine (SVM)

### 5. Evaluation

* Classification Report (Precision, Recall, F1-score)
* Confusion Matrix Analysis
* ROC Curve
* ROC-AUC Score Comparison
---

## 🧠 Key Concept

This project uses:

* **Multi-model classification**
* **Credit risk prediction**
* **ROC-AUC based model comparison**
* **Feature importance analysis**
* **Financial risk analytics**

---

## 📈 Results

* Multiple classification models successfully identified customers with default risk.
* Repayment history variables were among the strongest predictors of default behavior.
* Model comparison helped determine the most reliable approach for credit risk prediction.
* Customers with poor repayment records showed significantly higher default probability.

---

## 🛠️ Tech Stack

* Python
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn

---

## 📌 Future Improvements

* Apply hyperparameter tuning using GridSearchCV
* Improve minority class detection performance
* Add explainability using SHAP values
* Implement advanced ensemble methods

---

## 👤 Author

* GitHub: [husnindz](https://github.com/husnindz)
