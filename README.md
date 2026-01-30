# 📊 Telecom Customer Churn Analytics

## 📌 Project Overview

Customer churn has a direct impact on **revenue, growth, and customer lifetime value** in the telecom industry.
This project focuses on analyzing telecom customer data to identify **who is churning, why they churn, and which customer segments require immediate attention**.

The analysis is entirely **data‑driven**, using Python-based Exploratory Data Analysis (EDA) to extract actionable business insights.

---

## 🔍 Dataset Snapshot

* **Total customers:** 7,043 (active & cancelled)
* **Total features:** 21
* **Key attributes include:**

  * Tenure
  * Contract type
  * Services subscribed
  * Monthly & total charges
  * Payment methods
  * Demographics

---

## 🧹 Data Preparation & Feature Engineering (Python)

* Cleaned blank values in **TotalCharges** and corrected data types
* Created new analytical features:

  * `SeniorCitizen_YN`
  * `Service_Count`
  * `AvgMonthlySpend`
* Ensured **zero missing values**, making the dataset analysis‑ and model‑ready

---

## 📈 Key Insights from Analysis

### 📉 Overall Churn

* **Churn rate:** 26.5%
* **Total churned customers:** 1,869

### 👥 Gender Impact

* Female churn rate: **25%**
* Male churn rate: **27%**
  ➡ Churn difference by gender is minimal

### 🧓 Age Effect

* Senior citizen churn: **31%**
* Non‑senior churn: **24%**
  ➡ Senior customers are at higher churn risk

### 📅 Contract Type Impact

* Month‑to‑month contracts account for **63% of total churn**
* 1‑year contracts: **17%**
* 2‑year contracts: **4%**
  ➡ Contract duration is the strongest churn driver

### 💳 Payment Method Risk

* Electronic check: **43% churn** (highest risk)
* Mailed check: **29% churn**
* Credit card / Bank transfer: **≤ 25% churn**

### 📺 Service Bundling Effect

* Customers with **0–2 services churn nearly 2× faster** than customers with **5+ services**

### 💰 Tenure Insights

* **40% of churned customers leave within the first 6 months**
* Median tenure of churned customers: **9 months**

---

## 💡 Business Takeaways

* Encourage **month‑to‑month customers** to switch to long‑term contracts
* Promote **bundle / combo service plans** to improve retention
* Focus retention efforts on **new customers in their early months**
* Reduce dependency on **high‑churn payment methods** such as electronic checks

---

## 🛠 Tools & Technologies

* **Python**
* **Pandas & NumPy** – Data manipulation
* **Matplotlib & Seaborn** – Data visualization
* **Jupyter Notebook** – Analysis environment

---

## 📁 Project Structure

Telecom-Customer-Churn-Analytics/
│
├── Telcom Customer Churn Analysis.ipynb
├── Telcom churn project images pdf.pdf
└── README.md

---

🤝 Connect

If you like this project or want to collaborate, feel free to connect!

📌 LinkedIn:  [LinkedIn](https://www.linkedin.com/in/iampravinchavan/) 
