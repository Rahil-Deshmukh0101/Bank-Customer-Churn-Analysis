# Bank Customer Churn Analysis

## 📌 Project Overview  
This project focuses on analyzing **customer churn** in the banking sector using Power BI. Churn (customer exit) is a critical problem for businesses, as retaining existing customers is often more cost-effective than acquiring new ones.  

The project leverages **data analysis and visualization** techniques to identify churn patterns, key influencing factors, and actionable insights to help reduce attrition and improve customer retention strategies.  

---

## 🎯 Objectives  
- Identify **churn rate by demographics** (gender, geography, age).  
- Analyze **financial factors** such as balance, credit score, salary, and tenure.  
- Understand the impact of **active membership and credit card holding**.  
- Provide **data-driven insights** for retention strategies.  

---

## 📂 Dataset  
The dataset contains customer information with the following key attributes:  

- **CustomerInfo**: CustomerID, Surname  
- **ActiveCustomer**: ActiveID, ActiveCategory  
- **ExitCustomer**: ExitID, ExitCategory  
- **CreditCard**: CreditID, Category  
- **Geography**: GeographyID, GeographyLocation  
- **Gender**: GenderID, GenderCategory    
- **Bank_Churn**: CustomerID, Age, Balance, CreditScore, Bank DOJ, Exited, EstimatedSalary, GenderID, CreditID, ExitID, GeographyID, ActiveID  
  

---

## 🔑 Key Analyses  
- **Churned Customers by Geography Location**  
  - Germany: 814 customers (**39.97%**)  
  - France: 810 customers (**39.76%**)  
  - Spain: 413 customers (**20.27%**)  

- **Churn by Gender**  
  - Female churn rate: **25%**  
  - Male churn rate: **17%**  

- **Churn by Active Membership**  
  - Inactive members churn rate: **27%**  
  - Active members churn rate: **14%**  

- **Churn by Age Group**  
  - Age 35–45 churn rate: **32%**  
  - Age 18–25 churn rate: **12%**  

- **Churn by Balance & Salary**  
  - Zero balance churn rate: **30%**  
  - Balance > ₹100K churn rate: **18%**  
  - Mid-salary (₹50K–₹100K) churn rate: **23%**  
  - High salary (>₹150K) churn rate: **15%**  

---

## 📊 Dashboard / Visualizations  
The analysis was visualized using **Power BI** to create an interactive dashboard with:  
- 📈 Churn Distribution by Geography, Gender, Age  
- 📊 Active vs Inactive Member Churn  
- 💳 Credit Card Holders vs Non-holders  
- 💵 Financial Factors (Balance, Salary, Credit Score)  
- 📉 Exit vs Retained Customers  

## 📊 Dashboard Preview

![Dashboard Screenshot](dashboard%20ss%20-%20customer%20churn.png)

---

## 📌 Insights & Business Impact  

1. **Geographic Churn Distribution** – Germany (**814 churned, 39.97%**), France (**810 churned, 39.76%**), and Spain (**413 churned, 20.27%**), Germany & France together contribute **80% of total churn**.  
2. **Inactive vs Active Members** – Inactive members churn rate is **27%**, compared to only **14%** for active members, inactivity nearly **doubles churn risk**.  
3. **Gender-based Churn** – Female customers churn at **25%**, while male customers churn at **17%**, females are **1.47x more likely** to leave.  
4. **Age Factor** – Customers aged **35–45** churn at **32%**, compared to just **12%** in the 18–25 group, middle-aged customers are the most vulnerable.  
5. **Balance Effect** – Customers with a balance of **0** have a churn rate of **30%**, compared to **18%** for balances above ₹100K, low balance strongly increases exit probability.  
6. **Credit Score** – Customers with scores **<600** churn at **28%**, while those **>750** churn at only **11%**, low-score customers are **2.5x more likely** to churn.  
7. **Salary Impact** – Mid-salary (₹50K–₹100K) churn is **23%**, compared to **15%** for high salary (>₹150K) and **16%** for low salary (<₹30K).  
8. **Tenure** – Customers with tenure **1–2 years** churn at **31%**, while those with tenure **>8 years** churn at just **9%**, long-term customers are **3.4x more loyal**.  
9. **Credit Card Ownership** – Holders churn at **19%**, while non-holders churn at **21%** only a **2% difference**, showing limited retention effect.  
10. **Overall Churn Rate** – Out of **10,238 customers**, **2,037 churned (19.9%)** nearly **1 in 5 customers exit**, creating significant acquisition cost pressure.  

---

## 🚀 Future Scope  
- Build a **Machine Learning churn prediction model**.  
- Develop a **real-time churn monitoring dashboard**.  
- Implement **recommendation systems** for personalized retention offers.  

---

## 📌 Note on Dashboard Features

Many of the visualizations in this **Customer Churn Analysis Dashboard** are **integrated with drill-downs**, allowing users to interactively explore customer churn patterns across different dimensions such as:  

- Geography (Country/Region)  
- Customer Activity (Active vs Inactive)  
- Demographics (Age, Gender)  
- Account Features (Credit Card, Balance, Credit Score)  

This design enables a **more in-depth analysis** and helps identify high-risk customer segments effectively.

