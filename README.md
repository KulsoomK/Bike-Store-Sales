# Bike Store Sales Analysis

This project explores a comprehensive dataset of bike store sales, spanning multiple years, countries, and product categories. Using Python’s **pandas** for data manipulation and **matplotlib** for visualization, the goal is to extract insights about customer demographics, sales trends, and product performance.

## Dataset Overview

The dataset contains sales records with the following key fields:

* **Date, Day, Month, Year:** Time-related details for each sale.
* **Customer\_Age, Age\_Group, Customer\_Gender:** Customer demographic information.
* **Country, State:** Geographic details of the sale.
* **Product\_Category, Sub\_Category, Product:** Details about the product sold.
* **Order\_Quantity, Unit\_Cost, Unit\_Price, Profit, Cost, Revenue:** Financial and quantity metrics.

## Key Questions Explored

* What is the average age of customers and their distribution?
* How does order quantity vary and what are typical order sizes?
* Which years and months had the highest sales volume?
* What countries contribute most to sales and revenue?
* What are the best-selling products and categories?
* Are there noticeable relationships between costs, prices, profits, and quantities?
* How do profits and customer ages vary by country?
* How have sales evolved over time?
* What is the impact of tax adjustments on unit prices in different countries?

## Summary of Findings

* The average customer age centers around the adult demographic (35-64 years).
* Sales are distributed unevenly across years, with some peaks in certain months.
* The United States and Canada lead in total sales quantities.
* Accessories and Bikes are the primary product categories, with specific sub-categories like Bike Racks dominating in sales.
* There is a positive correlation between unit cost and unit price, and larger orders tend to yield higher profits.
* Profits and customer age vary significantly by country, suggesting different market dynamics.
* Time series analysis reveals seasonal trends and growth in sales over the years.
* Adjusting unit prices for taxes in the U.S. leads to a noticeable increase in revenue figures.

## Technologies Used

* Python (3.x)
* pandas (data manipulation)
* matplotlib (visualization)
* Jupyter Notebook (interactive exploration)

