# 🚖 Zuber Ride-Sharing Analysis – Sprint 2: Data Collection and Storage (SQL)
## 🧑‍🎓 Role
**Business Intelligence Analyst (TripleTen Student)**
## 📌 Project Overview
In this project, I applied my foundational SQL skills as part of **Sprint 2** in the TripleTen Business Intelligence program. Working as a data analyst for **Zuber**, a new ride-sharing company entering the Chicago market, I explored real-world taxi data to uncover insights that could guide strategic business decisions.
The analysis focused on two primary objectives:
1. **Exploratory Data Analysis (EDA)** – Understanding ride volume patterns across different taxi companies and date ranges.
2. **Hypothesis Testing** – Investigating whether weather conditions affect the duration of rides between two key neighborhoods: **The Loop** and **O’Hare International Airport**.
---
## 🧠 Business Context
**Zuber** is preparing for launch in Chicago and wants to understand:
- What taxi usage patterns exist in the city?
- Which companies dominate ride volume?
- How does **weather**, particularly **rainy Saturdays**, affect ride duration on high-traffic routes?
The goal of this project was to uncover insights using SQL queries on a relational database containing taxi ride, weather, and location data.
---
## 🗃️ Dataset Description
The project database included four key tables:
- **neighborhoods** – IDs and names of city neighborhoods
- **cabs** – Taxi vehicle IDs and their associated companies
- **trips** – Data on taxi rides (timestamps, distance, pickup/dropoff locations)
- **weather_records** – Hourly weather data including temperature and descriptive conditions
---

## 🧪 Analysis Tasks
### Step 1: Exploratory Data Analysis (EDA)
- 📊 Counted rides per taxi company for **Nov 15–16, 2017**
- 🔍 Filtered ride data for companies containing **"Yellow"** or **"Blue"** during **Nov 1–7, 2017**
- 🥇 Ranked the most popular companies in Nov 2017:  
  Grouped **Flash Cab** and **Taxi Affiliation Services** separately, others under "Other"
### Step 2: Weather-Based Hypothesis Testing
- 🌧️ Labeled weather as "Bad" (if description included "rain" or "storm") or "Good"
- 🚕 Filtered rides from **The Loop (ID: 50)** to **O’Hare (ID: 63)** on **Saturdays**
- 🔄 Joined trip data with weather conditions to compare ride durations between good and bad weather days
- 🕐 Focused on hourly-level analysis and only rides with valid weather data
---
## 📊 Key Insights
- **Flash Cab** and **Taxi Affiliation Services** led in ride volume across the analysis periods.
- The term “Yellow” dominated company names among high-volume operators.
- Ride durations from the Loop to O’Hare were noticeably **longer during bad weather on Saturdays**, supporting the hypothesis that poor weather impacts travel time.
---
## 💼 Business Recommendations
- **Zuber** should prepare for delays and longer service times during rainy weekends, especially on major routes like Loop–O’Hare.
- Consider surge pricing or driver incentives during **bad weather Saturdays** to maintain service efficiency.
- Benchmark Flash Cab and Taxi Affiliation Services' operations as models for achieving volume and reach.
---
## 🛠️ Tools & Skills Applied
- **SQL (PostgreSQL)**  
- Data filtering, aggregation, and joins  
- Conditional logic using `CASE`  
- Time-based data slicing  
- Hypothesis testing using grouped data  
- Real-world relational schema analysis
---
## 📁 Project Files
- 📄 SQL Queries & Notes: [Zuber SQL Project Report (PDF)](link-to-your-file) *(Replace with actual link)*
- 🧾 Query Output and Insights Summary
- ✅ Completed as part of TripleTen's Sprint 2 curriculum
---

## 📅 Completion Date
**November 2024**

---

## 📚 Learning Outcomes

- Gained hands-on experience querying relational databases.
- Learned to translate vague business hypotheses into precise SQL logic.
- Developed storytelling skills through real-world business data analysis.

---

## 🔗 Next Steps

Future sprints will build on this by introducing data visualization and reporting tools like Tableau and Power BI, allowing these SQL findings to be transformed into interactive dashboards and stakeholder-ready presentations.
