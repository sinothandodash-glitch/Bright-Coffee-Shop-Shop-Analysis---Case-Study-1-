# Bright-Coffee-Shop-Shop-Analysis Case Study 1

End-to-end sales analysis for Bright Coffee Shop: data processing in Databricks (SQL), pivot tables and charts in Excel, Miro project planning, and a CEO presentation with recommendations to grow revenue.

## 1. Overview
Bright Coffee Shop has appointed a new CEO whose mission is to grow revenue and improve product performance. As a Junior Data Analyst, my role was to analyse the "Bright Coffee Shop Sales" dataset, which captures daily transactional data from the coffee shop, and turn it into insights the CEO can act on.

The analysis set out to answer four questions:
- Which products generate the most revenue?
- What time of day does the store perform best?
- What are the sales trends across products and time intervals?
- How can sales performance be improved?

## 2. Approach
1. **Planning (Miro):** Designed a data flow and architecture diagram covering the data source, the ETL pipeline, storage in Databricks, and how the data is analysed and presented. Also listed the key insights to deliver and the calculations to perform.
2. **Data processing (Databricks + SQL):** Converted the Excel data to CSV and loaded it into Databricks. Then:
   - Created a `transaction_time_bucket` column to group transactions into [30-minute / 3-hour] intervals
   - Cast `unit_price` to a proper numeric type (some values used commas as decimals, e.g. `3,1` → `3.1`)
   - Calculated `total_amount = unit_price * transaction_qty`
   - Grouped the data by product type, product details and time bucket
3. **Analysis (Excel):** Exported the processed table to Excel and built pivot tables and charts for revenue, peak times, quantities sold and best sellers.
4. **Presentation:** Prepared a PowerPoint presentation for the CEO and a separate methodology document.

## 3. Key Insights
- **Top revenue products:** [product types/details and their revenue] - yet to initiate
- **Best-performing time of day:** [time intervals with the highest sales] - yet to initiate
- **Slowest time slots:** [time intervals with the lowest sales] - yet to initiate
- **Low-performing products:** [products/categories] - yet to initiate
- **Total revenue:** [amount] - yet to initiate
  
## Summary
[2–3 sentences wrapping up: what you did (processed the sales data in Databricks, analysed it in Excel, presented to the CEO) and the main thing you found (e.g. top product and peak time).] - yet to initiate

## 4. Recommendations
- Run marketing campaigns during slow time slots
- Stock more of the best-selling items
- Promote underperforming products

## 5. Next Steps
- Automate daily sales reporting
- Track sales performance across multiple locations in future
- Introduce loyalty programmes based on peak customer time slots

## 6. Tools Used
- **Miro** – project planning and architecture diagram - still busy
- **Databricks (SQL)** – data storage, transformation and analysis
- **Microsoft Excel** – pivot tables and charts
- **Microsoft PowerPoint** – presentation to the CEO
- **[Power BI / Looker Studio / Databricks dashboard]** – dashboard (if used)
- **GitHub** – version control and project documentation

## 7. Dashboard
[Add your dashboard link here, or a screenshot if it isn't public.] - yet to initiate
