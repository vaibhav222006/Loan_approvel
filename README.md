# Loan_approvel
Built on end to end supervised ML pipeline using KNN ,Logistic Regression and Naive Bayes to predict Loan approval implemented Binary classification along with EDA feature engineering and model evaluation (Precision,Recall,f1) 
# Loan Approval Prediction 🏦

## 📌 Project Overview
This Machine Learning project predicts whether a loan application will be approved or rejected based on an applicant's demographic and financial profile. By automating the eligibility screening process, this model aims to help financial institutions reduce manual effort and minimize default risks.

## 🛠️ Tech Stack
* **Programming Language:** Python
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn
* **Development Environment:** JupyterLab / PyCharm

## 📊 Dataset Features
The dataset contains historical applicant records with the following key attributes:
* **Personal Details:** `Gender`, `Married`, `Dependents`, `Education`, `Self_Employed`
* **Financials:** `ApplicantIncome`, `CoapplicantIncome`, `LoanAmount`, `Loan_Amount_Term`
* **Credit & Property:** `Credit_History`, `Property_Area`
* **Target Variable:** `Loan_Status` (Approved / Not Approved)


## ⚙️ Project Workflow
1. **Data Cleaning & Preprocessing:** Handled missing values using statistical imputation (mean/mode) and treated outliers.
2. **Exploratory Data Analysis (EDA):** Visualized correlations and distributions across income, credit history, and loan approval rates.
3. **Feature Engineering:** Encoded categorical variables into numerical format and scaled features where necessary.
4. **Model Training & Evaluation:** Trained multiple classification algorithms (such as Logistic Regression, Decision Tree, and Random Forest) and compared their performance using accuracy and confusion matrices.

## 📈 Results
* **Best Performing Model:** `Naive bayes`
* **Accuracy Score:** '80.3%`'

## 🚀 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/vaibhav222006/Loan_approvel.git](https://github.com/vaibhav222006/Loan_approvel.git)
