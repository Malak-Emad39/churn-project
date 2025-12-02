# 📊 Churn Analysis Dashboard – Source Code & Data Visualization

## 📁 Project Overview
This repository contains the source code, data, and visualizations for a customer churn analysis dashboard. The project aims to identify key factors influencing customer attrition and provide actionable insights through interactive charts and dashboards.

## 📈 Visualizations Included

### 1. *Total Customer and Churn Rate by Age (bins)*
   - Bar chart showing total customers per age group.
   - Overlay line chart displaying churn rate per age bin.
   - Highlights high-risk age groups (e.g., 45–50 with ~45% churn).

### 2. *Average Monthly Charge and Churn Rate by Customer Group*
   - Dual-axis chart:
     - Bars: Average monthly charge per customer group.
     - Line: Churn rate per group.
   - Shows correlation between higher monthly charges and increased churn.

### 3. *Churn by Demographics*
   - Pie/bar charts showing churn distribution by:
     - Gender (Female, Male, Prefer not to say)
     - Contract type (Monthly vs. Yearly)
   - Monthly churn: 46.29%, Yearly churn: 6.62%.

### 4. *Churn Rate by Account Length and Contract Type*
   - Stacked bar chart comparing churn rates for:
     - Month-to-Month
     - One Year
     - Two Year contracts
   - Binned by account length in months.

### 5. *Churn Rate by Payment Method*
   - Breakdown by:
     - Credit Card
     - Direct Debit
     - Paper Check
   - Shows churn rates for monthly and yearly billing cycles.

### 6. *Churn Rate by Data Consumption and Unlimited Plan*
   - Grouped bar chart comparing:
     - Customers with Unlimited Data Plan (Yes/No)
     - Grouped consumption levels:
       - Less than 5 GB
       - Between 5 and 10 GB
       - 10 GB or More
   - Churn rates displayed as percentages (6%, 39%, 55%).

## 🛠 Tech Stack
- *Frontend:* React.js / Vue.js / HTML5 + CSS3
- *Charts:* Chart.js / D3.js / Plotly
- *Backend (if applicable):* Python (Flask/Django) / Node.js
- *Data Processing:* Pandas, NumPy
- *Version Control:* Git & GitHub

## 📂 Repository Structure
