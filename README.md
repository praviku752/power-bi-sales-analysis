# Power BI Sales Analysis Dashboard

## 📊 Project Overview

This project is an interactive Business Intelligence dashboard developed using Microsoft Power BI to analyze sales performance and generate actionable business insights.

The project demonstrates an end-to-end Power BI workflow, including data preparation, data modeling, DAX calculations, KPI development, and interactive dashboard design.

## 🎯 Business Objective

The objective of this project is to provide a centralized dashboard for monitoring sales performance and identifying trends across different business dimensions.

The analysis focuses on:

- Overall sales performance
- Sales trends over time
- Product/category performance
- Customer analysis
- Channel performance
- Key business KPIs
- Identification of high and low performing segments

## 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel / CSV
- Data Modeling
- Star Schema

## 🗂️ Data Model

The project follows a **Star Schema** approach with a central fact table connected to multiple dimension tables.

### Fact Table

- Fact Sales

### Dimension Tables

- Dim Date
- Dim Product
- Dim Customer
- Dim Channel

The star schema helps improve model organization, filtering, and analytical performance.

## 🔄 Data Preparation

Power Query was used for data preparation and transformation, including:

- Data type standardization
- Data cleaning
- Column transformations
- Creating dimension tables
- Preparing the fact table
- Removing unnecessary fields
- Creating relationships between tables

## 📐 DAX & Measures

DAX measures were created to support the dashboard analysis, including:

- Total Sales
- Total Quantity
- Average Sales
- Sales by Month
- Sales by Category
- Sales by Channel
- Other KPI calculations

Time-based analysis was implemented using a dedicated Date dimension.

## 📈 Dashboard

The dashboard provides interactive analysis using:

- KPI cards
- Sales trend charts
- Category analysis
- Channel analysis
- Product analysis
- Date filters
- Interactive slicers

### Dashboard Preview

<img width="1142" height="647" alt="image" src="https://github.com/user-attachments/assets/3910f42d-a7a7-48f1-8d33-42dd498aebda" />


### Data Model

<img width="962" height="692" alt="image" src="https://github.com/user-attachments/assets/7bf9c168-f610-436f-aa4f-bf653c445ad6" />


## 💡 Key Business Insights

The dashboard can be used to identify:

- Sales growth and decline trends
- Top-performing products and categories
- High-performing sales channels
- Periods of strong and weak sales
- Areas requiring further business attention

## 📁 Repository Structure

```text
power-bi-sales-analysis/
│
├── Pharma_Sales_Analytics.pbix
│   
│
├── Screenshots/
│   ├── Executive_Summary.jpg
│   └── Distributor and Customer Analysis.jpg
│
└── README.md
