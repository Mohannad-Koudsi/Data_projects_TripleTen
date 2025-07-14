# 🏙 NYC Airbnb Market Analysis

## 🧠 Problem
A real estate client needed data-backed recommendations for which types of Manhattan properties to invest in for vacation rentals.

## 🎯 Project Goal
Use Airbnb listing and calendar data to identify:
- The most attractive neighborhoods
- The most popular property sizes
- Revenue potential of top listings

## 🛠 Tools Used
- Google Sheets
- Pivot Tables
- Data Cleaning Functions (IF, SUMIF, VLOOKUP)

## 📊 Key Insights

### Neighborhood Attractiveness
Using number of reviews in the last 12 months as a proxy for popularity:
- **Top 3 neighborhoods**: Lower East Side, Hell's Kitchen, Harlem
- Cleaned neighborhood names using a new column `neighborhood_clean`

### Property Size Popularity
- Most common property sizes were:
  - **1-bedrooms** (1,265 listings)
  - **Studios** (441)
  - **2-bedrooms** (526)
- Harlem showed highest preference for **1-bedroom** units.

### Revenue Analysis
- Created a `top_listing` flag for matching neighborhood + size
- Joined listing data with calendar data
- Calculated revenue using `adjusted_price * rented_days` (filtered for availability = "f")
- **Top listing ID:** `49946551` earned **$29,940** in 30 days → **~$359,280 annually**

## 💾 Deliverables
- Executive summary
- Data cleaning log
- Pivot tables
- Revenue estimation model

## 📈 Visuals
- Bar chart: Reviews by neighborhood
- Pivot table: Size popularity
- Revenue ranking of top listings

## ✅ Skills Demonstrated
- Spreadsheet-based data cleaning
- Pivot table mastery
- Logical thinking and business recommendations
