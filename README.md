# Walmart Sales Data Analysis

## About

This project is a simple analysis of Walmart Sales data. It focuses on understanding which branches and products perform best, customer buying patterns, and overall sales trends. The dataset is from the [Kaggle Walmart Sales Forecasting Competition](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting).

## Purpose

The goal of this project is to explore the sales data and learn about:
- Top-selling products and branches
- Customer buying behavior
- Sales trends over time

## Dataset Information

The dataset contains sales data from three Walmart branches located in Mandalay, Yangon, and Naypyitaw. Below is a brief description of the data:

| Column Name             | Description                             |
|-------------------------|-----------------------------------------|
| invoice_id              | Sales invoice number                    |
| branch                  | Branch where the sale happened          |
| city                    | City where the branch is located        |
| customer_type           | Type of customer (new or returning)     |
| gender                  | Gender of the customer                  |
| product_line            | Category of the product sold            |
| unit_price              | Price per unit of the product           |
| quantity                | Number of units sold                    |
| VAT                 | Tax on the sale                         |
| total                   | Total amount of the sale                |
| date                    | Date of the sale                        |
| time                    | Time of the sale                        |
| payment_method          | Payment method (cash, card, etc.)       |
| cogs                    | Cost of Goods Sold                      |
| gross_margin_percentage | Profit margin in percentage             |
| gross_income            | Total profit from the sale              |
| rating                  | Customer rating for the product         |

## What I Did

1. **Loaded the Data**: I imported the sales data into a SQL database.
2. **Cleaned the Data**: I checked for missing values and corrected them.
3. **Created New Columns**: I added columns like `time_of_day` (morning, afternoon, evening) and `day_name` (Monday, Tuesday, etc.) to analyze when most sales happen.
4. **Analyzed the Data**: I wrote SQL queries to answer questions like:
   - What products are most popular?
   - Which branch makes the most sales?
   - How do customer preferences change by gender?

## Key Questions

Here are some of the questions I answered with SQL queries:

1. How many cities and branches are in the data?
2. What are the most popular products and which branch sells the most?
3. Which customer type (new/returning) spends the most money?
4. How does sales performance change throughout the day or week?

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/walmart-sales-analysis.git


### Explanation of Sections:

1. **About**: A brief overview of what the project is about.
2. **Purpose**: Simple goals of the project in plain language.
3. **Dataset Information**: A quick summary of the dataset, focusing on the columns.
4. **What I Did**: A simple explanation of the steps you took in your project.
5. **Key Questions**: Basic questions that the analysis addresses.
6. **How to Use**: Instructions for how someone can use your project, like cloning the repository and running the queries.
7. **Conclusion**: A quick summary of what you learned.

This `README.md` is easy to understand, and it's suitable for someone who is new to data analysis projects. You can copy and adjust this as needed for your GitHub repository! Let me know if you need any further help!
