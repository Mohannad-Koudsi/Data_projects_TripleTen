# 📈 Cohort Retention Rate Analysis

## 🧠 Problem
The company needed to understand how well users were being retained over time and how behaviors varied by signup cohorts.

## 🎯 Project Goal
Build a conversion funnel and perform a cohort analysis to:
- Identify drop-off points in the user journey
- Track user retention over time
- Uncover patterns and suggest strategies for improvement

## 🛠 Tools Used
- Google Sheets
- Pivot Tables
- VLOOKUP, TEXT, DATEDIF
- Cohort logic and funnel modeling

## 🔍 Process Overview

### Part 1: Conversion Funnel
- Tracked unique users across 3 funnel stages:
  1. Product Views
  2. Cart Opens
  3. Purchases
- Calculated conversion rates for each stage and the overall conversion rate.

### Part 2: Cohort Setup
- Filtered `raw_user_activity` to only include purchases.
- Calculated each user’s first purchase date using a pivot table.
- Created new columns:
  - `event_month` (month of activity)
  - `first_purchase_month` (month of first purchase)
  - `cohort_age` (months since first purchase)

### Part 3: Retention Rate Calculation
- Built a cohort pivot table showing unique users by cohort and age.
- Created a retention matrix to visualize drop-off rates month over month.

### Part 4: Presentation & Summary
- Compiled results into an executive summary
- Organized the spreadsheet with tabs for raw data, calculations, results, and documentation
- Created a visual “cohort heatmap” for better communication

## 💡 Key Insights
- Clear drop-off in user activity after the first month
- Some cohorts had consistently higher retention than others
- Recommendations made for onboarding improvements and re-engagement strategies

## ✅ Deliverables
- Cohort tables with visual heatmap
- Funnel performance metrics
- Summary of assumptions and methodology

---

## 🔗 Cohort Retention Rate Project Link
*https://docs.google.com/spreadsheets/d/1joX1OplKcvF4GcA1_Ih-jTiMwNcKntT2tnI399fMccI/edit?usp=sharing*

---

## 🧠 Skills Demonstrated
- Spreadsheet modeling
- Cohort & funnel analysis
- Logical data manipulation
- Communicating data stories clearly

