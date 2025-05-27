🛒 Retail Sales ETL & KPI Dashboard Project

🚀 Project Summary
This project simulates a real-world Retail ETL + Reporting Pipeline where raw transactional data is processed using Python (pandas), cleaned, transformed, and analyzed to derive key performance indicators. The results are then visualized through a Power BI dashboard that can be used by business teams for strategic decisions.

📌 Objective
-Ingest raw sales CSV data
-Clean and prepare the dataset using Python
-Compute KPIs like Revenue, Profit, Margin, and Units Sold
-Aggregate metrics by Region and Product Category
-Export final data for visualization
-Create a dashboard using Power BI to present insights

🧰 Tools & Technologies
Tool	                 Purpose
Python	               Core data processing & calculations
Pandas	               DataFrame operations & ETL logic
Power BI	             Visualize final KPIs & insights
Git/GitHub	           Version control & project hosting
Jupyter Notebook	     Interactive development

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
├── Retail_Sales_ETL_KPI_Analysis.ipynb
|
|
└── README.md

📂 Data Dictionary
Column	                 Description
date	                   Date of transaction
region	                 Sales region
product_category	       Category of the sold product
units_sold	             Quantity of units sold
unit_price	             Price per unit
cost	Total              cost of the sale
revenue	                 units_sold × unit_price
profit	                 revenue − cost
margin	                 profit / revenue

⚙️ Process Flow (ETL)
Extraction: Load raw .csv data

Transformation:
-Clean column names
-Convert date column
-Compute revenue, profit, margin
-Drop missing values if critical fields are empty

Load: Save cleaned data and aggregated results

📊 Power BI Dashboard
The following visuals were created using summary_report.csv:
Total Revenue, Profit, Units Sold (KPIs)
Revenue by Region (Bar chart)
Profit by Product Category (Column chart)
Average Margin by Region (Donut chart)
Detailed Table view

📈 Key Business Insights
🏆 Highest Revenue: North Region
💰 Most Profitable Category: Electronics
📉 Lowest Margin Region: West
📦 High volume: Fashion and Home Decor categories

🛠️ How to Run (Locally)
Clone this repo:
git clone https://github.com/Swagy026/Retail_Sales_ETL_Project.git

Run the ETL notebook:
jupyter notebook Retail_Sales_ETL_KPI_Analysis.ipynb

✅ Future Enhancements
-Add automation using Apache Airflow
-Store raw data in cloud (GCS / S3)
-Write final output to BigQuery / SQL database
-Automate dashboard refresh in Power BI Service
-Add unit testing and data validation steps

🧑‍💼 Author
Built with 💪 by Ashwani Chaudhary
For Data Analyst / Data Engineer roles 

