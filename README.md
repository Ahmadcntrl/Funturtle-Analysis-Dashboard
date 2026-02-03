# Sales Analysis Dashboard - Funturtle
## 📊 Project Overview
This project features a multi-page interactive Power BI dashboard designed for Funturtle. It provides a deep dive into sales performance, profitability, and operational costs across different market segments, countries, and product lines for the period of September 2021 to December 2022.The dashboard is designed to transition from high-level executive summaries to granular, row-level data, allowing stakeholders to identify growth opportunities and cost inefficiencies.

## 📈 Key Insights & Analysis
### 1. Executive Summary (The Big Picture)Total 
- Net Sales: $118.73MTotal 
- Profit: $16.89M (Profit Margin: 14.23%)
- Total Units Sold: 1.13M
- Cost Efficiency: The Cost of Goods Sold (COGS) stands at $101.83M. With a gross profit of $127.93M, the business maintains a healthy spread, though heavy discounting ($9.2M) is a factor to watch.
### 2. Temporal Trends (Analysis Tab)
- Seasonality: Sales and profits show significant volatility. There is a notable peak in October 2021 and December 2021, followed by a dip in early 2022.
- Growth Spike: The "Profit by Month" chart indicates a massive recovery trend toward the end of 2022, with a relative profit increase of 235.58% in the most recent periods shown.
### 3. Segment Performance
- Government Sector: This is the primary driver of volume, accounting for the highest Units Sold (~0.47M) and Net Sales ($53M).
- Small Business: Despite lower volume than Government, it contributes significantly to the profit pool.
- Enterprise Challenge: The Enterprise segment shows a negative profit margin (-3.13%) in certain views, suggesting that the cost of acquisition or COGS for these large-scale contracts may be too high.
### 4. Geographical Distribution
- Top Performer: The USA and Canada lead in Net Sales ($25M each).
- Profitability Leader: France and Germany show strong profit contributions despite slightly lower sales volumes than the USA, indicating better margin control in European markets.
### 5. Product Analysis
- The Flagship: Paseo is the clear winner in volume (0.34M units) and Net Sales ($33M).
- High Margin: Products like Amarilla and Carretera show strong profitability.
- Discount Impact: High discount bands are frequently applied to "VTT" and "Velo," which correlates with tighter margins for those specific lines.
## 🛠️ Dashboard Architecture
The report is organized into six functional areas:
<img width="582" height="258" alt="image" src="https://github.com/user-attachments/assets/4af6d0d4-cd1d-453e-b13e-d4366bf84cac" />

## 🚀 How to Use
- Filters: Use the top slicers to filter by Discount Band (None, Low, Medium, High) to see how aggressive pricing affects the bottom line.
- Navigation: Use the left-hand sidebar to toggle between different analytical lenses.
- Drill-Down: On the "Product" and "Country" pages, hover over charts to see specific data points or use the table at the bottom for raw figures.
## 📂 Technologies Used
- Power BI Desktop: For data modeling and visualization.
- DAX (Data Analysis Expressions): For calculating YOY growth, profit margins, and dynamic KPIs.
- Power Query: For ETL (Extract, Transform, Load) processes.
