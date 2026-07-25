# Heart Disease Risk Analysis Dashboard

## Overview
An end-to-end data analytics project analyzing heart disease risk factors 
using SQL, Power BI, and cloud data warehousing.

## What This Project Demonstrates
- Data cleaning and validation using Python (Pandas)
- Cloud PostgreSQL database (Supabase) integration
- Advanced SQL queries: joins, subqueries, aggregations, CASE statements
- Power BI dashboard with custom DAX measures (CALCULATE, AVERAGEX, DIVIDE)
- Power Query feature engineering (calculated Risk Category column)
- Row-Level Security (RLS) for role-based data access
- AI-driven storytelling using Power BI's Key Influencers and Top Segments

## Key Findings
- Elevated total cholesterol shows the strongest association with heart disease risk
- Smoking and family history each independently increase risk likelihood by ~17%
- A specific patient segment (BMI ≤ 36.4, Cholesterol > 220) represents 32.8% of 
  patients and shows 2x the average heart disease rate

## Dataset Note
This project uses a synthetic dataset ("Heart Disease Risk 2026," Kaggle) for 
demonstration purposes. Findings reflect patterns in simulated data and are not 
validated real-world clinical conclusions. This project showcases technical 
proficiency in data engineering and analytics.

## Tools Used
Python, Pandas, PostgreSQL (Supabase), Power BI, DAX, Power Query, Google Colab

## Files
- `Heart_Disease_Dashboard.pbix` — Power BI report file
- `heart_disease_cleaning.ipynb` — Data cleaning notebook
- `dashboard_screenshot.png` — Preview of the final dashboard
