# 📊 Data Visualization Project – Saving the Superstore

## 🧠 Problem
The Superstore is facing financial instability and needs actionable insights to boost profitability and avoid bankruptcy.

## 🎯 Project Goal
Leverage Tableau to build clear, insightful visualizations that identify:
- Profit and loss centers
- Products to stop or promote
- High-value advertising opportunities
- Risk areas related to returns

## 🛠 Tools Used
- Tableau
- Superstore dataset (`Superstore.xls`)
- Data joins (Orders + Returns)
- Calculated fields, aggregations, filters

---

## 🔍 Project Breakdown

### Part 1: Profits & Losses
- Identified best and worst-performing segments by subcategory, region, shipping mode, and product ID
- Highlighted underperforming products to phase out
- Recommended top 3 subcategories to focus on and 3 to remove

### Part 2: Advertising Insights
- Calculated average profit by state and month
- Selected 3 top-performing state+month pairs for ad spending
- Used ROI logic: suggested ad spend = 1/5 of expected profits

### Part 3: Returned Items
- Joined Returns data to Orders with LEFT JOIN
- Created binary "Returned" field (Yes = 1, null = 0)
- Built visualizations:
  - Top products & customers by return rate
  - Return rates by region, time, and shipping mode
  - Scatterplot of average profit vs. return rate

---

## 📈 Key Visualizations
- Bar chart: Profit by Subcategory
- Line chart: Monthly Profit Trends (by state)
- Map: Geographic Return Rate
- Scatterplot: Profit vs. Return Rate
- Customer segmentation based on return behavior

---

## 🔗 Tableau Public Link
*https://public.tableau.com/views/MohannadKoudsi-DataVisualizationproject/TopProfitLoss-Sub-Category?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link*

---


## ✅ Skills Demonstrated
- Dashboard design for storytelling
- Visual decision-making tools
- Data cleaning + joins
- ROI-based logic for business strategy
