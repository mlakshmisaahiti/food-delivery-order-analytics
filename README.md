# Food Delivery Order Analytics
## Overview

This project explores food-delivery order data to identify patterns in order demand, discounts, geographic concentration, kitchen preparation time, rider waiting time, and order value.

The analysis combines exploratory data analysis, feature engineering, visualization, correlation analysis, and statistical testing.
## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels
- Google Colab
## Analysis Performed

- Data cleaning and initial data inspection
- Feature engineering
- Order demand analysis by time and location
- Discount and order value analysis
- Kitchen Preparation Time (KPT) analysis
- Rider wait time analysis
- Correlation analysis
- One-way ANOVA
- Tukey HSD post-hoc test
- Data visualization
## Key Findings

- Rider wait time showed a moderate positive correlation with Kitchen Preparation Time (KPT).
- KPT differed significantly across time periods based on one-way ANOVA.
- Evening and night accounted for the highest order volumes.
- A small number of subzones and restaurants accounted for a large share of the orders.
- Order value showed a positive association with KPT, while distance had a very weak association with KPT.
- The dataset contained a substantial proportion of discounted orders.
## Dataset

The dataset used in this project is the Food Delivery Order History dataset available on Kaggle.

Source: https://www.kaggle.com/datasets/sujalsuthar/food-delivery-order-history-data

The dataset contains 20,165 food-delivery orders with 29 variables.
