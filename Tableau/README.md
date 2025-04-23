# 📊 Superstore Data Visualization Project – Sprint 4 (Tableau)
## 🧑‍🎓 Role
**Junior Business Intelligence Analyst**
---
## 📌 Project Overview
This project was completed as part of **Sprint 4: Data Visualization with Tableau** in the TripleTen Business Intelligence Program.
I was brought in as a **consultant analyst** to evaluate the operations of a fictional **Superstore** on the verge of bankruptcy. Using Tableau, I built a series of interactive dashboards to analyze profit drivers, high-return products, advertising opportunities, and business risks — to improve profitability and strategic focus.
All visualizations were published to Tableau Public and used to support genuine business recommendations.
---
## 📁 Project Link
👉 **[View Tableau Dashboard on Tableau Public](https://public.tableau.com/app/profile/noah.bevilacqua/viz/TripleTenProject_17368988267210/Top3vs_Bottom3Subcategories)**  
---
## 📊 Project Dataset
- Source: `Superstore.xls` dataset
- Supplementary data: `Returns` table, LEFT JOINED to `Orders`
- Key variables used:
  - Product ID, Subcategory, Region, Shipping Mode
  - Order Date, Sales, Profit, Returned
  - Customer ID, Product Name, State
---
## 🧠 Analysis Summary
### 🟩 Part 1: Profits & Losses
- Identified the **top 2 profit centers** and **top 2 loss centers** using dimension pairs.
- Pinpointed **low-performing products** to discontinue.
- Selected **3 subcategories to prioritize** and **3 to eliminate**.
- 🔍 Tools: Bar charts, scatter plots, filters by subcategory and product ID.
### 📢 Part 2: Advertising Strategy
- Analyzed average monthly profits across states.
- Chose **3 best state/month pairs** for advertising based on **Return on Ad Spend (ROAS)**.
- Justified **budget recommendations** for ad spending (set to 1/5 of average monthly profits).
- 📅 Tools: Line charts, dual-axis visuals, map visualizations.
### 🔁 Part 3: Return Rate Analysis
- Joined Returns to Orders to identify:
  - Products with the **highest return rates**
  - Customers with **frequent returns**
- Created calculated field: `Returned = IFNULL(Returned, 0)` to ensure clean data.
- Built comparison visuals showing **average return rate vs average profit** across dimensions like product category and shipping mode.
- 🎯 Tools: Heat maps, calculated fields, dual-metric scatter plots.
---
## 📌 Key Business Insights
- High-return, low-profit products are costing the Superstore money — these should be phased out.
- The **Technology** and **Office Supplies** categories show strong margins and low returns.
- Advertising should be **concentrated in states with consistently high monthly profit trends** (e.g., California in December).
- Certain customers exhibit **high return behavior**, and may require special policies or segmentation.
---
## 📚 Skills Demonstrated
- Data joining and cleansing (LEFT JOIN, calculated fields)
- Interactive dashboards using Tableau Public
- Business performance segmentation
- Return on Ad Spend (ROAS) and profitability analysis
- Visual storytelling for stakeholder communication
---
## 📂 Project Deliverables
- ✅ `README.md` file (this document)
- ✅ Tableau Public Link (see above)
- ✅ Data files and supporting documents in ZIP archive
---
## 🗓 Completion Date
**Sprint 4 Completed – January 2025**
---
## 🧾 Summary
This project showcased my ability to use **Tableau** as a strategic analytics tool to uncover profit opportunities, flag inefficiencies, and support high-impact business decisions. It represents my first full-cycle visual analytics engagement as part of the TripleTen BI program.
📈 Through compelling visuals and clear logic, I demonstrated how data visualization drives real business action.
