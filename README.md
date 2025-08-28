# Retail Sales Dashboard: SQL Analysis 

This project demonstrates end-to-end data analysis using PostgreSQL for data aggregation and Tableau for dynamic visualizations. It simulates a retail sales dataset and explores performance across time, region, and product category, while generating business-ready insights.

## Tools Used
- **PostgreSQL (pgAdmin)** — Data storage, transformation, and querying
- **SQL** — Used to calculate key performance metrics
- **Tableau Public** — For creating dashboards and visualizing the output
- **GitHub** — For hosting code and CSVs for reproducibility

---

## Folder Structure

```
retail-sales-dashboard/
├── SQL/
│   └── retail_sales_analysis.sql
├── csv/
│   ├── monthly_trends.csv
│   ├── sales_by_region.csv
│   ├── sales_by_category.csv
│   ├── category_profit_margin.csv
│   └── customer_ltv.csv
├── tableau/
│   └── retail_sales_dashboard.twbx
└── README.md
```

---

## Insights Generated

### 1. **Monthly Trends**
- Total sales and profit per month
- Used for identifying seasonality or performance shifts

### 2. **Sales by Region**
- Compares sales and profitability across East, West, North, and South

### 3. **Sales by Product Category**
- Helps evaluate which categories drive the most revenue

### 4. **Category Profit Margins**
- Calculates profit margins (%) by category to assess profitability

### 5. **Customer Lifetime Value**
- Aggregates total sales and profit per customer to identify top-value clients

---

## Tableau Dashboard

The Tableau dashboard contains five core views, one per dataset:
- Monthly Trends
- Regional Sales Breakdown
- Category Performance
- Profit Margins
- Customer Lifetime Value

It is available on Tableau Public or can be opened via the included `.twbx` file.

---

## How to Reproduce

1. Run the SQL script in `SQL/retail_sales_analysis.sql` inside a PostgreSQL environment (e.g., pgAdmin)
2. Export the query results into CSVs
3. Load each CSV into Tableau as a separate data source
4. Build visualizations from each and organize them into dashboards
5. Save and publish to Tableau Public (optional)

---

## Sample Visuals

Include screenshots or a Tableau Public link here if desired.

---

## Future Improvements

- Replace synthetic data with real-world datasets
- Join customer or product dimension tables for deeper analysis
- Build an interactive Tableau dashboard with filters and tooltips




