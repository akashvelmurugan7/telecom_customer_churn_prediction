# Telecom Customer Churn Prediction

## Project Overview

This project aims to predict customer churn in the telecom industry using machine learning techniques. By analyzing customer data, we can identify patterns and factors contributing to customer attrition, enabling proactive retention strategies.

## Dataset

File: telecom_data.xlsx

CustomerID – Unique identifier for each customer

Gender – Customer’s gender (Male/Female)

SeniorCitizen – Whether the customer is a senior citizen (1 = Yes, 0 = No)

Partner – Whether the customer has a partner (Yes/No)

Dependents – Whether the customer has dependents (Yes/No)

Tenure – Number of months the customer has stayed with the company

PhoneService – Whether the customer has phone service (Yes/No)

MultipleLines – Whether the customer has multiple lines (Yes/No/No phone service)

InternetService – Type of internet service (DSL/Fiber optic/None)

OnlineSecurity – Whether the customer has online security service (Yes/No/No internet service)

OnlineBackup – Whether the customer has online backup service (Yes/No/No internet service)

DeviceProtection – Whether the customer has device protection (Yes/No/No internet service)

TechSupport – Whether the customer has tech support (Yes/No/No internet service)

StreamingTV – Whether the customer has streaming TV (Yes/No/No internet service)

StreamingMovies – Whether the customer has streaming movies (Yes/No/No internet service)

Contract – Type of contract (Month-to-month/One year/Two year)

PaperlessBilling – Whether the customer has paperless billing (Yes/No)

PaymentMethod – Method of payment (Electronic check/Mailed check/Bank transfer/Credit card)

MonthlyCharges – Monthly amount charged to the customer

TotalCharges – Total amount charged to the customer

Churn – Whether the customer has churned (Yes/No) (Target Variable)

## Project Structure

|-- telecom_customer_churn_prediction.ipynb   # Jupyter Notebook with analysis and model building
|-- telecom_data.xlsx                         # Dataset used for training the model
|-- customer_churn_segments                   # Saved excel document after prediction
|-- README.md                                 # Project documentation

## Methodology

* Data Preprocessing

* Handling missing values

* Encoding categorical variables

* Feature scaling

* Exploratory Data Analysis (EDA)

* Visualizing customer trends

* Understanding correlations

## Model Development

* Tested multiple machine learning models (e.g., Logistic Regression, Random Forest, XGBoost)

* Performance evaluation using accuracy, precision, recall, and F1-score

## Model Evaluation & Insights

* Identified key factors influencing churn

* Suggested business strategies for retention

## Technologies Used

* Python

* Pandas, NumPy

* Scikit-learn

* Matplotlib, Seaborn

* Jupyter Notebook

## How to Use

* Clone the repository:

  git clone  https://github.com/akashvelmurugan7/telecom_customer_churn_prediction.git

* Install dependencies

* Run the Jupyter Notebook to explore the analysis and predictions.

## Results & Insights

* The model achieved an roc-auc score of 84.09% (update with actual result).

* Top churn indicators: ( tenure, partner, InternetService,	TechSupport, Contract, PaymentMethod,	MonthlyCharges, TotalCharges)

## Retention Strategies Based on Findings

### Offer Incentives for Long-Term Contracts

Customers on month-to-month contracts tend to churn more. Offering discounts or exclusive benefits for 1-year or 2-year contracts can improve retention.

### Improve Customer Support & Technical Assistance

Customers who lack tech support or device protection are more likely to churn. Providing proactive customer service, faster issue resolution, and AI-driven chatbots can help retain them.

### Personalized Discount Plans for High Churn Risk Customers

Customers with higher monthly charges often leave for cheaper alternatives. Using customer segmentation, offer loyalty discounts or bundled services to reduce their likelihood of switching.

### Enhance Service Quality for Fiber Optic & Streaming Users

Customers with Fiber Optic Internet and Streaming Services expect high performance. Ensuring low downtime, better bandwidth, and exclusive streaming content can reduce churn.

### Introduce Loyalty & Rewards Programs

Reward long-term customers with discounts, exclusive content, priority customer service, or referral bonuses to increase retention.

### Optimize Payment & Billing Systems

Customers with electronic check payments or billing issues often churn. Implement flexible payment options, automatic reminders, and transparent billing policies.

### Target Senior Citizens & Family Users

Senior citizens and customers with dependents are often more loyal. Offering senior discounts or family plans can encourage long-term engagement.

### Data-Driven Customer Engagement

Use predictive analytics to identify customers at high churn risk and proactively engage them via personalized offers, service upgrades, or retention campaigns.

## Future Enhancements

* Implement deep learning techniques

* Improve feature engineering

* Deploy the model using Flask or FastAPI

## Author

Akash Velmurugan

## License

This project is licensed under the MIT License.
