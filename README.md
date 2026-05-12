# 📊 Customer Churn Analysis using Power BI
<img width="1064" height="443" alt="SEG_BlogHeader_CustomerChurnAnalysis" src="https://github.com/user-attachments/assets/eed91ddd-eca4-415a-8033-2e9d5f24c4e9" />
## 📌 Project Overview

This project presents an interactive **Customer Churn Analysis Dashboard** built using **Microsoft Power BI**. The goal is to analyze customer churn behavior, identify key drivers of churn, and provide actionable insights to help reduce customer attrition.

---

## 🗂️ Dashboard Pages

### 1. Churn Dashboard
A high-level overview of churn metrics including:
- **1,869** Customers at Risk
- **2,173** Tech Tickets | **885** Admin Tickets
- **$2.86M** Yearly Charges | **$139.13K** Monthly Charges
- Demographics by Gender (49.76% Female / 50.24% Male)
- Subscription time distribution
- Subscribed services breakdown
- Payment method and contract type analysis
- Internet service usage

### 2. Customer Risk Analysis Dashboard
A detailed risk analysis view including:
- **7,043** Total Customers
- **26.54%** Overall Churn Rate
- **$16.06M** Yearly Charges
- **3,632** Admin Tickets | **2,955** Tech Tickets
- Churn rate by internet service type
- Type of contract analysis
- Years of contract vs churn rate
- Churn by payment method

---

## 📈 Key Insights

- The overall churn rate is **26.54%**, with **1,869** customers identified as at risk.
- **Month-to-month contract** customers have the highest churn rate at **42.71%**, compared to **11.27%** (one year) and **2.83%** (two year).
- **Fibre Optic** internet users have the highest churn rate at **41.89%**, followed by DSL at **18.96%**.
- **Electronic Check** is the most common payment method among churned customers at **45.29%**.
- Customers with shorter tenure (under 1 year) account for **55.48%** of churned customers.
- Only **17%** of churned customers subscribed to Tech Support, and **16%** to Online Security — indicating low adoption of value-added services.
- **25%** of churned customers are senior citizens, and **36%** had a partner.

---

## 💡 Suggestions

- Extend basic contract plans from monthly to 3–6 months to improve retention.
- Target single customers with no dependents with personalized offers and loyalty programs ("Catch them Young" strategy).
- Bundle Tech Support, Device Protection, and Online Security into standard packages to boost satisfaction.
- Investigate Fibre Optic service quality issues to reduce its high churn rate.
- Incentivize customers to switch from Electronic Check to auto-pay methods.

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Microsoft Power BI | Dashboard creation and data visualization |
| DAX | Calculated measures and KPIs |
| Power Query | Data transformation and cleaning |
| Excel / CSV | Source data |

---
<img width="1000" height="566" alt="churn-analysis-pages" src="https://github.com/user-attachments/assets/8abdcd88-7e2c-412b-aa64-9dc89f8e3796" />

## 📂 Project Structure

```
Customer-Churn-Analysis-using-Power-BI/
│
├── CustomerChurn.pbix       # Power BI report file
├── data/
│   └── churn_data.csv       # Source dataset
├── screenshots/
│   ├── churn_dashboard.png
│   └── risk_analysis.png
└── README.md
```

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open `CustomerChurn.pbix` in **Microsoft Power BI Desktop**.
3. Refresh the data source if needed.
4. Navigate between dashboard pages using the tabs at the bottom:
   - **Churn Dashboard**
   - **Customer Risk Analysis**
   - **Insights**
   - **Email**

---

## 👩‍💻 Author

**Shreya Jagtap**  
Data Analyst | Power BI Developer

---

## 📃 License

This project is for educational and portfolio purposes only.
