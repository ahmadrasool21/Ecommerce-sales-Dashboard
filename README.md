# Ecommerce-sales-Dashboard
📊 **Project Overview**
This Power BI project provides a comprehensive analysis of e-commerce sales data. The goal was to transform raw order and detail data into actionable insights, focusing on monthly profitability, regional performance, and customer segment behavior.

🎯 **Key Business Questions Answered:**
Which states and cities are driving the highest profits?

How does profitability fluctuate month-over-month?

Which product categories and sub-categories are the most/least profitable?

What are the preferred payment modes for customers?

🛠️ **Data Architecture**
The analysis is built using two primary datasets:

Orders Table: Contains high-level order information including Order ID, Date, Customer Name, State, and City.

Details Table: Contains granular line-item data including Amount, Profit, Quantity, Category, and Sub-Category.

Data Modeling
Relationship: Established a Many-to-One (*:1) relationship between Details and Orders using the Order ID column.

Data Cleaning: Performed Date Type conversion using Locale settings to ensure DD-MM-YYYY formats were correctly parsed for time-series analysis.

🚀 **Key Features**
KPI Cards: Instant visibility into total Profit, Quantity, and average order values.

Geographical Analysis: A breakdown of Profit by State (e.g., Maharashtra and Madhya Pradesh as top contributors).

Monthly Trends: A line chart visualizing profit fluctuations throughout the year.

Product Deep-Dive: Analysis of profit by Category (Clothing, Electronics, Furniture) and specific Sub-Categories (Printers, Bookcases, etc.).

Customer Segmentation: Breakdown of sales by Customer Name and Payment Mode.

💡 **Insights & Recommendations**
Top Performers: The Clothing category drives the highest volume, while Electronics (specifically Printers and Accessories) shows high profit margins.

Regional Focus: Maharashtra is the leading state in terms of total profit; marketing efforts should be scaled in underperforming regions like Punjab or Bihar.

Payment Trends: Cash on Delivery (COD) remains a dominant payment method, suggesting a need for robust logistics and return-handling processes.
