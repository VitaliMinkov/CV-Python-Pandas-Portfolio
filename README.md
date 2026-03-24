## Python (Pandas, Numpy) Portfolio
This project is based on transactional retail data (orders, returns, customers, products) and focuses on solving core business and product analytics tasks using Python (Pandas, NumPy) on a real-world dataset. 

It covers the full analytical workflow — from raw data validation and preparation to advanced business insights and forecasting. It includes data cleaning, feature engineering, KPI design, segmentation, time series analysis, cohort analysis, and performance evaluation across multiple business dimensions.

# Key analytical tasks performed in the project
1. Data validation and quality checks (missing values, duplicates, logical and range validation)
2. Feature engineering (e.g., shipping duration calculation, loss flags)
3. Global KPI calculation (Sales, Profit, Profit Margin, AOV, Discount)
4. KPI breakdown by Region, Segment, Category, and Sub-Category
5. Loss and risk analysis (loss share, total loss, negative transaction rate)
6. Discount impact analysis (bucketization, profitability thresholds, correlation analysis)
7. Product analytics (sub-category performance, Pareto analysis, profit concentration)
8. Customer analytics (customer-level KPIs, top/loss-making customers)
9. RFM segmentation and segment-level profitability analysis
10. Time series analysis (monthly trends, MoM/YoY growth, seasonality, anomaly detection)
11. Operational analysis (shipping performance, delivery speed vs profitability, return rate)
12. Cohort and retention analysis (customer retention, revenue retention, lifetime value dynamics)
13. Manager performance analysis (profit stability, risk concentration, contribution analysis)
14. Forecasting (trend-based sales and profit prediction, growth estimation)

# Key metrics used throughout the project
1. Sales, Profit, Profit Margin
2. Total Orders, Average Order Value (AOV), Average Discount
3. Loss Share, Total Loss, Percent of Negative Transactions
4. Profit Share, Sales Share
5. RFM metrics (Recency, Frequency, Monetary)
6. Retention Rate, Revenue Retention
7. MoM and YoY Growth
8. Shipping Days, Return Rate
9. Forecast Growth
   
# Main objective of the project
To demonstrate practical understanding and the ability to apply Python Pandas for real-world data analysis tasks, including:
1. Data loading and inspection (read_excel, shape, dtypes)
2. Data cleaning and validation (isna, duplicated, describe)
3. Column operations and feature engineering (vectorized operations, .dt, boolean flags)
4. Grouping and aggregation (groupby, agg)
5. Pivot tables (pivot_table)
6. Sorting and filtering (sort_values, boolean indexing)
7. Merging datasets (merge)
8. Reshaping data (unstack, to_frame)
9. Window-like operations and ranking (rank)
10. Binning and segmentation (pd.cut, pd.qcut)
11. Applying custom logic (apply, custom functions)
12. Time series operations (to_period, to_timestamp, pct_change)
13. Rolling calculations (rolling)
14. Correlation analysis (corr)
15. Cumulative calculations (cumsum)
16. Concatenation (concat)
17. Index operations and alignment
18. Basic visualization (plot, scatter, bar, pie)
19. Styling tables (style.background_gradient)
20. NumPy integration (np.arange, np.polyfit, np.poly1d)

Overall, the project demonstrates end-to-end analytical thinking: transforming raw transactional data into structured insights, identifying key profit drivers and risks, and supporting data-driven decision-making through quantitative analysis.


# How to Run .ipynb file
pip install -r requirements.txt
jupyter lab
