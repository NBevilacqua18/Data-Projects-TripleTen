# 🛒 Business Analytics Project: Turning Event Logs into Business Metrics
## 🧑‍🎓 Role
**Junior Business Intelligence Analyst**
---
## 📌 Project Overview
As part of **Sprint 3** of the TripleTen Business Intelligence Program, I was tasked with conducting an end-to-end business analytics project using raw transactional event logs from a fictional **e-commerce company**.
The dataset captured detailed user activities such as product views, cart interactions, and purchases. My goal was to turn this raw event data into clear, actionable business metrics — from a **conversion funnel** to **cohort retention analysis** — and present the insights in a well-organized, executive-ready spreadsheet report.
---
## 📊 Key Objectives
1. **Build a Conversion Funnel**  
   Analyze user flow from product views to purchases to identify drop-off rates and total conversion efficiency.
2. **Prepare Data for Cohort Analysis**  
   Track customer purchase behavior across monthly cohorts and measure engagement over time.
3. **Calculate Retention Rates**  
   Determine user retention for each cohort across four months following their first purchase.
4. **Organize & Document**  
   Polish the spreadsheet with summaries, explanations, and formatting for presentation to executive stakeholders.
---
## 📁 Dataset Description
The dataset was provided via the `raw_user_activity` tab in a Google Spreadsheet and included:
| Column Name       | Description                                         |
|-------------------|-----------------------------------------------------|
| `user_id`         | Unique identifier for each user                     |
| `event_type`      | Type of event (view, cart, purchase)                |
| `category_code`   | Product category (hierarchical format)              |
| `brand`           | Brand associated with the product                   |
| `price`           | Product price (USD)                                 |
| `event_date`      | Date of the activity (YYYY-MM-DD format)           |
---
## 🔧 Project Components
### 1️⃣ Conversion Funnel (`conversion_funnel` sheet)
- Created a 3-stage funnel: **Product Views → Cart Opens → Purchases**
- Counted **unique users** per stage
- Calculated:
  - **Total conversion rate** from first to last step
  - **Step-by-step conversion rate**
### 2️⃣ Purchase Filtering (`purchase_activity` sheet)
- Filtered only rows with `event_type = purchase`
- Created helper columns for:
  - `first_purchase_date` using `VLOOKUP()`
  - `event_month` and `first_purchase_month` using `TEXT()`
  - `cohort_age` using `DATEDIF()`

### 3️⃣ First Purchase Summary (`first_purchase` sheet)
- Pivot table showing the **earliest purchase date** per user
- Used to assign users to acquisition cohorts
### 4️⃣ Cohort Analysis (`cohort_analysis` sheet)
- Created cohort groups by **first purchase month**
- Counted **unique users** per `cohort_age` across cohorts
### 5️⃣ Retention Rate Calculation (`retention_rates` sheet)
- Calculated retention as:  
  **retained users / cohort size** (excluding month 0)
- Retention shown for cohort ages **1–4 months**
### 6️⃣ Executive Summary
- Highlighted findings from:
  - **Conversion Funnel**: Where users dropped off
  - **Retention Rates**: Which cohorts stayed engaged over time
- Included methodology, assumptions, and data insights
### 7️⃣ Table of Contents
- Organized and documented each sheet's purpose and placement
- Structured the spreadsheet for executive readability
---
## 📊 Insights & Key Takeaways
- The largest user drop-off occurred **between product views and cart opens**, highlighting a key optimization opportunity.
- Average total **conversion rate** from views to purchases was **under 5%**.
- **Retention rates** steadily declined month over month, with the first cohort showing the highest retention at age 1.
- Most purchases were concentrated among a few top-performing months, underscoring the importance of early lifecycle engagement.
---
## 📚 Skills Applied
- Funnel analysis and cohort-based segmentation
- Advanced spreadsheet techniques (VLOOKUP, TEXT, DATEDIF, Pivot Tables)
- Metric design and retention modeling
- Business storytelling and executive reporting
- Spreadsheet documentation and formatting best practices
---
## 🗂 File Structure
| Sheet Name          | Description                                               |
|---------------------|-----------------------------------------------------------|
| `Table of Contents` | Organized index of all sheets with descriptions           |
| `Executive Summary` | High-level summary of insights and methodology            |
| `conversion_funnel` | Funnel stages and conversion metrics                      |
| `purchase_activity` | Filtered data with calculated columns for cohorting       |
| `first_purchase`    | Pivot showing each user's first purchase date             |
| `cohort_analysis`   | Unique user counts by cohort month and age                |
| `retention_rates`   | Retention percentages for cohorts age 1 to 4              |
| `raw_user_activity` | Original dataset with all user activity                   |
---
## 🗓 Completion Date
**Sprint 3 Completed – December 2024**
---
## 🔗 Submission Link
[🔗 View Google Sheets Project (View-Only Link)](https://docs.google.com/spreadsheets/d/1anwYjX51qRU3DX8KM4Q_Z7qsv0DYDHz6in5pueje3Vw/edit?usp=sharing)  
---
