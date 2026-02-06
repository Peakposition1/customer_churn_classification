# Customer Churn Prediction

## Project Overview
This project predicts which customers are likely to churn using the **Telco Customer Churn dataset**. It demonstrates a complete data science workflow, including:

- Data cleaning and preprocessing  
- Feature encoding  
- Train-test split  
- Logistic Regression modeling  
- Model evaluation using accuracy, confusion matrix, precision, and recall  
- Business insights and visualization of top churn predictors

The goal is to provide actionable insights for businesses to reduce customer churn and retain high-risk customers.

---

## Tools Used
- Python (pandas, numpy, matplotlib, seaborn, scikit-learn)  
- Jupyter Notebook  

---

## Data Description
- **Dataset:** Telco Customer Churn  
- **Target variable:** `Churn` (Yes = customer left, No = customer stayed)  
- **Key features:** Contract type, MonthlyCharges, InternetService, PaymentMethod, tenure, and more  

---

## Workflow
1. **Data Loading** – Load CSV data into pandas and inspect basic info  
2. **Data Cleaning** – Handle missing values and convert data types  
3. **Feature Encoding** – Convert categorical variables to numerical format  
4. **Train-Test Split** – Split dataset into training and testing sets  
5. **Modeling** – Logistic Regression to predict customer churn  
6. **Evaluation** – Assess model using accuracy, confusion matrix, precision, and recall  
7. **Insights** – Visualize top features influencing churn and provide business recommendations  

---

## Key Insights
- Customers on **month-to-month contracts** with **high monthly charges** are more likely to churn  
- Long-term contracts and certain **payment methods** reduce churn  
- Businesses can **target high-risk customers** for retention campaigns  

---

## Repository Contents
- `customer_churn_classification.ipynb` — Full notebook with all analysis, modeling, and plots  
- `Telco-Customer-Churn.csv` — Dataset used for the project  

---

## How to Run
1. Clone the repository  
2. Open `customer_churn_classification.ipynb` in **JupyterLab** or **VS Code**  
3. Run all cells sequentially to reproduce results and charts  

---

## Optional Enhancements
- Add screenshots of important plots to the README for better presentation  
- Explore more advanced models like Random Forest or XGBoost  
- Perform additional feature engineering to improve model performance
