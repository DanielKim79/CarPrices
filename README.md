# CarPrices

This repository contains the files for the Module 11 Practical Application 2: "What Drives the Price of a Car?".

## Description of Files

•	'car_sales.ipynb' - this file contains the code for the practical application assignment.

• 'data.zip' - this file contains the vehicles.csv dataset.


## Data Preparation

•	Import the vehicles.csv data set.

•	Use functions such as info(), describe(), and head() to examine the data set.

•	Remove columns we won’t be using such as ID, Region, State, VIN, and Model.

•	Remove duplicate rows

•	Remove rows that null values in columns.

•	Delete cars where the price is not between $2K and $250K. This is to help remove outliers.

•	Delete cars where the odometer is not between 1K and 500K miles. This is also to help remove outliers.

•	Creates various plots to analyze the data.

•	Based on the plots, we decided to remove the Manufacturer, Cylinders, Title Status, Drive, Size, Type, and Paint Color columns.


## Modeling

•	We will be keeping the Condition, Fuel, and Transmission columns in our model.

•	Use OneHotEncoder on Condition, Fuel, and Transmission to convert the non-numeric values to numeric.

•	Use the MinMaxScaler

•	Use RFE to identify which features to select.

•	Use Variance Inflation Factor to see which ones have the most impact.

•	Use Price, Year, Odometer, Fuel Diesel, and Transmission Manual in our final dataset

•	Use Linear Regression modeling to train and test our data.
