# IBM-EMPLOYEE-DATA-ANALYSIS
This project aims to analyze IBM HR data to understand factors contributing to employee attrition and develop predictive models to identify employees at risk of leaving the company.

About the Dataset
The dataset used in this analysis is the IBM HR Analytics Attrition Dataset. It contains various attributes of employees such as age, education, job role, and whether they have left the company (attrition).

Installation and Execution
Clone the Repository:

'''git clone https://github.com/your-username/ibm-hr-data-analysis.git'''


Install Dependencies:

'''pip install -r requirements.txt'''

Run the Code:

'''python ibm_hr_data_analysis.py'''

Summary of Findings
Exploratory data analysis (EDA) revealed insights into the distribution and relationships between various employee attributes.
Data preprocessing steps included handling missing values, encoding categorical variables, and feature scaling.
Models such as Logistic Regression, Random Forest, XGBoost, and Support Vector Machine were trained and evaluated for predicting employee attrition.
XGBoost and Random Forest models demonstrated the highest performance in distinguishing between positive and negative instances of attrition, with higher AUC scores.
