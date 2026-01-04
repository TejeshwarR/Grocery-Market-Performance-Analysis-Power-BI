# 🛒 Grocery Market Performance Analysis – Power BI

## 📌 Project Overview
This project delivers an **end-to-end Grocery Market Performance Analysis using Power BI**, backed by a **well-structured star-schema data model**. The dashboard is designed to track **transactions, revenue, profit, margins, returns, geographic performance, and target achievement** at both operational and executive levels.

The analysis mirrors a **real-world retail BI implementation**, combining transactional fact data with **product, customer, store, region, return, and calendar dimensions**.
<img width="1390" height="781" alt="image" src="https://github.com/user-attachments/assets/a2ef7cb7-0aed-4aaf-b5f5-ce489b3ecf31" /><img width="1390" height="781" alt="image" src="https://github.com/user-attachments/assets/77a0a6ae-32cf-436f-a7fd-1e886de430fa" />
<img width="1372" height="776" alt="image" src="https://github.com/user-attachments/assets/55f24321-cf30-45ce-8871-4436787d3ec5" />
<img width="1027" height="708" alt="image" src="https://github.com/user-attachments/assets/07015178-9b4e-4d98-bbef-d11f2c41980b" />




---

## 🎯 Business Goal
The primary objectives of this project are to:

- Monitor **sales and profit performance against targets**
- Identify **high- and low-performing grocery products**
- Track **return behavior** and its impact on profitability
- Analyze **geographic revenue distribution**
- Enable **data-driven merchandising and operational decisions**

---

## 🗄️ Data Source & Model

### 🔹 Source Narrative
The data represents extracts from a **retail transaction system / data warehouse** (e.g., MSSQL or a cloud data warehouse), imported into Power BI for analytical reporting.

### 🔹 Data Model (Star Schema)

#### Fact Table
- **Transaction_Data** – transaction-level sales, revenue, profit, and dates

#### Dimension Tables
- **Products** – product name, brand, pricing, cost  
- **Customers** – customer demographics and attributes  
- **Stores** – store location and region mapping  
- **Regions** – geographic grouping  
- **Returns** – returned quantities and return dates  
- **Calendar** – time intelligence (date, week, month)

#### Model Benefits
- Clean **one-to-many relationships**
- Optimized **filter propagation**
- Scalable foundation for **advanced DAX and time intelligence**

---

## 🔄 Methodology
1. Designed a **star-schema semantic model**
2. Created **reusable DAX measures** for KPIs and analysis
3. Built **interactive visuals and KPI cards**
4. Validated trends, targets, and business logic

---

## 📊 Dashboard Highlights

### KPI Cards
- Current Month Transactions  
- Current Month Profit  
- Current Month Returns  
- Profit Margin  
- Revenue vs Target *(Gauge)*  

### Analytical Views
- Product performance *(Transactions, Profit, Margin, Return Rate)*
- Weekly revenue trending
- Geographic revenue map *(USA, Canada, Mexico)*
- Revenue contribution by region

---

## 📈 Key Insights (Final Narrative)
- Several products generate **high margins (>60%)** despite moderate sales volumes
- Current month **revenue and profit are below target**, indicating opportunities for pricing or promotional optimization
- Return rates remain low *(~1%)* but vary significantly by product
- Revenue is **geographically concentrated**, increasing dependency risk
- Weekly revenue trends reveal clear **seasonality patterns**

---

## 🧠 Business Recommendations
1. Prioritize **high-margin products** over pure volume drivers
2. Investigate **low-margin, high-transaction items**
3. Actively manage **weeks trending below target**
4. Diversify **geographic revenue sources** to reduce risk

---

## 🚀 Next Steps
- Enable **live refresh** from source systems
- Add **forecasting and anomaly detection**
- Introduce **basket analysis and customer segmentation**
- Implement **alerts for target deviation**

---

## 👤 Author
**Tejeshwar R**  
Data Analyst | Power BI | SQL | Excel | Python  |  Statistics
