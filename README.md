# BIS_Assignment
# Business Intelligence Systems - Assignment 1

## Overview
This repository contains the code and analysis for Assignment 1 of the IS4116 - Business Intelligence Systems course. The project focuses on performing a complete data analytics process to gain insights into car pricing and performance metrics. The analysis includes data preprocessing, exploratory data analysis (EDA), statistical methods, and machine learning models to predict car prices.

## Author
- **Name:** S.M.R.L.A. Senadheera  

## Dataset
The dataset used for this analysis is sourced from Kaggle and contains information about various car models, including engine specifications, fuel type, transmission type, market category, and pricing (MSRP). The dataset can be found [here](https://www.kaggle.com/datasets/CooperUnion/cardataset/data).

## Repository Structure
- **Data Preprocessing:** Cleaning the dataset by handling missing values, dropping duplicates, and encoding categorical variables using one-hot encoding.
- **Feature Engineering:** Normalizing numerical features and preparing the dataset for machine learning models.
- **Exploratory Data Analysis (EDA):** Visualizing key trends, including the distribution of car prices, correlations between engine horsepower and MSRP, and fuel efficiency trends.
- **Statistical Analysis:** Applying correlation analysis and training machine learning models (Linear Regression and Decision Tree Regression) to predict car prices.
- **Model Evaluation:** Comparing model performance using metrics such as Mean Squared Error (MSE) and R-squared (R²).

## Key Findings
- **Average Car Prices by Most Frequent Models:** Models like Mercedes-Benz, BMW, and Cadillac are among the most expensive among the most frequent models, reflecting their premium positioning in the automotive market.
- **Average Car Prices Over the Years:** The graph shows a steady increase in car prices over the 1990-2000 decade, with a significant increment after 2000.
- **Correlation Matrix:** Higher engine horsepower correlates positively with engine cylinders and MSRP but negatively with fuel efficiency.
- **Linear Regression Model:** Achieved an MSE of 2,153,104,435.78 and an R-squared (R²) value of 0.52.
- **Decision Tree Model:** Achieved an MSE of 326,881,601.59 and an R-squared (R²) value of 0.93, indicating a significant improvement in prediction accuracy compared to the linear regression model.

## Usage
To replicate the analysis, follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/Rashmina-Senadheera/BIS_Assignment.git
   cd BIS_Assignment