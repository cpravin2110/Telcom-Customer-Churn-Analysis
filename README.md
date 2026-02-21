# 📊 Telecom Customer Churn Analysis

---
![Dashboard Preview](Screenshot%202025-11-22%20131808.png)

---

## 📌 Project Overview

Customer churn significantly impacts revenue, profitability, and long-term business growth in the telecom industry. This project analyzes 7,043 telecom customers with 21 features using Python-based Exploratory Data Analysis (EDA) to identify churn patterns, high-risk customer segments, and key business drivers behind customer attrition.

The analysis revealed an overall churn rate of 26.5% (1,869 customers), highlighting a substantial revenue risk. Key factors such as contract type, tenure, payment method, and service subscriptions were found to strongly influence customer retention and churn behavior.

---

## 🔍 Dataset Snapshot

Total Customers: 7,043

Total Features: 21

Churned Customers: 1,869

Churn Rate: 26.5%

---


### Key Attributes Analyzed:

**Tenure, contract type, subscribed services, monthly charges, total charges, payment methods, and demographics.**

---


## 🧹 Data Preparation & Feature Engineering (Python)

Cleaned missing values and corrected data types in TotalCharges

Created new analytical features such as:

Service_Count

AvgMonthlySpend

SeniorCitizen_YN

Ensured 100% clean and analysis-ready dataset with no missing values

---

## 📈 Key Insights

**📉 Overall Churn Behavior**

⁘ 26.5% churn rate indicates over 1 in 4 customers leave the service.

⁘ 40% of churned customers left within the first 6 months, showing high early-stage risk.

**📅 Contract Type Impact (Strongest Driver)**

⁘ Month-to-month contracts contributed to 63% of total churn

⁘ 1-year contracts: 17% churn

⁘ 2-year contracts: only 4% churn
➡ Long-term contracts significantly improve retention

**💳 Payment Method Risk**

⁘ Electronic check users showed the highest churn rate at 43%

⁘ Credit card and bank transfer customers had lower churn (≤ 25%)
➡ Payment method is a key churn risk indicator

**📺 Service Subscription Impact**

⁘ Customers with 0–2 services churn nearly 2× faster than customers with 5+ services
➡ More service adoption improves customer retention

**🧓 Customer Demographics**

⁘ Senior citizen churn rate: 31%

⁘ Non-senior churn rate: 24%
➡ Senior customers are at higher churn risk

**💡 Business Insights & Recommendations**

» Convert month-to-month customers into long-term contracts to reduce churn risk

» Promote bundle service packages to increase customer retention

» Focus retention strategies on new customers within first 6 months

» Encourage customers to switch from electronic check to secure payment methods

---

## 🛠 Tools & Technologies

● Python

● Pandas & NumPy – Data analysis

● Matplotlib & Seaborn – Data visualization

● Jupyter Notebook – Analysis environment

---

## 🚀 Conclusion

This analysis identified key churn drivers including contract type, payment method, tenure, and service adoption, with month-to-month contracts and electronic check users showing the highest churn risk. The findings show that early customer experience and service engagement are critical for retention.

By targeting high-risk segments and promoting long-term contracts and service bundles, telecom companies can significantly reduce churn, improve customer lifetime value, and increase overall business stability through data-driven retention strategies.

---

## 📁 Project Structure

Telecom-Customer-Churn-Analytics/
│
├── Telcom Customer Churn Analysis.ipynb
├── Telcom churn project images pdf.pdf
└── README.md

---

### 🤝Connect

If you like this project or want to collaborate, feel free to connect!

📌 LinkedIn:  [LinkedIn](https://www.linkedin.com/in/iampravinchavan/) 
