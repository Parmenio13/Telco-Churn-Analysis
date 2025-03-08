## **David Emilio Vega Bonza, david.vegabonza@colorado.edu**

### **CC 80215162, Bogotá. Colombia**

## CSCA Supervised Learning Final Project
# **Telecomunications Company Customer Churn Analysis**

## **1. This Notebook Project Topic:**

Customer churn analysis in telecom companies focuses on identifying customers who are likely to leave the service provider. This project involves analyzing customer data to predict churn and understand the factors contributing to it.

In this project we will review how "Customer churn analysis" is crucial for telecom companies for several reasons:

1. **Revenue Loss Prevention**: Losing customers directly impacts a company's bottom line. By identifying patterns that lead to customer churn, telecom companies can proactively address issues and reduce the likelihood of losing subscribers.

2. **Customer Retention**: Retaining existing customers is often more cost-effective than acquiring new ones. Through churn analysis, telecom companies can implement targeted retention strategies, such as personalized offers, discounts, and loyalty programs.

3. **Competitive Edge**: The telecom industry is highly competitive. Understanding why customers leave can help companies improve their services and offerings, staying ahead of competitors and retaining their market share.

4. **Customer Satisfaction**: Churn analysis provides insights into customer behavior and preferences. This information can be used to enhance customer experiences, addressing pain points and improving overall satisfaction.

5. **Marketing Optimization**: By knowing which customers are at risk of leaving, telecom companies can focus their marketing efforts more effectively. Targeted campaigns aimed at retaining high-value customers or re-engaging those at risk of churning can lead to better returns on marketing investments.

6. **Product Development**: Insights gained from churn analysis can inform product and service development. By understanding what factors contribute to customer dissatisfaction, companies can make data-driven decisions to improve their offerings.

The main **goal is to develop predictive models that can accurately identify potential churners** and **provide insights to help telecom companies** retain their customers for a much longer time.

In summary, customer churn analysis helps telecom companies maintain their customer base, optimize marketing efforts, enhance customer satisfaction, and ultimately ensure business growth and stability.

---

## **2. Data:**

### **Data Source Description:**

#### Context Data Source:
- **Dataset Name:** Telco Customer Churn (focused customer retention programs)
- **Url:** https://www.kaggle.com/datasets/blastchar/telco-customer-churn
- **Motivation:** "Predict behavior to retain customers. You can analyze all relevant customer data and develop focused customer retention programs." [IBM Sample Data Sets]

#### Content:
Each row represents a customer, each column contains customer’s attributes described on the column Metadata.

**The data set includes information about:**

- Customers who left within the last month – the column is called Churn
- Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
- Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
- Demographic info about customers – gender, age range, and if they have partners and dependents

#### Dataset variables detail:

1. **customerID:** Customer ID

2. **gender:** Whether the customer is a male or a female

3. **SeniorCitizen:** Whether the customer is a senior citizen or not (1, 0)

4. **Partner:** Whether the customer has a partner or not (Yes, No)

5. **Dependents:** Whether the customer has dependents or not (Yes, No)

6. **tenure:** Number of months the customer has stayed with the company

7. **PhoneService:** Whether the customer has a phone service or not (Yes, No)

8. **MultipleLines:** Whether the customer has multiple lines or not (Yes, No, No phone service)

9. **InternetService:** Customer’s internet service provider (DSL, Fiber optic, No)

10. **OnlineSecurity:** Whether the customer has online security or not (Yes, No, No internet service)

11. **OnlineBackup:** Whether the customer has online backup or not (Yes, No, No internet service)

12. **DeviceProtection:** Whether the customer has device protection or not (Yes, No, No internet service)

13. **TechSupport:** Whether the customer has tech support or not (Yes, No, No internet service)

14. **StreamingTV:** Whether the customer has streaming TV or not (Yes, No, No internet service)

15. **StreamingMovies:** Whether the customer has streaming movies or not (Yes, No, No internet service)

16. **Contract:** The contract term of the customer (Month-to-month, One year, Two year)

17. **PaperlessBilling:** Whether the customer has paperless billing or not (Yes, No)

18. **PaymentMethod:** The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))

19. **MonthlyCharges:** The amount charged to the customer monthly

20. **TotalCharges:** The total amount charged to the customer

21. **Churn:** Whether the customer churned or not (Yes or No)
