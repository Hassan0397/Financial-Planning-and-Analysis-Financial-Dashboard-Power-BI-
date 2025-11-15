# FP&A Financial Dashboard (Power BI)

A professional Financial Planning & Analysis (FP&A) Dashboard built in Microsoft Power BI, designed to simulate how finance teams in multinational companies track Revenue, Expenses, Budgets, Variance, and Department Performance.

This project demonstrates enterprise-grade BI skills including data modeling, DAX, finance KPIs, and clean dashboard UI/UX.

# Features
# Enterprise-Level Financial Insights

Revenue, Expenses, Profit, Operating Margin

Budget vs Actual Analysis

Variance & Variance %

YoY Growth & Rolling 12-Month Metrics

Department & Project Performance

# Professional Dashboard Design

Multi-page Power BI report (Executive, P&L, Department Analysis)

Alignment, formatting, color themes (Revenue–Blue, Expenses–Red)

Interactive filters, drilldowns, tooltips, slicers

# FP&A & BI Best Practices

Star Schema Data Modeling

Dedicated ModelMeasures table

Time Intelligence (YoY, Rolling 12)

Clean relationships & DimDate table

Enterprise-grade visuals

# Data Model (Star Schema)
# Fact Tables

fact_finance – Actual revenue & expenses

fact_budget – Department budgets

# Dimension Tables

DimDate – Calendar table (marked as Date Table)

dim_department – Department master

dim_project – Project master

# Data Preparation Steps

Created realistic finance & budget CSV files

Built DimDate using CALENDAR()

Marked DimDate as official date table

Linked facts & dimensions (1-to-many relationships)

Cleaned data types (Date, Decimal, Currency, %)

# Core DAX Measures
# Financial KPIs

Total Revenue

Total Expenses

Gross Profit

Operating Margin (%)

# Budget & Variance

Total Budget

Budget Variance (Actual – Budget)

Budget Variance %

# Time Intelligence

Revenue YoY Growth

Rolling 12-Month Revenue

# Report Pages
# 1️⃣ Executive Overview

  KPI Cards

  Revenue Trend (with forecast)

  Waterfall visualization

  Budget vs Actual

  Department Variance Table

  [Executive Overview Page Preview](http://github.com/Hassan0397/Financial-Planning-and-Analysis-Financial-Dashboard-Power-BI-/blob/main/Executive%20Overview%20of%20Dashboard.png)

# 2️⃣ P&L Matrix

  Income Statement-style view

  Drilldown by Category → Subcategory

  Monthly/Yearly P&L

  Conditional formatting for performance

# 3️⃣ Department Analysis

  Department & Date slicers

  Revenue Trend

  Top Projects by Expense

  KPI Cards (Revenue, Expense, Margin)

# Future Enhancements

What-If Analysis for budgeting

Forecasting page with decomposition tree

Drillthrough page for transaction details

Row-Level Security (RLS)

Publish to Power BI Service with scheduled refresh

# Skills Demonstrated

FP&A Dashboard Design

Power BI Data Modeling

DAX for Finance Analytics

KPI Engineering

Executive-Level Storytelling

Enterprise Reporting Standards

# How to Use This Project

Download or clone the repository

Open the .pbix file in Power BI Desktop

Explore pages, slicers, and KPIs

Modify data or add your own CSVs for practice
