📊 Sales Performance Dashboard – Microsoft Power BI

"Power BI" (https://img.shields.io/badge/Power%20BI-Dashboard-yellow?style=for-the-badge&logo=powerbi)
"Data Analysis" (https://img.shields.io/badge/Data-Analysis-blue?style=for-the-badge)
"DAX" (https://img.shields.io/badge/DAX-Measures-purple?style=for-the-badge)
"Status" (https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

🚀 Project Overview

The Sales Performance Dashboard is an interactive business intelligence and data visualization project developed using Microsoft Power BI.

The main objective of this project is to analyze sales data and transform raw business data into meaningful insights through interactive visualizations and key performance indicators (KPIs).

This dashboard provides an overview of sales performance, profitability, customer activity, product categories, regional performance, and payment methods.

It helps users understand business performance, identify sales trends, compare different regions, and support data-driven decision-making.

This project represents my practical learning journey in Data Analysis, Business Intelligence, and Power BI Dashboard Development.

🎯 Project Objectives

- Analyze overall sales and profit performance.
- Monitor key business performance indicators.
- Understand sales trends over time.
- Compare sales performance across different regions.
- Analyze sales distribution by product category.
- Understand customer purchasing and payment patterns.
- Develop an interactive and user-friendly dashboard.
- Present business data through meaningful visualizations.

🛠️ Tools & Technologies

Tool / Technology| Purpose
Microsoft Power BI| Dashboard development and data visualization
Power Query| Data cleaning and transformation
DAX| Calculated measures and KPI calculations
Microsoft Excel| Dataset management and data source
Data Visualization| Presenting business insights

📈 Dashboard Key Performance Indicators (KPIs)

The dashboard includes five major KPIs:

KPI| Description
Total Sales| Overall sales revenue
Total Profit| Total profit generated
Total Orders| Number of unique orders
Total Customers| Number of unique customers
Average Order Value| Average sales value per order

📊 Dashboard Features & Visualizations

1. Monthly Sales Trend

Visualizes sales performance over time to identify trends and changes in sales activity.

2. Sales by Region

Compares sales performance across different geographical regions to identify high-performing and low-performing areas.

3. Sales by Category

Analyzes sales distribution across product categories, including:

- Technology
- Furniture
- Office Supplies

4. Sales by Payment Method

Provides insights into customer payment preferences through payment method analysis.

5. Total Sales Distribution

Displays the contribution of different product categories to overall sales performance.

🎛️ Interactive Dashboard Features

The dashboard includes interactive slicers that allow users to filter and explore data dynamically.

Year Slicer

- Filter dashboard data by year.
- Current dataset contains 2025 records.

Region Slicer

- Filter data by individual geographical regions.
- Compare regional sales performance.
- Observe changes in KPIs and charts dynamically.

These interactive features make the dashboard more flexible and user-friendly.

🧮 DAX Measures

The following DAX measures were used to calculate key business metrics.

Total Sales

Total Sales = SUM(SalesData[Sales])

Total Profit

Total Profit = SUM(SalesData[Profit])

Total Orders

Total Orders = DISTINCTCOUNT(SalesData[Order ID])

Total Customers

Total Customers = DISTINCTCOUNT(SalesData[Customer ID])

Average Order Value

Avg Order Value = DIVIDE([Total Sales], [Total Orders], 0)

Year Column

Year = YEAR(SalesData[Order Date])

📌 Key Business Insights

Based on the dashboard's default filter selection:

- Total Sales reached approximately 155M.
- Total Profit was approximately 38.47M.
- The dashboard recorded approximately 1K unique orders.
- The total customer count was 179.
- The Average Order Value was approximately 154.86K.
- Technology represented the largest sales category in the displayed analysis.

Note: KPI values can change when different dashboard filters are selected. Displayed values are based on the current dataset and default filter selection.

💡 Skills Demonstrated

Through this project, I developed and practiced the following skills:

- Data Analysis
- Data Cleaning and Transformation
- Power Query
- DAX Calculations
- KPI Development
- Data Visualization
- Interactive Dashboard Development
- Business Intelligence
- Analytical Thinking
- Data-driven Decision Making

📷 Dashboard Preview

<!-- Add your actual dashboard screenshot here -->"Sales Performance Dashboard" (images/Sales_Performance_Dashboard.png)

📁 Project Structure

Sales-Performance-Dashboard-PowerBI/
│
├── README.md
├── Sales_Performance_Dashboard.pbix
├── images/
│   └── Sales_Performance_Dashboard.png
└── video/
    └── Sales_Performance_Dashboard_Demo.mp4

Update the file names in this structure to match the actual files uploaded to the repository.

🔗 Project Repository

GitHub:
https://github.com/Thenuka-Dissanayaka/Sales-Performance-Dashboard-PowerBI

👨‍💻 About Me

I am a BICT (Hons) undergraduate at the University of Vavuniya, Sri Lanka, with a strong interest in Data Analysis, Programming, and Business Intelligence.

I am continuously developing my technical knowledge and practical skills by working on real-world inspired projects and exploring data-driven solutions.

My current learning interests include:

- Data Analysis
- Microsoft Power BI
- SQL
- Python
- Data Visualization
- Business Intelligence

🌱 Learning Journey

This project is an important step in my journey toward becoming a Data Analyst.

I believe in continuous learning, practical experience, and building projects that demonstrate technical skills and problem-solving abilities.

Thank you for visiting my project repository!

If you find this project useful, feel free to ⭐ Star this repository.

---

Developed by Thenuka Dissanayaka
Data Analysis | Power BI | Business Intelligence
