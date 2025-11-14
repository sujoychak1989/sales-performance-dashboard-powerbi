# 📊 Sales Performance Dashboard (Power BI)
### End-to-end Business Intelligence Project (May–July 2025)

This project is a fully developed Power BI dashboard that analyzes sales performance across multiple regions and departments.  
It includes KPIs, trend analysis, error tracking, and incentive breakdown using a 400+ row dataset.

---

## 🚀 Key Features
- KPI Cards for Total Revenue, Total Orders, Avg Revenue Per Order, and Error Rate  
- Daily Revenue Trend (Line Chart)  
- Department-wise Incentive Distribution (Donut Chart)  
- Region & Date Slicers for interactive filtering  
- Department-wise performance table  
- Professional **Dark Theme Dashboard** with consistent styling  
- Custom DAX measures & Power Query data cleaning  

---

## 🛠️ Tools Used
- Power BI Desktop  
- Power Query (ETL)  
- DAX (Measures)  
- MS Excel  
- Data Modeling  

---

## 📁 Project Files
- `Sales_Performance_Dashboard.pbix` (Full Dashboard File)  
- `Sales_Data.xlsx` (Raw Dataset)  
- `Screenshots/` (Dashboard Images)  

👉 Upload these files manually after creating this repository.

---

## 📷 Dashboard Preview
(Add a screenshot here after uploading your image)

---

## 🧮 DAX Measures Used
otal Revenue = SUM(Sales[Revenue])

Total Orders = SUM(Sales[Orders])

Avg Revenue Per Order =
DIVIDE([Total Revenue], [Total Orders], 0)

Error Rate =
DIVIDE(SUM(Sales[Errors]), SUM(Sales[Orders]), 0)


---

## 🎯 Insights Delivered
- Revenue increased steadily month-over-month  
- Support & Marketing have higher error rates  
- Finance receives the highest incentive share  
- Sales department has consistent monthly order volume  

---

## 🧑‍💼 Created By
**Sujoy Chakraborty**  
Power BI | Business Analyst | Data Enthusiast  
GitHub: https://github.com/sujoychak1989
