# Customer Churn Analysis & Prediction

## Project Overview
This project analyzes customer churn data to identify factors that influence customer attrition and to build predictive models that support business decision-making. The workflow includes data cleaning, preprocessing, model development, evaluation, and interpretation of results into actionable business insights.

The objective is to understand churn drivers and provide recommendations that help improve customer retention.

---

## Dataset Information
- Dataset: Telco-Churn-Customer-Synthetic
- Source: Public dataset (Kaggle / open data)
- Type: Structured tabular data containing customer demographics, service usage, billing information, and churn status.

---

## Tools and Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Google Colab
- Microsoft Excel

---

## Project Workflow
1. Data loading and exploration  
2. Data cleaning and preprocessing  
3. Handling missing values  
4. Encoding categorical variables  
5. Train-test split  
6. Model training:
   - Logistic Regression
   - Random Forest Classifier  
7. Model evaluation using classification metrics and ROC-AUC  
8. Feature importance analysis  
9. Business insight generation and recommendations  

---

## Visualizations

### Churn Distribution
![Churn Distribution](images/churn-distribution.png)

### Feature Importance (Random Forest)
![Feature Importance](images/feature-importance.png)

---

## Model Results
Two models were implemented and compared:

- Logistic Regression  
- Random Forest Classifier  

Random Forest showed stronger performance in identifying key features related to customer churn.

---

## Business Insights
Key factors influencing churn include:

- Tenure (length of customer relationship)
- Total Charges
- Contract type
- Internet Service and Technical Support

Key findings:
- Customers with monthly contracts show higher churn risk.
- Customers with shorter tenure are more likely to churn.
- Poor technical support is associated with higher churn probability.

---

## Business Recommendations
- Develop loyalty programs for new customers.
- Improve technical support quality and responsiveness.
- Encourage customers with monthly contracts to switch to longer-term plans through incentives.

---

## Run the Project
The notebook can be opened and executed directly in Google Colab:

[Open in Google Colab](https://colab.research.google.com/drive/1ztFrO_oTZCSzvHUrn1MI0P7nP34kyr9w#scrollTo=arybfacega6Z)

---

## Repository Structure

<pre>
customer-churn-analysis/
│
├── Telco_Customer_Churn.ipynb
├── README.md
├── Telco-Churn-Customer-Synthetic.xlsx
└── images/
    ├── churn-distribution.png
    └── feature-importance.png
</pre>



## Author
ERIAN HADI

