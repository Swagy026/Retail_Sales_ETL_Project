# 🛒 Retail Sales ETL & KPI Dashboard Project

## 🚀 Project Summary

This end-to-end **ETL + KPI Dashboard project** simulates a real-world retail reporting pipeline.  
It transforms raw sales data using **Python (Pandas)** into business-ready KPIs and visualizes insights via **Power BI**.

The workflow mimics the kind of report automation and data transformation I delivered at Wipro — but using modern, self-coded tools.

---

## 📌 Key Business Goals

- 📥 Clean messy transactional data using Pandas
- 📊 Calculate KPIs: **Revenue, Profit, Margin, Units Sold**
- 🌍 Aggregate by **Region & Product Category**
- 📈 Visualize trends in **Power BI** dashboard

## 🧰 Tools & Technologies

| Tool        | Purpose                           |
|-------------|-----------------------------------|
| Python      | Data transformation & cleaning    |
| pandas      | DataFrame manipulation            |
| Power BI    | Visual dashboard for KPIs         |
| GitHub      | Project versioning and showcase   |
| Jupyter Notebook | Code documentation & workflow |

🔁 This project mirrors 100+ manual reports I delivered at Wipro, now reimagined with Python.

---

📁 Folder Structure
Retail_Sales_ETL_Project/
│
├── data/
│   ├── raw_sales_data.csv
│   └── cleaned_sales_data.csv
│
├── output/
│   └── summary_report.csv
│
├── visuals/
│   ├── dashboard.pbix
│   └── dashboard_screenshot.png
│
|
├── scripts/
├── sales_etl_pipeline.ipynb
|
├── requirements.txt
└── README.md


---

## 📈 Data Dictionary

| Column           | Description                             |
|------------------|-----------------------------------------|
| date           | Date of transaction                     |
| region         | Region where the sale occurred          |
| product_category | Product category                      |
| units_sold     | Number of units sold                    |
| unit_price     | Price per unit                          |
| cost           | Total cost of the transaction           |
| revenue        | units_sold × unit_price                 |
| profit         | revenue − cost                          |
| margin         | profit / revenue                        |

---

## ⚙️ ETL Process Flow

1. Extract raw sales data from CSV
2. Transform:
   - Rename & clean columns
   - Convert data types
   - Calculate Revenue, Profit, Margin
3. Load final output as:
   - Cleaned CSV
   - Aggregated summary report

---
## 📊 Power BI Dashboard
![Retail Dashboard](visuals/dashboard_screenshot.png)

## 🧠 Real-World Use Case

> In my previous role at Wipro, we often worked with regional payroll and sales reports in Excel.  
> This project reflects how I could now **replace manual Excel work with automated ETL scripts + modern dashboards**, reducing time and human error.

It proves my ability to **build full-cycle reporting tools using Python**, exactly what’s needed in analyst/automation roles.

---

📬 **Need a Python-powered analyst?**  
I’m available for interviews immediately — connect on [LinkedIn](www.linkedin.com/in/ashwani-kumar-data-analyst).


