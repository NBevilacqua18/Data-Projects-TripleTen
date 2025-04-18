# 🏙️ Manhattan Airbnb Analysis
## 🚀 Project Overview
**Spreadsheet Data Analysis**
As part of the TripleTen Data Analytics Bootcamp, I took on the role of a **Business Intelligence Analyst** to help a client analyze the Manhattan vacation rental market using Airbnb data. The primary goal was to guide investment decisions by identifying the most attractive neighborhoods and property sizes and estimating potential revenue from high-performing listings.
This spreadsheet-based analysis represents a deeper dive into data cleaning, pivot tables, and revenue calculations using real-world datasets.
---
## 🧑‍🎓 Role:
**Business Intelligence Analyst**
---
## 📈 Business Objectives
The client needed data-driven recommendations to make smart property investment choices in Manhattan’s vacation rental space. My analysis addressed two key questions:
1. **Which neighborhoods and property sizes are most attractive for vacation rentals?**
2. **How much revenue did these listings generate?**
---
## 🧹 Data Cleaning Steps
- Created a `neighborhood_clean` column by removing inconsistent capitalization and trailing spaces.
- Added a `bedrooms_clean` column to treat empty values as studio apartments (0 bedrooms).
- Labeled top listings using a `top_listing` column based on popular neighborhood-property size pairs.
- In the calendar dataset, calculated `revenue_earned` for each day using availability and adjusted price.
- Used `SUMIF()` to consolidate 30-day revenue into the listings data.
- Estimated **annual revenue** by multiplying 30-day revenue totals by 12.
---
## 🔍 Key Insights
### 🌆 Most Attractive Neighborhoods (Based on Reviews LTM)
Using the number of reviews in the last 12 months as a proxy for demand:
- **Top 3 Neighborhoods:**
  - Harlem
  - Greenpoint
  - Hell’s Kitchen
- Visualized using a bar chart for top 10 neighborhoods by number of reviews.
---
### 🛏️ Most Popular Property Sizes
From cleaned data:
- Most popular listings by size:
  - **Studios**
  - **1-bedrooms**
  - **2-bedrooms**
- In Harlem, for instance, **1-bedroom listings** were most in demand.
---
### 💰 Revenue Insights
- Added `revenue_earned` column based on whether the listing was booked.
- Summarized 30-day revenue per listing and projected **annual revenue**.
- Filtered listings to highlight **top performers** (in top 10 neighborhoods with popular bedroom size).
- **Top-Earning Listing ID:** `44267714`
---
## 📄 Deliverables
- 📊 **Excel Workbook** with:
  - Pivot tables
  - Cleaned and organized data
  - Revenue calculations
  - Visuals (charts)
  - Executive Summary and Table of Contents
  - Documented assumptions and cleaning steps
---
## ✅ Final Recommendations
- **Invest in 1-bedroom properties** in high-demand neighborhoods like Harlem and Greenpoint.
- **Studios in Midtown** also show strong potential based on localized demand.
- **Target properties with consistent booking histories**, as shown by high review counts.
- Use **estimated annual revenue** to filter and prioritize listings for acquisition.
---
## 🛠 Skills Demonstrated
- Spreadsheet data cleaning
- Pivot table analysis
- Revenue forecasting using formulas
- Data-driven investment strategy formulation
- Data storytelling through charts and summaries
---
## 🔗 Resources
- [NYC Airbnb Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)
- [Final Project Workbook](https://docs.google.com/spreadsheets/d/1QFZ13Zlo8oKNHVcgCdZ9M411eoY5uoicV6C6gsH0Wsk/edit?usp=sharing)
