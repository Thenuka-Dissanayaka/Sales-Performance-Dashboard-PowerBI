# 📊 Sales Performance Dashboard – Microsoft Power BI

[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?style=for-the-badge&logo=powerbi)](https://github.com/Thenuka-Dissanayaka/Sales-Performance-Dashboard-PowerBI)
[![Data Analysis](https://img.shields.io/badge/Data-Analysis-blue?style=for-the-badge)](https://github.com/Thenuka-Dissanayaka/Sales-Performance-Dashboard-PowerBI)
[![DAX](https://img.shields.io/badge/DAX-Measures-purple?style=for-the-badge)](https://github.com/Thenuka-Dissanayaka/Sales-Performance-Dashboard-PowerBI)
[![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)](https://github.com/Thenuka-Dissanayaka/Sales-Performance-Dashboard-PowerBI)

---

## 🚀 Project Overview

The **Sales Performance Dashboard** is an interactive business intelligence and data visualization project developed using Microsoft Power BI.

The main objective of this project is to analyze sales data and transform raw business data into meaningful insights through interactive visualizations and key performance indicators (KPIs).

This dashboard provides an overview of sales performance, profitability, customer activity, product categories, regional performance, and payment methods. It helps users understand business performance, identify sales trends, compare different regions, and support data-driven decision-making.

---

## 🎯 Project Objectives

- Analyze overall sales and profit performance.
- Monitor key business performance indicators (KPIs).
- Understand sales trends over time.
- Compare sales performance across different regions.
- Analyze sales distribution by product category.
- Understand customer purchasing and payment patterns.
- Develop an interactive and user-friendly dashboard interface.
- Present business data through impactful visualizations.

---

## 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
| :--- | :--- |
| **Microsoft Power BI** | Dashboard development and data visualization |
| **Power Query** | Data cleaning and transformation |
| **DAX** | Calculated measures and KPI calculations |
| **Microsoft Excel** | Dataset management and initial data source |
| **Data Visualization** | Presenting clear and actionable business insights |

---

## 📈 Dashboard Key Performance Indicators (KPIs)

The dashboard tracks five major core metrics:

| KPI | Description |
| :--- | :--- |
| **Total Sales** | Overall sales revenue generated |
| **Total Profit** | Total net profit earned |
| **Total Orders** | Number of unique customer orders |
| **Total Customers** | Number of unique active customers |
| **Average Order Value** | Average sales value per order |

---

## 📊 Dashboard Features & Visualizations

1. **Monthly Sales Trend:** Visualizes sales performance over time to identify seasonal trends and sales fluctuations.
2. **Sales by Region:** Compares performance across different geographical regions to pinpoint high and low-performing areas.
3. **Sales by Category:** Analyzes sales distribution across key product lines (**Technology**, **Furniture**, **Office Supplies**).
4. **Sales by Payment Method:** Provides insight into customer payment preferences.
5. **Total Sales Distribution:** Displays category contributions to overall revenue.

---

## 🎛️ Interactive Dashboard Features

- **Year Slicer:** Filter dashboard metrics dynamically by year (dataset features 2025 records).
- **Region Slicer:** Filter data by individual geographical regions to instantly update KPIs and charts in real-time.

---

## 🧮 DAX Measures

Core business metrics were calculated using the following DAX formulas:

```dax
Total Sales = SUM(SalesData[Sales])
