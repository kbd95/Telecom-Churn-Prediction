# Churn Prediction Using Machine Learning
Telecom need to predict customers at high risk of churn. In this repositary we will have three main goals - 

1. Analyse customer-level data of a leading telecom firm.
2. Build predictive models to identify customers at high risk of churn
3. Identify the main indicators of churn.

Churn prediction is common use case in machine learning domain. If you are not familiar with the term, churn means "leaving the company". It is very critical for business to have an idea about why and when customers are likely to churn. Having a robust and accurate churn prediction model helps businesses to take actions to prevent customers from leaving the company.

In this project, Telco Customer Churn Dataset which is available at Kaggle is used.

There are 20 featuures (independent variables) and 1 target (dependent) variable for 7043 customers. Target variable indicates if a customer has has left the company (i.e. churn=yes) within the last month. Since the target variable has two states (yes/no or 1/0), this is a binary classification problem.

### Attributes Information
### Prediction column:
#### Churn:
Whether the customer churned or not (Yes or No)

### Two numerical columns:
#### MonthlyCharges:
The amount charged to the customer monthly
#### TotalCharges:
The total amount charged to the customer
### Eighteen categorical columns:
1. CustomerID: Customer ID unique for each customer
2. gender: Whether the customer is a male or a female
3. SeniorCitizen: Whether the customer is a senior citizen or not (1, 0)
4. Partner: Whether the customer has a partner or not (Yes, No)
5. Dependents: Whether the customer has dependents or not (Yes, No)
6. Tenure: Number of months the customer has stayed with the company
7. PhoneService: Whether the customer has a phone service or not (Yes, No)
8. MultipleLines: Whether the customer has multiple lines or not (Yes, No, No phone service)
9. InternetService: Customer’s internet service provider (DSL, Fiber optic, No)
10. OnlineSecurity: Whether the customer has online security or not (Yes, No, No internet service)
11. OnlineBackup: Whether the customer has an online backup or not (Yes, No, No internet service)
12. DeviceProtection: Whether the customer has device protection or not (Yes, No, No internet service)
13. TechSupport: Whether the customer has tech support or not (Yes, No, No internet service)
14. StreamingTV: Whether the customer has streaming TV or not (Yes, No, No internet service)
15. StreamingMovies: Whether the customer has streaming movies or not (Yes, No, No internet service)
16. Contract: The contract term of the customer (Month-to-month, One year, Two years)
17. PaperlessBilling: Whether the customer has paperless billing or not (Yes, No)
18. PaymentMethod: The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))

### The project is structured as follows:
#### Data cleaning
#### Exploratory Data Analysis
#### Data Preprocessing
#### Encoding
#### Feature Selection
#### Oversampling Technique
#### Model Creation and Evaluation
#### Improving the Model







