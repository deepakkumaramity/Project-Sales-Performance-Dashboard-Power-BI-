# 📊 Sales Performance Dashboard (Power BI)

## 🚀 Project Overview
This project is a **Sales Performance Dashboard** built using Power BI to analyze business data and generate insights.

---

## 🎯 Objective
- Analyze sales trends
- Track KPIs (Sales, Profit, Growth)
- Identify top-performing regions & products

---

## 🛠 Tools Used
- Power BI  
- DAX  
- Excel  

---

## 📸 Dashboard Preview

### 🔹 Sales & Marketing Dashboard
![Dashboard 1]<img width="1133" height="640" alt="Screenshot 2026-03-30 134728" src="https://github.com/user-attachments/assets/7b98e45f-1c36-46b5-98b5-de7e83394a0c" />


### 🔹 Executive Dashboard
![Dashboard 2](Images/dashboard2.png)

### 🔹 KPI Performance Dashboard
![Dashboard 3](Images/dashboard3.png)

---

## 📊 Key Features
- KPI Cards (Sales, Profit, Units)
- Sales Trend Analysis
- Region-wise Performance
- Interactive Filters (Slicers)

---

## 🧠 DAX Formulas Used

```DAX
Total Sales = SUM(Sales[Sales])
Authur - Deepak kumar
Profit = SUM(Sales[Sales]) - SUM(Sales[Cost])

Profit % = DIVIDE([Profit], [Total Sales], 0)
