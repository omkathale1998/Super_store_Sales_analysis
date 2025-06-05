# Super_store_Sales_analysis

# 🔍 Overview
This project analyzes sales data from a sample superstore to understand performance across various areas such as product categories, customer segments, and regions. The aim is to identify trends in sales and profit, discover which products or areas contribute most or least to revenue, and find opportunities to improve business strategy. The analysis involves exploring historical order data that includes information on order dates, customer location, product types, sales figures, profits, and applied discounts.

# 🧹 Data Preparation and Cleaning
The dataset was first loaded from a CSV file. Initial checks were done to understand its size, structure, and types of values it contained. Columns like order date were converted to proper date formats, and data types were verified for accuracy. Duplicate rows were removed to avoid skewed results, and unnecessary columns such as "Row_ID" and "Product ID" were dropped. The dataset had no missing values. To improve the analysis, new columns were created, such as "Profit Margin", "Month", and "Year", allowing deeper insights into trends over time and profitability. Some potential outliers, especially in the profit column, were also identified during this phase.

# 📊 Insights
- The Consumer segment had the highest number of orders and sales.
- Technology was the most profitable product category
- Office Supplies had high sales but relatively low profit margins.
- The West and East regions performed better in both sales and profit compared to other regions.
- Some states like Texas and Illinois had high sales but negative profits.
- High discounts often led to losses, showing that over-discounting is not sustainable.

# 💡 Recommendations
- Reconsider discount policies, especially in states or categories where they reduce profits.
- Promote and invest more in Technology products due to their high profitability.
- Focus on strengthening performance in high-profit regions like the West and East.
- Analyze loss-making states like Texas in more detail to improve operations.
- Use time-based trends (monthly and yearly) for better planning in inventory and sales strategy.

