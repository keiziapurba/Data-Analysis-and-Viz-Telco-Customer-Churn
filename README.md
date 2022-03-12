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
|id| (continous) |Unique identifier for the Customer.|
|Age |Numerical| Age of the Customer.|
|Gender |Categorical|Gender of the Customer|
|Driving_License |Categorical|0 for customer not having DL, 1 for customer having DL.|
|Region_Code |Categorical|Unique code for the region of the customer.|
|Previously_Insured| Categorical | 0 for customer not having vehicle insurance, 1 for customer having vehicle insurance.|
|Vehicle_Age| Categorical | Age of the vehicle.|
|Vehicle_Damage | Categorical | Customer got his/her vehicle damaged in the past. 0 : Customer didn't get his/her vehicle damaged in the past.|
|Annual_Premium| Numerical| The amount customer needs to pay as premium in the year.|
|Policy_Sales_Channel| Categorical | Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.|
|Vintage |Numerical|Number of Days, Customer has been associated with the company.|
|**Response** (Target Feature)| Categorical | 1 for Customer is interested, 0 for Customer is not interested.|
