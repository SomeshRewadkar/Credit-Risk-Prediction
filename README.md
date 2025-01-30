# Credit Risk Prediction Model

---

## Project Background

XYZ Company operates in the lending industry, where making accurate decisions about loan approvals is crucial. When a lending company receives a loan application, it must assess the applicant's profile to determine if they are likely to repay the loan. Approving a loan to an applicant who is unlikely to repay it can lead to significant financial losses for the company. Conversely, rejecting a loan application from an applicant who is likely to repay it results in missed business opportunities. Therefore, identifying and minimizing bad-risk loans is essential to mitigate financial losses and maintain business profitability.

---

## Objectives

This project aims to minimize the approval of bad-risk loans by:
1. Identifying patterns that indicate a high likelihood of loan default (bad risk).
2. Developing predictive models to assess the credit risk of loan applicants.

---

## Methodology

### 1. Data Preparation
- **Source:** Data obtained from the ID/X Partners Data Scientist Virtual Internship Program at Rakamin Academy.
- **Actions:** Cleaning and preparing the data for analysis, ensuring data quality and consistency.

### 2. Exploratory Data Analysis (EDA)
- **Purpose:** Discover patterns, spot anomalies, and gain a deeper understanding of the data's characteristics.
- **Key Insights:** Identified factors such as last payment month, last payment amount, principal amount received, recovery value, and last payment year as significant predictors of loan repayment likelihood.

### 3. Machine Learning
- **Approach:** Building predictive models to assess credit risk.
- **Algorithms Tested:** Eight different algorithms were evaluated, including Random Forest, XGBoost, LightGBM, and CatBoost.
- **Best Model:** Random Forest achieved the highest accuracy of **99%**, making it the most effective model for credit risk prediction.

---

## Tools

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Model Deployment:** Flask (optional, if applicable)

---

## Results

- The **Random Forest model** achieved an accuracy of **99%**, enabling precise and reliable decision-making.
- Key factors influencing loan repayment likelihood were identified:
  - Last payment month
  - Last payment amount
  - Principal amount received
  - Recovery value
  - Last payment year
- The model significantly reduces the likelihood of granting loans to bad-risk applicants, minimizing financial losses for the company.

---

## Future Work

1. **Model Improvement:** Further hyperparameter tuning and exploring advanced algorithms (e.g., Neural Networks) to improve performance.
2. **Extended Analysis:** Include additional data sources and variables for a more comprehensive understanding of credit risk factors.
3. **Deployment:** Integrate the model into a real-time decision-making system for loan approvals.

---

## Repository Contents

- **Scripts:** Python scripts for data preprocessing, cleaning, and model training.
- **Notebooks:** Jupyter notebooks for exploratory data analysis (EDA) and model building.
- **Report Deck:** Detailed reports on findings, including insights and model performance metrics.
- **Visualizations:** Charts and graphs illustrating key trends and model performance.

---

## How to Run the Code

1. Clone this repository:
   ```bash
   git clone https://github.com/SomeshRewadkar/credit-risk-prediction.git
