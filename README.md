# Customer Churn Prediction

## Project Overview
This project predicts which customers are likely to churn using the **Telco Customer Churn dataset**. It demonstrates the full data science workflow: data cleaning, feature encoding, machine learning modeling, evaluation, and actionable business insights.

## Tools Used
- Python (pandas, numpy, matplotlib, seaborn, scikit-learn)
- Jupyter Notebook

## Data Description
- Dataset contains customer demographics, subscription info, and service usage.
- Target variable: `Churn` (Yes = customer left, No = customer stayed)
- Features include `Contract`, `MonthlyCharges`, `InternetService`, `PaymentMethod`, etc.

## Key Steps
1. **Data Cleaning**: Handle missing values and convert data types
2. **Feature Encoding**: Convert categorical variables to numerical
3. **Train-Test Split**: Split data for modeling
4. **Modeling**: Logistic Regression to predict churn
5. **Evaluation**: Accuracy, confusion matrix, precision, recall
6. **Insights**: Visualize top features affecting churn and provide business recommendations

## Key Insights
- **Month-to-month contracts** and **high monthly charges** increase churn risk
- **Long-term contracts** and certain **payment methods** reduce churn
- Businesses can target **high-risk customers** for retention campaigns

## Repository Contents
- `customer_churn_classification.ipynb` — Full notebook  
- `Telco-Customer-Churn.csv` — Dataset  

## How to Run
1. Clone the repository  
2. Open `customer_churn_classification.ipynb` in **JupyterLab**  
3. Run all cells sequentially to reproduce results and charts
