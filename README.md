📊 Vendor Performance & Inventory Optimization Analytics

📌 Project Overview
This project presents a complete end-to-end Data Analytics workflow focused on supply chain and retail inventory management. The objective is to transform raw procurement and sales data into actionable business insights that improve vendor selection, inventory turnover, and overall profitability. By consolidating six distinct datasets (begin_inventory, end_inventory, purchases, purchase_prices, sales, vendor_invoice), this project explores stock movement, profit margins, freight costs, and unsold inventory value. The project simulates a real-world scenario where management needs to understand: Which vendors yield the highest profit margins? What is the stock turnover rate per brand? Where is capital tied up in unsold inventory?

🛠️ Tools & Technologies Used
SQL (SQL Server) – Database storage, initial data loading, and relational management of the six core CSV files.
Python (Pandas, PyODBC, SQLAlchemy) – Database connection, data extraction, complex aggregations, and feature engineering (calculating profitability and turnover metrics).
Power BI – Interactive dashboard creation and visual data storytelling.
GitHub – Project documentation and version control.

🔍 Project Workflow
1️⃣ Data Preparation & Integration (SQL Server & Python)
Loaded 6 raw CSV datasets into SQL Server.
Established an ODBC connection using Python (pyodbc) to extract and merge the data in Jupyter Notebook.
Handled missing values and standardized product descriptions.

2️⃣ Feature Engineering & Business Modeling (Python)
Grouped data at the vendor and brand level to calculate aggregated performance.
Engineered critical business metrics including:
Gross Profit & Profit Margin: To assess the financial viability of each vendor.
Stock Turnover & Sales-to-Purchase Ratio: To measure how efficiently inventory is being sold.
Unsold Inventory Value: To identify tied-up capital and overstocked items.
Exported the finalized, clean dataset (vendor_sales_summary.csv) for visualization.

3️⃣ Dashboard & Visualization (Power BI)
Connected the structured summary data to Power BI to build an interactive dashboard presenting:
Vendor Profitability Rankings
Inventory Turnover Trends
Freight Cost vs. Gross Profit Analysis
Unsold Inventory Risk Assessment

📈 Key Insights
High-volume vendors do not always yield the highest profit margins due to underlying freight and excise tax costs.
Specific brands demonstrate high stock turnover, indicating strong market demand that justifies larger order sizes.
A measurable portion of capital is locked in unsold inventory for low-turnover brands, negatively impacting cash flow.

💡 Business Recommendations
Negotiate better freight terms or volume discounts with high-performing, high-cost vendors.
Optimize procurement by reallocating budget from low-turnover brands to high-turnover, high-margin products.
Implement targeted promotions or markdowns to liquidate high-value unsold inventory.

🎯 Project Outcome
This project demonstrates the ability to:
✔ Manage and integrate multi-table relational databases using SQL Server.
✔ Perform advanced data manipulation and financial feature engineering using Python.
✔ Build executive-level Power BI dashboards for supply chain optimization.
✔ Translate inventory metrics into strategic business recommendations.
