# Part 4: Tableau Executive Dashboard & Data Storytelling

## Business Problem Summary

The retail leadership team requires an executive dashboard to monitor overall business performance across sales, profitability, customer segments, product categories, shipping performance, discount effectiveness, and return behavior.

The objective is to provide decision-makers with a single dashboard that highlights business opportunities, operational risks, and areas requiring management attention.

---

## Dataset Description

Dataset Used:

dashboard_sales_data.xlsx

The dataset contains retail transaction-level information including:

- Order Date
- Ship Date
- Region
- State
- City
- Category
- Sub Category
- Customer Segment
- Ship Mode
- Sales
- Profit
- Discount
- Quantity
- Customer Rating
- Delivery Days
- Return Flag

### Data Types Identified

#### Date Fields
- Order Date
- Ship Date

#### Geographic Fields
- Region
- State
- City

#### Categorical Fields
- Category
- Sub Category
- Customer Segment
- Ship Mode

#### Numerical Measures
- Sales
- Profit
- Quantity
- Discount
- Customer Rating
- Delivery Days

#### Binary Fields
- Return Flag

---

## Tableau Workbook Description

Workbook Name:

executive_dashboard.twbx

The workbook contains multiple analytical views and a consolidated executive dashboard designed for leadership-level decision making.

---

## Calculated Fields Created

### 1. Profit Margin

Formula:

Profit / Sales

Purpose:

Measures profitability relative to revenue generated.

---

### 2. Cost

Formula:

Sales - Profit

Purpose:

Estimates product cost contribution.

---

### 3. Average Order Value

Formula:

Sales / Number of Orders

Purpose:

Measures average revenue generated per order.

---

### 4. Return Rate

Formula:

Returned Orders / Total Orders

Purpose:

Measures return risk and product quality performance.

---

### 5. Shipping Delay Bucket

Categories:

- Fast
- Medium
- Slow

Purpose:

Classifies shipping performance into meaningful business groups.

---

## Dashboard Components

The dashboard includes the following analytical views:

### Sales Trend View

Shows sales performance over time using a line chart.

---

### Regional Performance View

Compares sales and profit across regions.

---

### Category Profitability View

Identifies profitable and underperforming product categories and sub-categories.

---

### Customer Segment View

Compares sales performance across customer segments.

---

### Shipping Performance View

Analyzes shipping efficiency and delivery performance.

---

### Discount vs Profit View

Examines the relationship between discount levels and profitability.

---

### Return Analysis View

Highlights return behavior across product categories and customer segments.

---

## KPI Cards Included

The dashboard includes the following executive KPIs:

- Total Sales
- Total Profit
- Profit Margin
- Return Rate

These KPIs provide leadership with an immediate overview of business performance.

---

## Filters and Interactions Used

Interactive filters included:

- Region
- Category
- Customer Segment
- Order Date

Dashboard interaction included:

- Region-based Action Filter

Users can click a region and dynamically filter the remaining dashboard views.

---

## Key Business Insights

### Insight 1

Sales show fluctuations across time, indicating seasonal demand patterns.

### Insight 2

Certain regions contribute significantly higher sales and profit than others.

### Insight 3

Some categories generate strong profitability while others reduce overall performance.

### Insight 4

Customer segments exhibit different purchasing behavior and revenue contribution.

### Insight 5

Higher discounts may negatively impact profitability.

### Insight 6

Shipping performance varies across shipping modes.

### Insight 7

Returns are concentrated in specific product categories.

### Insight 8

The business has opportunities to improve profitability through discount optimization and category management.

---

## Dashboard Story Summary

The executive dashboard provides a comprehensive overview of retail performance.

The analysis shows that sales growth is driven by a combination of regional performance, product category profitability, customer behavior, and operational efficiency.

While some areas demonstrate strong performance, others reveal opportunities for improvement through better pricing strategy, return reduction initiatives, and shipping optimization.

The dashboard supports data-driven decision making and enables leadership to quickly identify business risks and growth opportunities.

---

## Assumptions

- Sales and Profit values are presented in USD.
- Return Flag is treated as a binary indicator where:
  - 1 = Returned
  - 0 = Not Returned
- Delivery Days accurately represents shipping duration.
- Historical data is representative of overall business performance.

---

## Limitations

- The dashboard is based on historical data only.
- Results show business patterns but do not establish causation.
- Analysis quality depends on the completeness and accuracy of the provided dataset.
- External market factors are not included in the dashboard.

---

## Screenshots Included

The repository contains the following screenshots:

- full_dashboard.png
- sales_trend_view.png
- regional_performance_view.png
- category_profitability_view.png
- filter_interaction_view.png

---

## Files Included in Repository

### Data

- dashboard_sales_data.xlsx

### Tableau

- executive_dashboard.twbx

### Outputs

- business_insights.md
- dashboard_story.md
- chart_selection_justification.md

### Screenshots

- full_dashboard.png
- sales_trend_view.png
- regional_performance_view.png
- category_profitability_view.png
- filter_interaction_view.png

---

## Final Recommendation

Leadership should continue monitoring profitability alongside revenue growth. Particular focus should be placed on:

- Expanding high-performing regions
- Improving low-profit categories
- Optimizing discount strategies
- Reducing return rates
- Improving shipping efficiency

The dashboard should be used as an ongoing performance monitoring tool to support strategic business decisions.
