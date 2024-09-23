# **Customer Churn & Retention Analysis in Power BI**

## **Overview**
This project focuses on analyzing customer churn and retention for **PhoneNow**, a telecom company, using Power BI. The goal is to identify key drivers of churn, provide insights into customer demographics, service usage, and offer recommendations to improve customer retention.

The dataset includes customer demographic information, service subscriptions, account details, payment methods, and churn status. This analysis will help **PhoneNow** understand patterns in customer behavior and address areas that impact churn.

---

## **Dataset Information**
The dataset contains the following columns:
- `customerID`: Unique identifier for each customer.
- `gender`: Gender of the customer (Male/Female).
- `senior_Citizen`: Whether the customer is a senior citizen (Yes/No).
- `partner`: Whether the customer has a partner (Yes/No).
- `dependents`: Whether the customer has dependents (Yes/No).
- `tenure`: Number of months the customer has been with the company.
- `phone_service`: Whether the customer has phone service (Yes/No).
- `multiple lines`: Whether the customer has multiple phone lines (Yes/No).
- `internet_service`: Whether the customer has internet service (DSL, Fiber optic, None).
- `online service`, `online backup`, `device protection`, `tech support`, `streamingTV`, `StreamingMovies`: Additional services subscribed by the customer (Yes/No).
- `contract`: Type of contract (Month-to-month, One year, Two year).
- `paperless`: Whether the customer has opted for paperless billing (Yes/No).
- `payment method`: Method of payment (Credit card, Bank transfer, etc.).
- `monthly charges`: Monthly charges paid by the customer.
- `total charges`: Total charges accrued by the customer.
- `numAdminTickets`: Number of administrative tickets opened by the customer.
- `numTecTickets`: Number of technical tickets opened by the customer.
- `churn`: Whether the customer has churned (Yes/No).

---

## **Project Goals**
The objectives of this project are to:
1. **Analyze churn rate** across different demographics and services.
2. **Identify key factors** that contribute to customer churn.
3. **Provide actionable insights** to improve customer retention.
4. **Visualize data** to support decision-making for PhoneNow's retention strategies.

---

## **Power BI Dashboard Structure**

### **1. Overview & Key KPIs**
- Displays overall churn rate, total customers, and monthly revenue.
- Provides high-level KPIs for decision-making.

### **2. Customer Demographics**
- Analyzes churn based on gender, senior citizen status, partner, and dependents.
- Visualizes churn rates by customer tenure.

### **3. Services Analysis**
- Breaks down the services customers subscribe to (phone, internet, tech support, etc.).
- Compares service usage between churned and retained customers.

### **4. Financial Insights**
- Analyzes monthly charges, total revenue, and payment methods.
- Compares contract types and their impact on churn.

### **5. Support & Tickets**
- Investigates how administrative and technical support requests relate to churn.
- Identifies customers who may churn due to frequent technical issues.

---

## **How to Use This Repository**

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/SathyamoorthyKGit/Customer-Retention.git
   cd Customer-Retention

   
