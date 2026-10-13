# E-Commerce-Sales-analysis-using-Power-BI
📊 E-Commerce Sales and Profit Analysis Using Power BI
This project uses Power BI to organize e-commerce order data and analyze sales amounts, profits, product categories, and sales targets.
📑 Table of Contents
- Project Overview
- Data Sources & Architecture
- Data Transformation (ETL)
- Data Model & DAX
- Dashboard Features
- Key Insights
- How To Use
🎯 Project Overview
- Business Problem: It can be difficult to understand which product categories and sub-categories contribute to sales and profit when order information is stored across separate files.
- Objective: Clean and combine the available data, create summary tables, and make sales and profitability information easier to review in Power BI.
- Target Audience: Beginners learning data analysis, sales teams, and business users who want to explore order performance.
🗃️ Data Sources & Architecture
- Source Files: Three CSV files — List of Orders, Order Details, and Sales Target.
- Data Volume: The List of Orders table was limited to 500 rows for the assignment. The other tables use the records available in their source files.
- Storage Mode: Import mode.
- Tool: Microsoft Power BI Desktop.
⚙️ Data Transformation (ETL)
- Tool Used: Power Query Editor.
- Key Cleanups: Checked column quality, adjusted data types, formatted customer names, combined city and state into a Location column, and sorted or filtered records as required.
- Custom Columns: Added Profit Margin and Profit Status to support profitability analysis.
- Table Merge: Merged List of Orders and Order Details using Order ID to create Orders Data.
- Summary Tables: Created summaries for order count by category, average profit by category, and total amount by sub-category. Sales target data was also prepared for monthly/category analysis.
- Data Quality: Reviewed missing values and errors using Power Query's data profiling tools.
🧠 Data Model & DAX
- Model Type: A relationship-based model built from the available order, target, and summary tables.
- Main Tables: List of Orders, Order Details, Sales Target, and the merged Orders Data table.
- Summary Tables: Order Count, Average Profit by Category, and Total Amount by Subcategory.
- Relationships: Used relevant common columns, including Order ID, and reviewed relationships to avoid ambiguous paths.
- Calculated Fields: Profit Margin and Profit Status were created in Power Query. No DAX measures are listed here because their creation has not been confirmed.
🖥️ Dashboard Features
The data preparation supports the following analyses:
- Order Analysis: Review order records and order counts by category.
- Profit Analysis: Compare average profit by category and review profit status.
- Sub-category Analysis: Compare total amount across sub-categories.
- Location Analysis: Filter records by location, including state.
- Sales Target Analysis: Organize target values by month and category.
Note: Include screenshots or descriptions of charts, KPI cards, and report pages here only if you have actually created them.

💡 Key Insights
The summary tables are intended to help answer questions such as:
- Which categories have higher or lower average profit?
- Which sub-categories account for the largest total amount?
- Which records are profitable, loss-making, or break-even?
- How do sales targets vary by month and category?
Recommendation: Use the completed summaries and report visuals to identify categories or sub-categories that may need closer review. Add specific findings only after checking the actual results in Power BI.
🚀 How To Use
1. Prerequisites: Install Microsoft Power BI Desktop.
2. Open the Project: Open the saved .pbix file in Power BI Desktop.
3. Keep Source Files Available: Store the three CSV files in an accessible folder.
4. Update Paths if Needed: If Power BI cannot find the source files, update the file paths through Data source settings.
5. Refresh: Select Refresh to reload the data after source files are updated.
6. Explore: Review the transformed tables, summaries, relationships, and any report visuals included in the project.
