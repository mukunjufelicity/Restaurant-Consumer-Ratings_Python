![image](https://github.com/mukunjufelicity/Restaurant-Consumer-Ratings_Python/assets/8385040/d18b6e51-ea30-4fdc-9894-4d3dadb032df)# Restaurant - Customer Rating Project

## Introduction
This project explores restaurant customer rating using Python libraries and Jupyter notebooks.

## Project Goal
This project aims to analyze and predict restaurant ratings based on various factors, for example service, cuisine type, and restaurant locations. The dataset consists of information about restaurants, user profiles, and ratings given by users to different restaurants.

## Project Overview
The project involves several steps, including data loading, data cleaning, exploratory data analysis (EDA), feature engineering, model building, and evaluation. Here's an overview of the project workflow:

### Step 1: Data Loading and Cleaning
- Imported necessary libraries such as pandas, matplotlib, and seaborn.
- Loaded CSV files into DataFrames using pandas.
- Checked basic information about each DataFrame.
- Handled missing values and outliers in the data to ensure data quality.

### Step 2: Exploratory Data Analysis (EDA)
- Conducted EDA to understand the distributions and relationships between different variables.
- Analyzed correlations between various factors such as service rating, cuisine type, and overall rating.
- Visualized key insights using plots and charts.

### Step 3: Feature Engineering
- Engineered new features or transformed existing ones to improve model performance.
- Merged restaurant-related and user-related data to create a comprehensive dataset for modeling.

### Step 4: Model Building and Evaluation
- Split the dataset into training and testing sets.
- Built a linear regression model to predict restaurant ratings based on service ratings.
- Evaluated the model using mean squared error (MSE) and R-squared (R^2) score.
- Visualized model predictions against actual ratings.

## Files and Directory Structure
- **README.md**: This file provides an overview of the project, its objectives, and the steps involved.
- **data**: This directory contains the original dataset files.
- **notebooks**: This directory contains Jupyter notebooks used for data analysis, modeling, and visualization.
- **scripts**: This directory contains Python scripts for specific tasks such as data cleaning, feature engineering, and model building.
- **reports**: This directory contains reports generated during the project, including EDA findings, model evaluation results, and visualizations.

## Findings Summary based off of Correlation Analysis
- There are a lot of customers going to various restaurants, whereby the top 10 most visited restaurants are located in Mexico.
- From the top 10 most visited restaurants Cafeteria y Restaurant El Pacifico (placeID 135032) ranked first on both weekdays and weekends, for a duration of 15hrs and 30 mins.
- Cafeteria y Restaurant El Pacifico was ranked high due to its popular cuisine type which is Cafeteria and Contemporary.
- Based on cuisine type the highest ranked is Fast_Food based off of the food rating by customers.
- From the model evaluation, a Linear Regression model was used to predict overall ratings based on service ratings. There appears to be a positive correlation between service rating and overall rating.

## Conclusion
This project demonstrates how data analysis and machine learning techniques can be used to gain insights and make predictions in the restaurant industry. By analyzing factors such as service quality, cuisine type, and restaurant visits, restaurant owners and managers can make informed decisions to improve customer satisfaction and business performance.
