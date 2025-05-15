## Amazon-Sales-Report
## Project Overview

This project performs a comprehensive exploratory data analysis (EDA) and visualization of an Amazon sales dataset. The goal is to extract meaningful insights into sales trends, product preferences, customer behavior, and geographical distribution to inform strategic business decisions.

## Dataset Description

The dataset contains detailed records of Amazon orders including:

Order details: Order ID, Date, Status, Fulfillment method

Product information: Category, Size, Quantity, Amount

Customer and shipping details: Sales channel, shipping city/state/country, courier status

Additional attributes: B2B indicator, currency, and fulfillment status

Total records: ~121,000 rows with 21 columns.

## Project Steps

1. Data Loading and Cleaning

Loaded data from CSV file

Converted date columns to datetime format

Handled missing values and corrected data types (categorical, numeric, datetime)

Extracted a ‘Month_Year’ column for time-series aggregation

2. Exploratory Data Analysis and Visualization
   
Monthly sales trends over time

Product category and size-wise sales distribution

Fulfillment method and order status breakdown

Customer segmentation by B2B/B2C and sales channels

Geographical sales distribution by states and cities

3. Insights and Recommendations

Identified peak sales periods and seasonal trends

Highlighted best-selling categories and popular sizes

Assessed fulfillment effectiveness and delivery status

Revealed key customer segments and top-performing regions

Provided actionable suggestions for inventory management, marketing, and customer service

## Key Findings

Sales peak during specific months indicating seasonality.

T-shirts and Shirts in sizes M and L are the most popular products.

Majority of orders fulfilled by merchants with high delivery success rates.

B2C customers generate most revenue; Amazon.in is the dominant sales channel.

Maharashtra, Karnataka, and Tamil Nadu are top-performing states.

## Recommendations

Increase marketing and inventory preparation ahead of peak sales months.

Optimize stock levels focusing on top-selling categories and sizes.

Strengthen partnerships with reliable fulfillment partners.

Tailor regional marketing efforts to high-sales states and cities.

Explore strategies to increase B2B customer sales.

## Technologies and Libraries

Python 3.x

Pandas for data manipulation

Matplotlib and Seaborn for visualization

Jupyter Notebook for interactive analysis

## How to Run

Ensure you have Python 3.x installed.

Install required libraries:

pip install pandas matplotlib seaborn

Load the dataset CSV into the notebook environment.

Run the notebook cells sequentially to perform data cleaning, analysis, and visualize results.
