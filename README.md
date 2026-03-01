# PROJECT 1: Advertising Sales Prediction

## Overview
This project analyzes the impact of advertising expenditure (TV, Radio, Newspaper) on product sales using Linear Regression.

## Objectives
- Identify correlation between advertising mediums and sales
- Build a multiple linear regression model
- Evaluate model performance
- Analyze impact of feature removal
- Study effect of feature normalization

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Key Findings
- TV advertising has the strongest correlation with Sales (~0.90)
- Removing TV significantly reduces prediction accuracy
- Feature normalization does not significantly affect Linear Regression performance

## Model Used
- Multiple Linear Regression
- Train/Test Split (80/20)
- MinMaxScaler (for normalization experiment)

## Sample Prediction
Input:
TV = 200, Radio = 40, Newspaper = 50

Predicted Sales:
19.79 units

## Conclusion
TV advertising is the most influential feature for predicting sales. The model demonstrates strong predictive performance with multiple features.

# PROJECT 2: Facebook Live Sellers Engagement Analysis

## Overview
This project analyzes engagement metrics of Facebook Live sellers and applies K-Means clustering to identify engagement patterns.

## Objectives
- Analyze impact of posting time on reactions
- Study correlation between reactions, comments, and shares
- Apply K-Means clustering
- Use Elbow Method to determine optimal clusters
- Analyze engagement across post types

## Technologies Used
- Python
- Pandas
- Matplotlib
- Scikit-learn

## Key Insights
- Highest reactions observed around 7 PM
- Weak positive correlation between reactions and comments/shares
- Optimal clusters found using Elbow Method (k=3)
- Video posts show significantly higher engagement

## Machine Learning Techniques
- K-Means Clustering
- Elbow Method for cluster optimization
- Correlation analysis

