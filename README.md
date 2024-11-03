# Capstone-Goodpaster
Capstone project for CodeU

#Description
The Amazon Product Tracker project is a data analysis tool designed to track and analyze the price trends and availability of Amazon products over time. Using RapidAPI’s Amazon data API, this tool fetches detailed information on specific items based on ASINs (Amazon Standard Identification Numbers). Users can select products to track from popular categories, customer reviews, or trending items. The project involves data collection, storage in a SQL database, and visualization of price changes with line charts to observe market dynamics or price fluctuations. Built in a Jupyter Notebook, the tracker features a user-friendly layout and includes data cleaning, database setup, and well-documented steps for reproducibility. Ideal for users interested in market analysis, the project provides clear insights into how prices and availability vary across different products on Amazon.


Project Outline: Amazon Product Tracker

1. Project Setup and Data Collection
  Objective: Set up a system to track item prices and availability over time for specific Amazon products.
    Steps: Create a list of product IDs (ASINs) for the items you want to track.
  Set up API integration with the Real-Time Amazon Data API to pull product details, pricing, and availability.
  Store the collected data in a SQL database.

2. Data Cleaning and Transformation
  Objective: Clean and prepare data for analysis.
   Steps: Parse and clean product details (e.g., remove duplicate entries, handle missing data).
    Ensure consistent data formatting for time series analysis.

3. Data Storage and Retrieval with SQL
  Objective: Store product data in a database to enable time-series analysis.
Steps: Use SQL to store data in tables based on product IDs, timestamps, prices, and availability.
    Retrieve data from SQL tables for analysis and visualizations.

4. Data Analysis and Visualization
  Objective: Analyze price trends and availability over time and display insights.
Steps: Calculate average price, price fluctuation, and identify any trends.
    Visualize price history and availability status for each item using Matplotlib, Tableau, or Seaborn.

5. Interpretation and Documentation
  Objective: Summarize findings, document project, and outline setup instructions.







   
  
