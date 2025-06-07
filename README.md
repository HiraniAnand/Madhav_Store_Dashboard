
# Madhav E-Commerce Sales Dashboard

![App Screenshot]()

## Problem Statement

This Power BI dashboard helps **Madhav E-Commerce Store** analyze and visualize its sales performance data. It enables the business to:

- Track **total revenue, profit** and **quantity sold**.
- Understand **customer behavior** and **payment patterns**.
- Identify **top-performing product categories** and **sub-categories**.
- Analyze **sales trends** across **months** and **states**.
- Optimize marketing and sales strategies based on data-driven insights.

By using this dashboard, Madhav Store can make informed decisions to improve profitability, enhance customer experience, and expand sales.

## Steps Followed
- **Step 1**: Loaded sales dataset into **Power BI Desktop** (source: CSV / Excel).
- **Step 2**: Opened **Power Query Editor** for data cleaning and transformation.
    - Checked for **null values, duplicates** and **column data types**.
- **Step 3**: Performed **basic data cleaning**:
    - Removed duplicates.
    - Handled nulls where necessary.
    - Created calculated columns as needed.
- **Step 4**: Set up a **theme** and consistent **color palette** for the report.
- **Step 5**: Created key **metrics** using Card visuals:
    - Sum of Amount
    - Sum of Quantity
    - Sum of Profit
    - Average Order Value (AOV)
- **Step 6**: Built various **visualizations**:
    - **Bar Chart** → Sum of Amount by State.
    - **Donut Chart** → Sum of Quantity by Product Category.
    - **Column Chart** → Profit by Month.
    - **Bar Chart** → Sum of Profit by Sub-Category.
    - **Cloumn Chart** → Sum of Amount by Customer Name.
    - **Donut Chart** → Sum of Quantity by Payment Mode.
- **Step 7**: Added **slicers** for interactivity:
    - Quarter Selection
    - State Selection
- **Step 8**: Published the report to **Power BI Service** for sharing and collaboration.

## Insights

#### 1️⃣ Key Metrics
| Metric                    | Value   |
| ------------------------- | ------- |
| Sum of Amount             | 438K    |
| Sum of Quantity           | 5615    |
| Sum of Profit             | 37K     |
| Average Order Value (AOV) | 121.01K |

#### 2️⃣ Sales Analysis
- **By State**:
    - **Top States by Sales**:
        - Maharashtra
        - Madhya Pradesh
        - Uttar Pradesh

- **By Month**:
    - **Sales peaks in**:
        - January
        - March
        - December
    - **Profit dips in**:
        - June
        - July
        - September

- **By Category**:
    - **Clothing** → 63% of quantity sold.
    - **Electronics** → 21%.
    - **Furniture** → 17%.

- **By Sub-Category (Top Profitable)**:
    - Printers
    - Bookcases
    - Saree
    - Accessories
    - Tables

- **By Customer**:

    **Harivansh** and **Madhav** are among the top customers by amount spent.

- **By Payment Mode**:
    - **Cash on Delivery (COD)** → 44% of quantity sold.
    - **UPI** → 21%.
    - **Debit Card** → 13%.
    - **Credit Card** → 12%.
    - **EMI** → 10%.

## Business Recommendations
- Optimize COD and UPI flows, as they are the most used payment modes.
- Focus marketing campaigns on Clothing and Electronics, which drive the most sales.
- Increase customer loyalty by identifying and rewarding top customers.
- Target underperforming months (June - September) with promotional campaigns.
- Monitor state-wise trends to identify growth opportunities in less active states.

## Future Improvements
- Add customer demographic analysis (Age, Gender, Location).
- Integrate time series forecasting for sales.
- Implement RFM segmentation for customer retention.
- Add a Profitability Heatmap by product and region.

## Conclusion
A single-page interactive Power BI dashboard was created to help **Madhav E-Commerce** gain visibility into its sales data. This dashboard serves as a foundation for making **data-driven business decisions**.
