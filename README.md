# 💳 Credit-Card-Fraud-Risk-Analysis-Power-BI-Dashboard

This project presents an **interactive Power BI dashboard** designed to analyze and detect patterns in **credit card fraud**.  
The dashboard highlights suspicious transactions, identifies top fraud types, and allows businesses to make informed, data-driven decisions to strengthen fraud prevention.

---

## 🎯 Objectives
- **Detect fraudulent activities** in credit card transactions.  
- **Analyze fraud distribution** by state, merchant, month, and transaction type.  
- Provide **key business indicators (KBIs)** for financial and operational insights.  
- Build an **interactive dashboard** for real-time fraud monitoring.  

---

## 📊 Key Business Indicators (KBIs)
- **Fraud Rate %** – Percentage of fraudulent transactions (**28.6%**).  
- **Fraudulent Transactions** – Total identified fraud cases (**286**).  
- **Critical Risk Transactions** – High-risk transactions requiring urgent attention (**10.7%**).  
- **Fraudulent Transaction Amount** – Total monetary loss due to fraud (**~3M**).  
- **Top Fraud Type** – *Card Not Present* (common in online transactions).  

---

## 🖥️ Dashboard Features

### 🔎 Filter Panel
- **Fraud Type** – Filter by fraud categories (Card Not Present, Skimming, Identity Theft, etc.).  
- **State** – Analyze fraud distribution by Indian states.  
- **Merchant** – Filter transactions by merchant (e.g., Flipkart, Amazon, etc.).  

### 📈 Visual Insights
- **Total Transaction Amount by Fraud Type & Category**  
  - Breakdown across fraud types (Skimming, Phishing, Identity Theft, etc.)  
  - Transaction categories include *E-commerce, Apparel, Food Delivery, Electronics, Groceries, Transportation*.  

- **Total Transaction Amount by Fraud Risk**  
  - Donut chart showing distribution of risk levels:  
    - Low (42.42%)  
    - Medium (27.93%)  
    - High (18.81%)  
    - Critical (10.85%)  

- **Fraudulent Transactions by State**  
  - Bar chart comparing state-level fraud activities (e.g., Maharashtra, Karnataka, Rajasthan).  

- **Fraudulent Transactions by Month**  
  - Line chart showing monthly fraud patterns with spikes in **June** and **December**.  

---

## ⚙️ Workflow
1. **Data Import** – Loaded data from CSV/Excel containing:  
   - Transaction IDs  
   - Merchant names  
   - States  
   - Banks  
   - Transaction dates & amounts  
   - Fraud type, fraud risk, and fraud indicator (0 or 1)  

2. **Data Cleaning & Transformation** – Standardized columns, flagged fraud indicators, and grouped categories.  

3. **Dashboard Design** – Applied a **dark theme** for clarity and readability, adjusted canvas layout.  

4. **Visualization Development** – Built KPIs, charts, and slicers for drill-down analysis.  

---

## 🚀 Insights from the Dashboard
- **Fraud rate** at 28.6% shows a significant threat level.  
- **Card Not Present** is the most common fraud type, highlighting risks in online transactions.  
- **Rajasthan** showed the highest frauds in June, while **Tamil Nadu** faced major merchant-level frauds for Flipkart.  
- Fraud activity **spikes during December**, likely linked to holiday season shopping.

---

## 🔮 Possible Actions & Recommendations

Based on insights from this analysis, organizations can take the following actions:

- **Enhance Fraud Detection Systems**  
  Use patterns like *Card Not Present* and seasonal spikes (e.g., December) to train fraud detection models.  

- **Merchant-Level Monitoring**  
  Track merchants with high fraud activity (e.g., Flipkart in Tamil Nadu) and implement stricter transaction verification.  

- **State-Level Risk Assessment**  
  Deploy additional security measures in high-risk states such as Rajasthan and Maharashtra.  

- **Transaction Alerts**  
  Set automated alerts for **critical and high-risk transactions** to prevent financial losses.  

- **Customer Education**  
  Educate users about common fraud types like *Skimming, Phishing, and Identity Theft* to reduce risk.  

- **Integration with Machine Learning** *(Future Scope)*  
  The dashboard can be extended with a **fraud prediction model** in Python/R and embedded into Power BI.  

---

## 🛠️ Tools & Technologies
- **Power BI Desktop** (Data Visualization & Dashboarding)  
- **Excel/CSV** (Data Source)  

---

## 📷 Dashboard Preview
![Dashboard Screenshot]([./3a3df3f2-d8fe-4ff2-8bc3-f50df0b22b38.png](https://github.com/m-hamza-7/Credit-Card-Fraud-Risk-Analysis-Power-BI-Dashboard/blob/main/Main.png)](https://github.com/m-hamza-7/Credit-Card-Fraud-Risk-Analysis-Power-BI-Dashboard/blob/main/Main.png)

---

## 📂 How to Use
1. Clone this repository.  
2. Open the `.pbix` file in **Power BI Desktop**.  
3. Use the **filter panel** (Fraud Type, State, Merchant) to explore fraud patterns interactively.  
4. Analyze KPIs, charts, and visualizations to gain insights into fraud risk.  

---
