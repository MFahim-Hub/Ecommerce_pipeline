# Ecommerce_pipeline

E Commerce Sales Performance Analytics Pipeline
This project demonstrates a complete analytics workflow built from a raw e commerce transactions dataset. The aim was to replicate the workflow expected from a junior data analyst: start with raw CSV data, explore and clean it using Excel and Python (Pandas), validate the results, and present insights through a structured Tableau dashboard.

The pipeline uses:
Excel → Pandas → Tableau → GitHub
All cleaning steps, analysis scripts, exports, and visualisations are included in this repository.

Project Summary
The project begins with an initial exploration of the raw dataset in Excel. This includes checking column types, identifying missing values, reviewing distinct values, and validating that the dataset is suitable for analysis.
The workflow then moves into Python (Pandas), where the dataset is cleaned and prepared. This includes:
•	Fixing data types
•	Handling missing values
•	Removing duplicates
•	Creating calculated fields (e.g., total price)
•	Parsing and extracting date components
•	Validating dataset structure
The cleaned dataset is exported and used to build a Tableau dashboard containing:
•	Three KPIs (Total Customers, Total Orders, Total Revenue)
•	Sales by weekday
•	Monthly revenue trend
•	Product revenue leaderboard
•	Sales by country
•	Geographic map visualisation
The final result is a complete analytics pipeline showing the full journey from raw data to business insights.



Pipeline Overview
Code
Excel (Initial exploration)
        ↓
Pandas (Cleaning, validation, transformation)
        ↓
CSV Export (Analytics ready dataset)
        ↓
Tableau (Dashboard and insights)
        ↓
GitHub (Documentation and publishing)
Project Plan
1. Data Acquisition and Initial Understanding (Excel)
•	Loaded dataset
•	Explored structure, missing values, and column types
•	Identified early cleaning requirements Outcome: Clear understanding of dataset issues and opportunities.
2. Data Cleaning and Validation (Pandas)
•	Cleaned and transformed the dataset
•	Fixed types, handled nulls, removed duplicates
•	Created calculated fields
•	Validated dataset integrity Outcome: Clean, analysis ready dataset.
3. Visualisation and Insight Development (Tableau)
•	Imported cleaned dataset
•	Built KPIs and charts
•	Designed dashboard layout
•	Published to Tableau Public Outcome: Professional, interactive dashboard.




4. Documentation and Publishing (GitHub & LinkedIn)
•	Wrote project summary
•	Created README
•	Uploaded all files
•	Published dashboard
•	Shared insights on LinkedIn Outcome: Fully documented, portfolio ready project.

Repository Structure
Code
project/
│
├── 0 - Project Plan/
│   └── README.md
│
├── 1 - Excel/
│   └── data.csv
│
├── 2 - Pandas/
│   └── cleaning_script.docx
│└── cleaned_data.csv
│
├── 3 - Tableau/
│   ├── E-Commerce Dashboard.png
│   └── E-Commerce Dashboard.twb
│
└── README.md
 
Data Dictionary
Column	Type	Description
InvoiceNo	TEXT	Unique transaction identifier
StockCode	TEXT	Product code
Description	TEXT	Product description
Quantity	INT	Quantity purchased
InvoiceDate	DATETIME	Date and time of transaction
UnitPrice	DOUBLE	Price per unit
CustomerID	TEXT	Unique customer identifier
Country	TEXT	Customer country
Tableau Dashboard
The dashboard includes:
•	KPI: Total Customers
•	KPI: Total Orders
•	KPI: Total Revenue
•	Sales by Day
•	Monthly Revenue Trend
•	Product Revenue Leaderboard
•	Sales by Country
•	Geographic Map

Final Result
This project demonstrates a complete analytics workflow from raw data to insights, showcasing skills in:
•	Excel
•	Pandas
•	Tableau
•	Data Documentation
It reflects the type of pipeline expected from a junior data analyst in a real business environment.
