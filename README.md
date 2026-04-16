# Customer-Churn-Analysis
This project explores why customers leave a telecom service and how we can predict and reduce churn.  I combined Python with Power BI to turn raw data into actionable insights that could help a business improve customer retention.
# Customer Churn Analysis & Prediction

## Overview

This project explores why customers leave a telecom service and how churn can be predicted and reduced.

It combines Python for data analysis and modelling with Power BI for visualisation, turning raw data into insights that could support better customer retention decisions.

---

## What this project looks at

* Why customers churn
* Which customers are most at risk
* What factors influence churn the most
* How churn impacts customer lifetime value (CLTV)

---

## Dataset

The analysis uses the IBM Telco Customer Churn dataset from Kaggle, which contains around 7,000 customers.

It includes:

* Customer demographics
* Services used (internet, streaming, support)
* Contract type and payment method
* Monthly and total charges
* Churn outcome

---

## Data preparation

Before analysis, the data was cleaned and prepared by:

* Handling missing values in Total_Charges
* Converting data types where needed
* Encoding categorical variables for modelling
* Creating features suitable for analysis

---

## Exploratory analysis

Some clear patterns emerged:

* Customers on month-to-month contracts churn more than those on longer contracts
* Churn is highest during the early months of a customer’s lifecycle
* Electronic check users show higher churn levels
* Higher monthly charges are associated with increased churn

---

## Modelling approach

A Logistic Regression model was used to predict churn.

Steps included:

* Splitting the data into training and testing sets
* Training the model on historical data
* Evaluating performance using standard classification metrics

The focus was on understanding which variables contribute most to churn.

---

## Power BI dashboard

A dashboard was built to present the results in a clear and interactive way.

It includes:

* Overall churn rate
* Churn by contract type
* Churn trend over customer tenure
* Churn by payment method
* Customer lifetime value by churn status
* Top drivers of customer churn

---

## Dashboard preview

![Dashboard](Screenshot2026-04-16/203434.png)

---

## Key insights

* Month-to-month contracts show the highest churn risk
* The early stage of the customer lifecycle is the most critical
* Electronic check users contribute the most to churn volume
* Losing high-value customers has a significant impact on revenue

---

## Business implications

Based on the analysis:

* Encouraging longer-term contracts could reduce churn
* Improving onboarding may reduce early-stage churn
* Reviewing payment processes could improve retention
* Targeting high-value customers at risk could protect revenue

---

## Tools used

* Python (Pandas, NumPy, Scikit-learn)
* Power BI
* Jupyter / Google Colab



## Next steps

Potential improvements include:

* Testing more advanced models such as Random Forest or XGBoost
* Deploying the model as a simple application
* Expanding the dashboard with additional interactivity
