# Telco Customer Churn Prediction
This project uses Machine Learning to predict which customers are likely to leave a telecommunications provider. By identifying at-risk customers, businesses can take proactive steps to improve retention.

##  Project Overview
The goal of this project is to build a binary classification model that predicts "Churn" (Yes/No). The project covers the entire data science pipeline, from data cleaning and preprocessing to model evaluation.

## Tech Skill :
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn ,Plotly 
* **Model:** Random Forest Classifier , Logistic Regression , XGBoost

##  Data Preprocessing
To prepare the data for the model, the following steps were taken:
1. **Data Cleaning:** Handled missing values in `TotalCharges` and converted data types.
2. **Label Encoding:** Converted categorical text data (Gender, Partner, etc.) into numerical format.
3. **Feature Scaling (Standardization):** Applied `StandardScaler` to normalize features like `MonthlyCharges` and `Tenure` to ensure the model isn't biased by large numerical values.

## Best Model Performance
IN **XGBoost** algorithm, which achieved the following results on the test set:

* **Accuracy:**  0.83 
* **ROC-AUC:** 86.02%

##  Key Insights
Based on the **Feature Importance** analysis, the top 3 drivers of churn were:
1. **Contract Type:** Month-to-month contracts have the highest churn risk.
2. **Tenure:** Newer customers are more likely to leave.
3. **Total Charges:** High-cost customers are more sensitive to price.



##  How to Run
1. Clone this repo: https://github.com/BhupeshRajput029/Churn-analysis-ml
2. Install requirements: `pip install -r requirements.txt`
3. Run the notebook: `jupyter notebook`
