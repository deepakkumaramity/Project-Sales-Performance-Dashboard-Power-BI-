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

<img width="705" height="636" alt="Screenshot 2026-03-30 134708" src="https://github.com/user-attachments/assets/6b485ee6-901a-477f-98cd-ffd9effe580b" />

### 🔹 Executive Dashboard

<img width="912" height="564" alt="Screenshot 2026-03-30 134717" src="https://github.com/user-attachments/assets/08ef9a61-9300-43cb-a9d2-b9bb0fe77abe" />


### 🔹 KPI Performance Dashboard


<img width="1133" height="640" alt="Screenshot 2026-03-30 134728" src="https://github.com/user-attachments/assets/05811b83-6d16-4a6c-85c9-79f2b5773006" />

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
