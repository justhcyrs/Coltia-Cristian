# London Crime Data Analysis and Prediction

## Introduction
This project focuses on the analysis and prediction of crime levels in London using large-scale public data. The dataset contains information about reported crimes, structured by borough, crime category, and time (year and month).

The project combines Big Data processing, exploratory data analysis, visualization, and machine learning regression models to identify crime trends and to predict the number of crimes based on temporal and categorical features.

All data was extracted from Google Cloud BigQuery, using a public dataset on London crime statistics, and processed in Google Colab using PySpark.

## Objectives
- Data extraction from Google BigQuery
- Data processing using PySpark
- Exploratory data analysis (EDA)
- Visualization of crime trends
- Predictive modeling using regression algorithms
- Model comparison using RMSE and R²

## Data Procurement
The dataset was retrieved from Google Cloud BigQuery using a public London crime database. The SQL query aggregates crime counts by borough, crime category, year, and month, for the period 2008–2016.

## Data Structure
The processed dataset includes:
- borough
- major_category
- year
- month
- total_crimes

Categorical variables were encoded and assembled into a feature vector for machine learning.

## Exploratory Data Analysis
The EDA includes:
- Total crime count
- Crime distribution by borough and category
- Temporal analysis by year and month
- Visualization of crime evolution over time

## Algorithms Used
Three regression models were implemented using PySpark ML:
1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor

## Evaluation Metrics
Models were evaluated using:
- RMSE (Root Mean Squared Error)
- R² (Coefficient of Determination)

## Results
Tree-based models (Decision Tree and Random Forest) significantly outperformed Linear Regression, indicating strong non-linear patterns in the data.

## Technologies Used
- Google Colab
- Google BigQuery
- PySpark
- Pandas
- Matplotlib
- Python

## Conclusion
This project demonstrates the effectiveness of Big Data tools and machine learning techniques in analyzing and predicting crime patterns in an urban environment.
