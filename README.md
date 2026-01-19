# E-Commerce Sales Analysis (Interactive Power BI Dashboard)

## Project Objective
The objective of this project is to analyze an e-commerce dataset to derive insights into sales performance, customer behavior, and profitability across various regions and categories. This dashboard serves as a tool for stakeholders to make data-driven decisions to optimize future business strategies.

## Dataset Overview
The analysis is performed on two interconnected tables:
* **Orders Table:** Contains order details including Order ID, Order Date, Customer Name, State, and City.
* **Details Table:** Contains transaction-level data such as Amount, Profit, Quantity, Category, Sub-Category, and Payment Mode.

## Key Questions Addressed
* What is the total revenue and profit generated?
* Which states are the top contributors to sales?
* What is the distribution of sales by product category and sub-category?
* How does profit fluctuate on a monthly basis?
* What is the most preferred payment method among customers?

## Custom Calculation (AOV)
In this project, I created a custom column for **AOV (Average Order Value)** within the Power BI 'Details' table. 
* **AOV Formula Logic:** It helps in understanding the revenue efficiency by calculating the average value spent per unit in an order.

## Dashboard Features & Visualizations
* **KPI Cards:** Displaying Total Amount (438K), Total Profit (37K), Total Quantity (5615), and Total AOV (121K).
* **Sales by State:** A bar chart showing regional performance, with **Maharashtra** being the top state.
* **Category Distribution:** A donut chart highlighting that **Clothing** is the dominant category (63%).
* **Monthly Profit Trend:** A visualization of profit growth and dips from January to December.
* **Payment Mode Analysis:** A chart showing **COD (Cash on Delivery)** as the most popular method (44%).
* **Interactive Slicers:** Added filters for **Quarter** and **State** to allow dynamic data exploration.

## Dashboard Preview
![E-Commerce Dashboard](img..png)

## Final Insights
* **Top Market:** Maharashtra and Madhya Pradesh are the key revenue-generating states.
* **Product Demand:** Clothing is the highest-selling category by quantity.
* **Customer Behavior:** The majority of customers prefer COD and UPI for their transactions.
* **Profitability:** Specific sub-categories like Printers and Bookcases show strong profit margins.
