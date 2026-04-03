# Sample Superstore – Tableau Data Visualization Project

This repository documents a Tableau-based data visualization project using the Sample Superstore dataset (2014–2017).  
The goal is to convert raw sales and profit data into clear, actionable business insights through interactive dashboards.

## Project Overview

The analysis focuses on questions such as:
- How have sales evolved over time across different product categories?
- What is the relationship between sales and profit?
- Which sub-categories drive revenue vs. profit?
- How do regions contribute to overall performance?
- How have discounting patterns changed over time?
- What does the distribution of profit look like at the transaction level?

All core visualizations were designed and built in **Tableau**.

## Tableau Visualizations

1. **Line Chart – Sales Over Time (2014–2017)**  
   Category-wise sales trends across years, highlighting growth acceleration after 2015 and the strong performance of Technology.

2. **Scatter Plot – Sales vs. Profit**  
   Relationship between sales and profit, surfacing outliers such as loss-making Furniture segments in specific regions.

3. **Bar Chart – Category & Sub‑category Analysis**  
   Sales and profit by category/sub-category, identifying high-volume and high-margin products as well as loss-making segments.

4. **Pie Chart – Region-wise Contribution**  
   Regional contribution to total revenue and profit, showing the dominance of West and East and underperformance in South.

5. **Trend Line – Discount Patterns**  
   Discount levels over time, especially for Office Supplies, and their implications for sales growth and margin pressure.

6. **Histogram – Profit Distribution**  
   Distribution of profit per transaction, showing clustering near break-even and a few large positive/negative outliers.

## Key Insights (High Level)

- Technology and Office Supplies drive strong sales growth, particularly in East and West.  
- Several Furniture sub‑categories (e.g., tables, bookcases) are consistently unprofitable.  
- Discounting has increased over time, supporting revenue but compressing margins.  
- Profitability is volatile at the order level, with many low-margin transactions.

## Tools and Technologies

- **Visualization Tool:** Tableau  
- **Dataset:** Sample Superstore (2014–2017)  
- **Tasks:** Data preparation, Tableau dashboard design, exploratory analysis, and business interpretation  


## How to View the Dashboards

1. Open the Tableau workbook in the `tableau/` folder using Tableau Desktop or Tableau Public.
2. Navigate through the different dashboards:
   - Sales Over Time
   - Sales vs Profit
   - Category/Sub-category Analysis
   - Region-wise Performance
   - Discount Trends
   - Profit Distribution
3. Use filters and interactive controls to explore the data further.


## Demo Image

<img width="1006" height="813" alt="img" src="https://github.com/user-attachments/assets/e9dc74e9-601e-46c6-b2e9-7fe389e428a7" />



## Possible Extensions

- Add calculated fields for customer segmentation and cohort analysis.  
- Integrate forecasting within Tableau to project future sales and profit.  
- Publish dashboards to Tableau Public or Server for broader stakeholder access.

---

If you find this project useful or have suggestions for improvement, feel free to open an issue or submit a pull request.
