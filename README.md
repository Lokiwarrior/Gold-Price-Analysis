# Gold-Price-Analysis
Project on Gold Price Trends


This project aims to predict Gold Prices (GLD) using various economic indicators such as stock index (S&P 500), oil prices, silver prices, and the EUR/USD exchange rate.
The goal is to apply Machine Learning regression models to understand patterns and make accurate future price predictions for gold — one of the most important global commodities.

#Steps- 

Loaded the dataset using pandas and inspected null values and data types.

Converted the ‘Date’ column into datetime format for analysis.

Explored correlations between features using a heatmap.

Selected GLD as the target variable and remaining features as independent variables.

Split the data into training and testing sets using train_test_split().

Standardized the features where necessary for model performance consistency.


#The EDA involved understanding relationships and distributions through:

Correlation heatmap (to check strongest influencing factors)

Line charts for trend visualization over time

Pairplots & scatter plots showing relationships between gold price and other features



#Key Observations:

GLD shows strong positive correlation with SLV (Silver).

Weak to moderate correlation with SPX (S&P 500 index).

Economic indicators like EUR/USD and Oil (USO) also impact gold price fluctuations.



Result# 
Random Forest proved to be the most reliable model for predicting gold prices.

The analysis showed that silver prices and currency rates are significant influencers.

The model can help investors, analysts, and traders understand how global factors affect gold pricing.

<img width="1045" height="785" alt="image" src="https://github.com/user-attachments/assets/f119545c-8de8-4f71-a54d-8dfd39076726" />


