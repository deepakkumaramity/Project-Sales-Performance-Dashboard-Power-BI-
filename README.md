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
![Dashboard 1](Images/dashboard1.png)

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
