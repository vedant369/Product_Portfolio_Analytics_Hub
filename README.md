# Sub-Category Performance and Investment Prioritization Dashboard

A comprehensive interactive Tableau dashboard designed to guide strategic investment and resource allocation decisions across product sub-categories using data-driven insights.

## Overview

This dashboard provides retail management with an actionable tool to evaluate sub-category performance, identify growth opportunities, and flag potential risks. By analyzing relationships between sales, profit, discounting, and quantity sold, stakeholders can make informed decisions about marketing spend and product investment priorities.

## 🎯 Objective

The dashboard addresses a critical business need: **identifying which product sub-categories merit future investment and which should be reconsidered**. By synthesizing quarterly performance data with profitability metrics, the tool enables management to allocate resources strategically and optimize the product portfolio.

## 📊 Key Features

### Interactive Dashboard Components

- **KPI Summary Cards** – Five prominent metrics displayed at the top for quick assessment:
  - Profit Margin (Profit/Sales %)
  - Category Share of Sales
  - Quarter-over-Quarter Growth (Sales)
  - Total Units Sold
  - Average Discount Applied

- **Dynamic Visualizations** – Multiple charts tracking:
  - Quarterly performance by sub-category
  - Relationship between sales, profit, and discounting
  - Volume-to-profit conversion analysis
  - Growth and vulnerability trends

- **Interactive Controls**:
  - **Filter Action** – Drill down across all visualizations by selecting a sub-category
  - **Parameter Action** – Switch between quarters to compare performance over time
  - **Table Calculations** – Derived metrics for deeper analytical insights

### Executive Analysis Section

Below the visualizations, four critical questions are answered with specific data references:

1. **High Discount, Low Profit Paradox** – Identifies sub-categories where aggressive discounting boosts sales but erodes profitability
2. **Volume vs. Profit Mismatch** – Highlights sub-categories selling high quantities without proportional profit growth
3. **Strong Performers** – Recognizes sub-categories demonstrating balanced revenue, profitability, and stable growth
4. **Vulnerability Assessment** – Flags sub-categories showing concerning recent performance trends

## 📈 Data Source

- **Dataset**: Superstore (includes sales orders across multiple regions)
- **Key Columns**: Orders, Sales, Profits, Discounts, Quantity, Shipping Details
- **Scope**: Multi-region analysis across product sub-categories

## 🔍 Critical Business Questions Addressed

| Question | Purpose |
|----------|---------|
| Is there a sub-category where high discounting drives sales growth but hurts profitability? | Identify unsustainable pricing strategies |
| Which sub-category sells high quantity but lacks profit performance? | Find operational efficiency issues |
| Which sub-category demonstrates strong revenue, profitability, and stable growth? | Identify models for replication |
| Which sub-category appears most vulnerable based on recent trends? | Flag at-risk product lines for intervention |

## 📋 Required Metrics (KPI Section)

The dashboard prominently displays at least four of the following metrics as color-coded KPI cards:

- **Profit Margin**: (Profit ÷ Sales) × 100
- **Category Share of Sales**: Sub-category sales as a percentage of total sales
- **Quarter-over-Quarter Growth**: Sales or profit growth rate between quarters
- **Total Units Sold**: Aggregate quantity across the period
- **Average Discount Applied**: Mean discount percentage for the sub-category

## 🛠️ Interactivity & User Controls

### Filter Action
Select any sub-category to automatically update all dashboard visualizations, enabling focused analysis on specific product lines.

### Parameter Action
Switch between quarters to compare performance metrics across time periods and identify seasonal patterns or strategic shifts.

### Table Calculations
Derived metrics (e.g., profit efficiency ratios, discount-to-growth correlations) enable viewers to explore non-obvious relationships in the data.

## 🎓 Learning Outcomes

This project demonstrates:
- Advanced Tableau dashboard design and interactivity
- Multi-dimensional data analysis and visualization best practices
- Executive-level insight communication
- Strategic use of KPIs and performance metrics
- Interactive exploration of complex business relationships

## 📖 How to Use

1. **View the Dashboard**: Open the Tableau workbook in Tableau Desktop or Tableau Public
2. **Explore Sub-Categories**: Use the filter controls to focus on specific products
3. **Compare Time Periods**: Use the parameter action to switch between quarters
4. **Interpret KPIs**: Reference the color-coded metric cards for quick summary insights
5. **Read Analysis**: Review the executive summary section for strategic recommendations

## 📁 Files Included

- `SubCategory_Performance_Dashboard.twbx` – Main Tableau workbook
- `README.md` – This documentation file
- `Superstore dataset` – Source data files

## 🎯 Key Insights Example

The dashboard reveals patterns such as:
- **Sub-categories with discount dependency**: High discounts driving volume but compressing margins
- **Profitable niche players**: Lower volume, high-margin products that stabilize the portfolio
- **Growth leaders**: Strong sales growth paired with maintained profitability
- **At-risk categories**: Declining sales, margin compression, and unstable performance

## 🔧 Technical Specifications

- **Tool**: Tableau (Desktop or Public)
- **Data Source**: Superstore dataset (CSV/Excel format)
- **Compatibility**: Tableau 2020.2+
- **Interactivity**: Filter actions, parameter actions, table calculations

---

## 📝 Notes

This dashboard was developed to address a real-world business challenge in resource allocation and product portfolio management. All metrics are calculated from source data without manual adjustments, ensuring reproducibility and accuracy across reporting periods.
