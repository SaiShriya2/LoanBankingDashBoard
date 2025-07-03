# 📊 Loan Portfolio & Risk Analysis - ABC Bank

ABC Bank operates across multiple countries in the finance sector. This project utilizes **Power BI** to analyze the bank’s loan portfolio, gain insights into loan performance, assess risk factors, and optimize lending practices using data-driven decision making.

## 🎯 Objective

To visualize and analyze the loan dataset using **Power BI Desktop** and **Power BI Service**, providing a comprehensive overview of:

- Loan performance
- Credit risks
- Customer demographics
- Yearly trends
- Regional breakdowns

---

## 🧠 Problem Statement

The bank collects loan data from multiple sources (loan forms, credit bureaus, internal systems, financial statements) into two files:

- `Bank Loan.xls`
- `Bank Region.csv`

The dataset requires integration, cleaning, transformation, and aggregation to ensure accuracy and consistency.

---

## 🧾 Metadata: Loan Status Mapping

| Code | Meaning                                 |
|------|------------------------------------------|
| A    | Contract Finished, No Problems (Fully Paid) |
| B    | Contract Finished, Loan Not Paid (Default)  |
| C    | Running Contract, OK So Far (Timely Payment)|
| D    | Running Contract, Client in Debt (Late Payment) |

---

## ⚙️ Environment

- Power BI Desktop
- Power BI Service

---

## 📌 Questions Answered in the Report

### Loan Distribution & Demographics
- ✅ Total loan amount given, total customers, and number of cities served
- ✅ Demographic profile by Country, State, and City
- ✅ Housing status: Own Home, Rent, Mortgage
- ✅ Loan terms taken by customers
- ✅ Top 5 reasons for loan applications
- ✅ Customer segmentation details

### Yearly Analysis & Loan Risk (Focus: 2015)
- ✅ Total loan amount for the selected year and YoY growth
- ✅ Number of loan defaulters (from `Status` column)
- ✅ Credit rating classification from credit scores:

| Score Range     | Rating      |
|-----------------|-------------|
| > 800           | Excellent   |
| 740–800         | Very Good   |
| 670–740         | Good        |
| 580–670         | Fair        |
| 300–580         | Poor        |
| < 580           | Very Poor   |

- ✅ Monthly customer growth trend (Month-Year format, e.g., Jan’15)
- ✅ Customers vs. defaulters by Market
- ✅ Top countries with highest number of defaulters
- ✅ Correlation of credit score with home ownership and job tenure

---

## 🔄 Slicers and Filters

- Year selector (Default focus: 2015)
- Country / State / City filters
- Loan Status filter (A, B, C, D)

---

## 📑 Pages in the Report

1. **Overview Dashboard**: High-level KPIs and loan summary
2. **Demographics**: Regional and customer profile
3. **Loan Risk**: Credit score, loan status, defaulters, trends
4. **Customer Growth**: Time-based trend visuals
5. **Market Analysis**: Regional breakdown of defaulters
6. **Customer Insights**: Housing, employment, credit rating
7. **Full Customer Details** (Exportable): Drillthrough by country, downloadable in CSV
8. **Phone View**: Key metrics optimized for mobile
9. **Q&A Page** (Power BI Service): Natural language insights

---

## ✅ Interactions & Features

- Dynamic title updates based on selected year
- Drill-through and button-based navigation across pages
- CSV export of full customer details
- Conditional visibility toggle to show customer credit rating on detail page
- Slicer synchronization across pages
- Responsive layout for both desktop and phone view
- Currency formatting in **$**, percentages with **2 decimal places**
- Aligned visuals with proper business labels and clean layout

---

## 📌 Power BI Best Practices Followed

- Loaded only required data columns
- Applied appropriate data types
- Used business-friendly naming conventions
- Applied clean, consistent layout
- Used tooltips, DAX measures, and proper aggregations

---

## 🤖 Q&A Experience (Power BI Service)

Customers can use natural language queries to get instant answers such as:

- "What is the total loan amount and number of defaulters?"
- "How many customers across Country, State, City?"
- "What is the trend of customer growth month-wise?"

---

## 📦 Deliverables

- `.pbix` Power BI report file
- Phone view design
- Exportable customer detail table
- Q&A enabled Power BI Service dashboard

---

## 📝 Author

**Sai Shriya Lingala**

---

