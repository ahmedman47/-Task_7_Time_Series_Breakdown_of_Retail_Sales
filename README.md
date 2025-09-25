## Overview
In this task, I analysed a retail sales dataset with the goal of understanding revenue trends over time.  
The objective was to break down sales by product and region, identify seasonal patterns, and visualise overall growth or decline.

## Steps
1. **Loading the dataset**  
   - Imported the Walmart Sales Forecasting dataset (from Kaggle) into Python.  
   - Used pandas to parse dates and set them as time-series indices.  

2. **Data preparation**  
   - Cleaned missing values in sales records.  
   - Ensured date formats were consistent for proper resampling.  
   - Grouped data by product categories and regions.  

3. **Exploratory time series analysis**  
   - Plotted monthly and yearly sales trends.  
   - Calculated moving averages to smooth fluctuations.  
   - Identified seasonality patterns (e.g., holiday peaks, slow months).  

4. **Breakdown by dimensions**  
   - Compared revenue across regions to spot geographic differences.  
   - Analysed performance by product category to identify best sellers.  

5. **Visualisations**  
   - Line plots showing overall sales trends.  
   - Moving average overlays to highlight underlying growth.  
   - Seasonal breakdowns for regions and products.  

6. **Bonus step**  
   - Applied simple forecasting techniques such as rolling mean and exponential smoothing to project near-future sales.  

## Outcome
The analysis provided a clear picture of how sales evolved over time, both overall and by region/product.  
Strong seasonal patterns were observed, and key products driving revenue were identified.  
These insights can help businesses forecast demand and optimise inventory planning.
