# Data-Viz-Telco-Customer-Churn
This dataset describes customers behavior and profiles of Telco companies that are used to analyze and predict customer retention.
---

### **Data Description**
The data set includes information about:
- Customers who left within the last month – the column is called Churn
- Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
- Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
- Demographic info about customers – gender, age range, and if they have partners and dependents
- Total data points: 7043 and total columns (features): 21. (https://www.kaggle.com/blastchar/telco-customer-churn)


| Feature Name | Type | Description |
|----|----|----|
|CustomerID| (continous) |Unique identifier for the Customer.|
|Gender|Numerical| Whether the customer is a male or a female.|
|SeniorCitizen|Categorical| Whether the customer is a senior citizen or not (1, 0). |
|Partner|Categorical| Whether the customer has a partner or not (Yes, No).|
|Dependents|Categorical| Whether the customer has dependents or not (Yes, No).|
|Tenure| Categorical | Number of months the customer has stayed with the company.|
|PhoneService| Categorical | Whether the customer has a phone service or not (Yes, No).|
|MultipleLines| Categorical | Whether the customer has multiple lines or not (Yes, No, No phone service).|
|InternetService| Numerical| Customer’s internet service provider (DSL, Fiber optic, No).|
|OnlineSecurity| Categorical | Whether the customer has online security or not (Yes, No, No internet service).|
|OnlineBackup|Numerical|Number of Days, Customer has been associated with the company.|
|DeviceProtection|Numerical|Number of Days, Customer has been associated with the company.|
|TechSupport|Numerical|Number of Days, Customer has been associated with the company.|
|StreamingTV|Numerical|Number of Days, Customer has been associated with the company.|
|StreamingMovies|Numerical|Number of Days, Customer has been associated with the company.|
|Contract|Numerical|Number of Days, Customer has been associated with the company.|
|PaperlessBilling|Numerical|Number of Days, Customer has been associated with the company.|
|PaymentMethod|Numerical|Number of Days, Customer has been associated with the company.|
|MonthlyCharges|Numerical|Number of Days, Customer has been associated with the company.|
|TotalCharges|Numerical|Number of Days, Customer has been associated with the company.|
|**Churn** (Target Feature)| Categorical | 1 for Customer is interested, 0 for Customer is not interested.|
