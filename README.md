# HR Attrition Analysis - Power BI Dashboard

## 📌 Business Problem
Company losing 16.12% employees (237/1470). Identify who & why leaving.

## 📊 Dataset
IBM HR Dataset - 1470 employees, 35 columns (Kaggle)

## 🛠️ Tools Used
Power BI Desktop, DAX, Power Query

## 🧹 Data Cleaning
- Removed duplicates
- Handled nulls
- Created Age Groups, Income Bins

## 📈 DAX Measures
- Active Employees = COUNTROWS(FILTER(HR, HR[Attrition]="No"))
- Attrition Count = COUNTROWS(FILTER(HR, HR[Attrition]="Yes"))
- Attrition % = DIVIDE([Attrition Count], 1470)

## 📷 Dashboard
Single Page Executive Dashboard
- 4 KPI Cards (Active 1K, Attrited 237, Age 18-60, Income ₹19,999)
- Dept wise attrition (Sales 20.6% highest)
- Job Level & Overtime analysis

## 💡 Insights
- Sales: 20.6%, HR: 19%
- Job Level 1: 24%
- Overtime Yes: 30%

## ✅ Recommendations
- Retention bonus for Sales
- Mentorship for Level 1 freshers
- Work-life balance for overtime

## 📁 Files
- PBIX File
- Screenshots & PDF Report
- Dataset & Documentation
