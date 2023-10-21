# Craigslist_car_timeseries

This project involves analyzing the Craigslist Vehicles Dataset, which contains information about vehicles listed for sale on Craigslist. We'll perform data cleaning, exploration, and create visualizations to gain insights into the dataset.

## Table of Contents
- [Overview](#overview)
- [Data Cleaning](#data-cleaning)
- [Data Exploration](#data-exploration)
- [Time-Series Analysis](#time-series-analysis)

## Overview
The dataset, available on Kaggle, contains details about vehicle listings, including attributes such as price, year, make, model, condition, location, and posting date. We will follow the steps outlined in the provided code to create a time-series analysis.

## Data Cleaning
We start by cleaning the dataset to ensure it is ready for analysis. Here's what we did:

- Handled missing values:
  - Filled missing values with the median for numerical columns.
  - Filled missing values with the mode for categorical columns.
  
- Converted the 'posting_date' column to a datetime data type for time-series analysis.

## Data Exploration
I explored the cleaned dataset to gain a better understanding of the data. This step is crucial for identifying patterns and trends. I performed exploratory data analysis, which can include:

- Visualizing the dataset using various plots and charts.
- Analyzing temporal patterns.
- Identifying seasonal trends and demand-supply dynamics by region and vehicle type.

## Time-Series Analysis
I created time-series charts to visualize trends in the data. Here's what we did:

- Plotted the count of listings on the first day of each month.
- Plotted the daily average price of listings.

These charts help us understand how listings change over time and the average price trend.



