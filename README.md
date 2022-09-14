# Data Analysis and Visualization of Telco Customer Churn

### This dataset describes customers behavior and profiles of Telco companies that are used to analyze and predict customer retention.
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
|Gender|Categorical| Whether the customer is a male or a female.|
|SeniorCitizen|Categorical| Whether the customer is a senior citizen or not (1, 0). |
|Partner|Categorical| Whether the customer has a partner or not (Yes, No).|
|Dependents|Categorical| Whether the customer has dependents or not (Yes, No).|
|Tenure| Numerical | Number of months the customer has stayed with the company.|
|PhoneService| Categorical | Whether the customer has a phone service or not (Yes, No).|
|MultipleLines| Categorical | Whether the customer has multiple lines or not (Yes, No, No phone service).|
|InternetService| Categorical| Customer’s internet service provider (DSL, Fiber optic, No).|
|OnlineSecurity| Categorical | Whether the customer has online security or not (Yes, No, No internet service).|
|OnlineBackup|Categorical| Data that copied to an “off-site' or cloud backup service (Yes, No). |
|DeviceProtection|Categorical| Protection from loss or theft to damage, malfunction and threats to your personal data (Yes, No). |
|TechSupport|Categorical| Assistance that is provided to a user who requires helps with a technical product or service (Yes, No). |
|StreamingTV|Categorical| Digital distribution of television content, such as TV shows, as streaming media delivered over the Internet (Yes, No). |
|StreamingMovies|Categorical| Consume movies online without downloading files that take up storage space on device (Yes, No). |
|Contract|Categorical| A legally enforceable agreement that creates, defines, and governs mutual rights and obligations among its parties. |
|PaperlessBilling|Categorical| Electronic version of a bill instead of a paper bill (Yes, No). |
|PaymentMethod|Categorical| A way that customers pay for a product or service. |
|MonthlyCharges|Numerical| Rates applicable to all billed electricity consumption included in a normal billing cycle. |
|TotalCharges|Numerical| All sums paid by the Customer and all sums payable under the Contract in respect of goods and Services. |
|**Churn** (Target Feature)| Categorical | Customers that stop using your business during a given time frame (Yes, No).|
