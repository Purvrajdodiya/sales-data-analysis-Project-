Sales and Profitability Analysis Power BI Dashboard
This repository contains a Power BI dashboard that analyzes sales and profitability data from a variety of sources. The dashboard provides a comprehensive overview of the business's performance, allowing users to drill down into specific areas to identify trends and opportunities.

📖 Table of Contents
📖 Table of Contents

🚀 Introduction

❓ Key Business Questions

📊 Data Sources

🛠️ How to Use

️ Data Model

📈 Dashboard Components

📄 Disclaimer

🚀 Introduction
This Power BI dashboard is designed to provide a clear and concise overview of the company's sales and profitability. It allows users to:

Track key performance indicators (KPIs) such as sales, profit, and profit margin.

Analyze sales and profitability by customer, product, market, and date.

Identify the most and least profitable products and customers.

Understand the impact of discounts and promotions on profitability.

Monitor sales performance over time.

❓ Key Business Questions
The dashboard is designed to answer the following key business questions:

What are the company's overall sales and profitability?

Which products and customers are the most and least profitable?

What is the impact of discounts and promotions on profitability?

How does sales performance vary by region and market?

What are the sales and profitability trends over time?

Who are the top customers by sales and profit?

What is the sales and profitability breakdown by customer type (e.g., Brick & Mortar vs. E-Commerce)?

📊 Data Sources
The dashboard is based on the following data sources:

sales profit 4.csv: This file contains detailed information about each sale, including the product, customer, market, sales quantity, sales amount, profit margin, and cost price.

transactions.csv: This file contains the raw transaction data.

customers.csv: This file contains information about each customer, including their name and type (e.g., Brick & Mortar, E-Commerce).

markets.csv: This file contains information about each market, including the city and zone.

products.csv: This file contains information about each product, including its type (e.g., Own Brand, Distribution).

date.csv: This file contains date information that can be used for time-based analysis.

sales tra.csv: This file contains comprehensive sales transaction data, including customer, product, market, and date information.

🛠️ How to Use
To use the dashboard, simply open the Power BI file and interact with the visuals. You can use the filters and slicers to drill down into specific areas of the data. For example, you can filter the data by date, customer, product, or market.

️ Data Model
The data is modeled using a star schema, with the sales profit 4.csv and sales tra.csv files as the fact tables and the other files as the dimension tables. The tables are related as follows:

sales profit 4.csv and sales tra.csv are related to customers.csv on customer_code.

sales profit 4.csv and sales tra.csv are related to products.csv on product_code.

sales profit 4.csv and sales tra.csv are related to markets.csv on market_code.

sales profit 4.csv and sales tra.csv are related to date.csv on order_date.

📈 Dashboard Components
The dashboard consists of the following pages:

Overview: This page provides a high-level overview of the company's sales and profitability.

Customer Analysis: This page allows you to analyze sales and profitability by customer.

Product Analysis: This page allows you to analyze sales and profitability by product.

Market Analysis: This page allows you to analyze sales and profitability by market.

Time Series Analysis: This page allows you to analyze sales and profitability over time.

📄 Disclaimer
The data in this dashboard is for demonstration purposes only and should not be used for making real-world business decisions.
