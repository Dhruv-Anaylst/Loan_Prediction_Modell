# 🏦 Loan Prediction ML Model

A Machine Learning–based application that predicts whether a loan applicant is **eligible for loan approval** based on demographic, financial, and credit-related attributes.
This project demonstrates an end-to-end ML pipeline including data preprocessing, model training, evaluation, and prediction.

---

## 📌 Project Overview

Financial institutions receive thousands of loan applications daily. Manual evaluation is time-consuming and error-prone.
This project automates the **loan approval decision process** using supervised machine learning algorithms.

The model predicts loan approval status (`Approved / Not Approved`) based on historical applicant data.

---

## 🎯 Objectives

* Automate loan eligibility prediction
* Reduce human bias and processing time
* Improve decision accuracy using ML models
* Demonstrate real-world application of classification algorithms

---

## 🧠 Machine Learning Approach

* **Problem Type:** Binary Classification
* **Target Variable:** Loan_Status
* **Algorithms Used:**

  * Logistic Regression
  * Decision Tree
  * Random Forest
  * Support Vector Machine (optional)

---

## 📂 Dataset Information

The dataset includes the following features:

| Feature           | Description               |
| ----------------- | ------------------------- |
| Gender            | Applicant gender          |
| Married           | Marital status            |
| Dependents        | Number of dependents      |
| Education         | Graduate / Not Graduate   |
| Self_Employed     | Employment status         |
| ApplicantIncome   | Applicant income          |
| CoapplicantIncome | Co-applicant income       |
| LoanAmount        | Loan amount requested     |
| Loan_Amount_Term  | Loan repayment term       |
| Credit_History    | Credit history (0/1)      |
| Property_Area     | Urban / Semiurban / Rural |
| Loan_Status       | Target variable           |

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries & Frameworks:**

  * NumPy
  * Pandas
  * Matplotlib / Seaborn
  * Scikit-learn
* **Development Environment:** Jupyter Notebook / VS Code

---

## 🔄 Project Workflow

1. Data Collection
2. Exploratory Data Analysis (EDA)
3. Data Cleaning & Handling Missing Values
4. Feature Encoding & Scaling
5. Model Training
6. Model Evaluation
7. Prediction on New Data

---

## 📊 Model Evaluation Metrics

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/Loan_Prediction_ML_Model.git
cd Loan_Prediction_ML_Model
```

### 2️⃣ Install Required Libraries

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Notebook / Script

```bash
jupyter notebook
```

or

```bash
python loan_prediction.py
```

---

## 📈 Results

* Achieved high accuracy with ensemble models (Random Forest)
* Credit history and income are the most influential features
* Model generalizes well on unseen data

---

## 🔮 Future Enhancements

* Deploy as a **web application** using Flask/Django
* Add real-time prediction interface
* Hyperparameter tuning using GridSearchCV
* Integrate explainability tools (SHAP / LIME)

---

## 🤝 Contributing

Contributions are welcome.
Feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👤 Author

**Dhruv Agnihotri**
Machine Learning Enthusiast | Data Science Learner

---

If you want, I can also:

* tailor this README for **college major project submission**
* add **screenshots + architecture diagram**
* create a **Flask web app README**
* generate a **project report (PDF / DOC)**
