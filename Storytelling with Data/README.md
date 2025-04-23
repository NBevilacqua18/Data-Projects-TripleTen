# 📊 Superstore Returns Analysis
---
## 📌 Project Overview
This project was completed as part of **Storytelling with Data** in the **TripleTen Business Intelligence Program**.
As a **BI Analyst consultant** for a **Superstore**, I was tasked with identifying **root causes** behind the store’s **high volume of returned orders** and presenting a **story-driven dashboard** for the CEO. The analysis involved Tableau visualizations, a dashboard for monitoring returns, and a structured narrative that guides the CEO through the data insights.
---
## 📁 Project Link
👉 **[View Tableau Story and Dashboard on Tableau Public](https://public.tableau.com/views/StorytellingwithData_17381914730120/Story?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**  
---
## 🗃️ Dataset Description
- Source: `Superstore.xls` dataset, supplemented by the `Returns` table.
- **LEFT JOIN** between `Orders` and `Returns` to ensure inclusion of all orders, with or without returns.
- Created a calculated field:  
  - `Returned = IFNULL(Returned, 0)` for numeric analysis of return rates.
- Key fields used:
  - Product ID, Product Name, Subcategory, Category
  - Customer ID, Region, State, City
  - Sales, Profit, Order Date
  - Returned (Yes/No/null)
---
## 🧠 Analysis Summary
### 📍 Part 1: Root Cause Analysis of Returns
Created multiple **worksheets** to uncover the causes behind returned orders:
- **Scatterplot**: Correlation between **total sales** and **total returns** (aggregated by subcategory).
- **Bar Chart**: Return rate across **product categories**.
- **Customer-Level Returns**: Identified high-return customers (filtered to those with >1 order).
- **Geographic Heatmap**: Return rate distribution across **states**.
- **Seasonal Analysis**: Return rates by **month** to explore seasonality.
- **Composite Charts**: Two mixed-factor visuals (e.g., combining product category, region, and time) for deeper analysis.
---
## 🖥️ Part 2: Dashboard Design and Construction
- Developed **three low-fidelity dashboard mockups** (pen-and-paper sketches).
- Selected the best mockup to implement in **Tableau**.
- Built the **dashboard template** with empty containers.
- Finalized the **Returns Monitoring Dashboard**:
  - Included key visualizations
  - Added filters for interactivity (e.g., by date, product category, region)
  - Designed for executive decision-making
---
## 🎬 Part 3: Story Arc and Presentation
- Constructed a **Tableau Story** to guide stakeholders through the analysis:
  - **Summary of findings**: High-level insights on return patterns
  - **Measurement discussion**: Evaluated different return metrics (rate, total returns, cost of returns)
  - **Root causes identified**: Insights from customer, product, geographic, and seasonal trends
  - **Dashboard walkthrough**: Explanation of how to use and interpret the dashboard
  - **Recommendations and next steps**: Suggested actions based on insights
- Prepared and submitted a **3-5 minute screen-recorded presentation** of the Tableau Story.
---
## 📌 Key Business Insights
- **Certain subcategories** (e.g., technology accessories) had both high sales and high return rates, indicating **quality issues**.
- Return rates varied significantly by **region**, with some **states** having notably higher rates.
- **Seasonality** affected returns, with spikes during **holiday months** (November-December).
- A **small group of customers** accounted for a disproportionately high number of returns.
---
## 📚 Skills Demonstrated
- Story-driven data analysis and dashboard development in **Tableau**.
- **Return rate modeling** and identifying business risk factors.
- Dashboard prototyping (low-fidelity mockups) and design.
- Data storytelling and stakeholder communication.
- Interactive data visualization techniques (heatmaps, scatterplots, composite charts).
---
## 📂 Project Deliverables
- ✅ Tableau Workbook (`.twbx` file)
- ✅ Tableau Public Link (see above)
- ✅ Dashboard mockups (3 variations) and final template screenshots
- ✅ Screen-recorded or PDF presentation of Tableau Story
- ✅ `README.md` file (this document)
- ✅ ZIP archive containing all project files (under 9 MB)
---
## 🗓 Completion Date
**March 2025**
---
## ✅ Summary
This project demonstrated how **data storytelling** and **visualization** can guide executive decision-making. Through Tableau dashboards and narrative techniques, I presented key findings and actionable insights to address **high return rates** at the Superstore. The resulting dashboard serves as an ongoing **monitoring tool** for reducing returns and improving profitability.
