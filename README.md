# E-Commerce Data Analysis Project

This project performs a comprehensive end-to-end data analysis on an e-commerce dataset consisting of 6 interlinked CSV files. Using **Python**, **Pandas**, **Matplotlib**, and **Seaborn**, the project explores customer behavior, sales trends, and seller performance.

## Project Structure
The analysis is divided into three tiers of problem-solving:
* **Basic:** General distributions and counts.
* **Intermediate:** Grouped aggregations and relational analysis.
* **Advanced:** Time-series trends, retention rates, and customer LTV.

## Dataset Description
The analysis utilizes the following relational files:
1.  `customers.csv`: Demographic data for buyers.
2.  `orders.csv`: Transaction lifecycle and timestamps.
3.  `order_items.csv`: Product-level details for each order.
4.  `payments.csv`: Financial transaction and installment data.
5.  `products.csv`: Item attributes and categories.
6.  `sellers.csv`: Merchant information.

## Key Insights
* **Market Concentration:** São Paulo is the primary hub, accounting for the highest customer density.
* **Financial Trends:** Over 51% of customers utilize installments for purchases.
* **Growth:** 2018 showed significant Year-over-Year revenue growth compared to 2017.
* **Retention:** Identified a baseline retention rate of 1.67%, suggesting a high focus on new customer acquisition.

## Requirements
To run the notebook in Google Colab or locally, you will need:
* Python 3.x
* Pandas
* Matplotlib
* Seaborn
* SQL Workbench (for SQL Queries)
