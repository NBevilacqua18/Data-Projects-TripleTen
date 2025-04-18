# 🚖 Zuber Ride-Sharing Analysis
---
## 🧑‍🎓 Role
**Junior Business Intelligence Analyst**
---
## 📌 Project Overview
In this project, I worked as a data analyst for **Zuber**, a new ride-sharing company entering the Chicago market, I explored real-world taxi data to uncover insights that could guide strategic business decisions.
The analysis focused on two primary objectives:
1. **Exploratory Data Analysis (EDA)** – Understanding ride volume patterns across different taxi companies and date ranges.
2. **Hypothesis Testing** – Investigating whether weather conditions affect the duration of rides between two key neighborhoods: **The Loop** and **O’Hare International Airport**.
---
## 🛢️ The Zuber Database
You're working as an analyst for **Zuber**, a new ride-sharing company that's launching in Chicago. Your task is to find patterns in the available information. You want to understand passenger preferences and the impact of external factors on rides.
You'll study a database, analyze data from competitors, and investigate the impact of weather on ride frequency.
### 🗃️ Description of the Data
The database includes information about taxi rides in Chicago, split across four main tables:
#### `neighborhoods` table
- `name`: name of the neighborhood  
- `neighborhood_id`: neighborhood code  
#### `cabs` table
- `cab_id`: vehicle code  
- `vehicle_id`: the vehicle's technical ID  
- `company_name`: the company that owns the vehicle  
#### `trips` table
- `trip_id`: ride code  
- `cab_id`: code of the vehicle operating the ride  
- `start_ts`: date and time of the beginning of the ride (time rounded to the hour)  
- `end_ts`: date and time of the end of the ride (time rounded to the hour)  
- `duration_seconds`: ride duration in seconds  
- `distance_miles`: ride distance in miles  
- `pickup_location_id`: pickup neighborhood code  
- `dropoff_location_id`: dropoff neighborhood code  
#### `weather_records` table
- `record_id`: weather record code  
- `ts`: record date and time (time rounded to the hour)  
- `temperature`: temperature when the record was taken  
- `description`: brief description of weather conditions, e.g. `"light rain"` or `"scattered clouds"`  
> 💡 **Note:** There isn't a direct connection between the `trips` and `weather_records` tables. However, you can JOIN them using the time a ride started (`trips.start_ts`) and the time the weather record was taken (`weather_records.ts`).
---
## 📊 Tasks and Structure
You’ve already completed the first part of the project: writing code to parse weather data from a website. This report covers the second and third parts of the project:
### 🔍 Tasks 1–4: Exploratory Data Analysis (EDA)
- Count ride volume per company across specific date ranges
- Filter companies by name (e.g., "Yellow", "Blue")
- Aggregate and group competitors by popularity
- Rank companies by number of rides
### 🌧️ Tasks 5–7: Hypothesis Testing
- Classify weather as `"Bad"` (rain/storm) or `"Good"`
- Filter rides from **The Loop (ID: 50)** to **O'Hare (ID: 63)** on **Saturdays**
- Compare ride duration under varying weather conditions
---
## 🧠 Business Context
**Zuber** is preparing for launch in Chicago and wants to understand:
- What taxi usage patterns exist in the city?
- Which companies dominate ride volume?
- How does **weather**, particularly **rainy Saturdays**, affect ride duration on high-traffic routes?
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
- **SQL**  
- Data filtering, aggregation, and joins  
- Conditional logic using `CASE`  
- Time-based data slicing  
- Hypothesis testing using grouped data  
- Real-world relational schema analysis
---
## 📁 Project Files
- 📄 SQL Queries & Notes: [Queries](https://tripleten.com/trainer/bi-analyst/lesson/32ddb20e-3ada-4aea-88d7-3ba42f2bd09c/task/d102902d-9759-41d6-8121-d35db6e9b511/)
- 🧾 Query Output and Insights Summary
---
## 📅 Completion Date
**December 2024**
---
## 📚 Learning Outcomes
- Gained hands-on experience querying relational databases.
- Learned to translate vague business hypotheses into precise SQL logic.
- Developed storytelling skills through real-world business data analysis.
---
