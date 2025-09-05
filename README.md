# pizza_sales_data

PROJECT OVERVIEW

This Project analyzes the 2015 pizza sales dataset (~48620 records) to evaluate business performance and customer behavior. The dataset includes order details such as pizza name, category, pizza size, quantity, price and order date, enabling calculation of key KPIs like revenue, order and avg order value.

The objective is to:
• Calculate Key Performance Indicators (KPIs)
• Perform data cleaning, transformation, and exploratory analysis
• Build interactive dashboards using Excel, Python, and Power BI
• Identify top-selling pizzas, peak order times, and customer preferences


📂 Dataset
Source: Pizza Sales Data (CSV format)
Dataset Link: https://github.com/VishlParmar/pizza_sales_data

Records: ~48620 rows
Columns: pizza_id, order_id, pizza_name_id, quantity, order_date, order_time, unit_price, total_price, pizza_size, pizza_category, pizza_ingredients, pizza_name


🔧 Data Processing

🧹 Data Cleaning & Transformation

• Standardized pizza sizes (M, L, S, XL → Medium, Large, Small, X-Large).
• Added new column Order Day for weekday analysis.
• Handled missing values & ensured consistency in categorical fields.



🔢 Unique Order Count
• Identified distinct order IDs.
• Calculated Total Orders and linked them with sales revenue.



📊 Key Performance Indicators (KPIs)

• Total Revenue – Total amount generated from pizza sales.
• Extract Year, Month, Weekday, Hour.
• Total Pizzas Sold – Number of pizzas sold.
• Total Orders – Unique orders placed.

1. Python (Jupyter Notebook)

Libraries Used: Pandas, Matplotlib, Seaborn, Plotly.

👉 Python Notebook Link: https://github.com/VishlParmar/pizza_sales_data

Steps:
• Data loading & cleaning with Pandas.
• EDA (Exploratory Data Analysis) with advanced visualizations.
• Interactive plots with Plotly (time series, category analysis).

 Data Visualization Images:

• Bar Chart by Monthly Revenue
• Line Chart by Hourly Trend
• Donut Chart for Pizza Size by Pizza Category
• Bar Chart for Top 5 Best Selling Pizza
• Donut Chart for Pizza Size by Pizza Category
• Gauge Chart by Category Indicator
• Cards: Total Revenue, Total Orders, Avg Price, Total Pizza Orders

2. Power BI Dashboard

🧹 Features:

• Interactive slicers (Date, Category, Size).
• KPI Cards (Revenue, Orders, AOV).
• Dynamic bar/line charts for sales trends.
• Customer preference insights by time & category.

🧹 Insights:

• Best-selling pizza categories by revenue.
• Peak sales hours & weekdays.
• Contribution of pizza sizes to total revenue.

👉 Power BI Dashboard Link: https://github.com/VishlParmar/pizza_sales_data


🛠️ Tools & Technologies Used

• Microsoft Excel → Data cleaning, KPI calculation, and visualization.
• Python → Pandas, Matplotlib, Seaborn, Plotly for EDA & visualization.
• Power BI → Interactive dashboard creation with slicers & KPIs.


🧹 Conclusion:

The analysis reveals clear trends in customer demand, peak sales hours and product performance, helping the restaurant optimize inventory and marketing strategies. By leveraging Excel, Python and Power BI, the project demonstrate a strong multi-tool approch to data analytics and provides actionable insights for better decision-making.
