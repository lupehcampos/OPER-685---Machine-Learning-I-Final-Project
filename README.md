This repository contains the code and resources for analyzing FIFA player data and predicting broad player positions using various machine learning techniques. The project focuses on data wrangling, feature engineering, and classification to explore player attributes and quality tiers.

## Project Overview

The main objectives of this project are:  

1. Predict a player's broad position on the soccer field (Goalkeeper, Defender, Midfielder, Forward) based on player attributes.  
2. Categorize player quality into tiers ("low", "mid", "high") using overall ratings.  

The project applies multiple machine learning methods, including Naive Bayes, K-Nearest Neighbors, Multinomial Logistic Regression, and Random Forests, with careful consideration of assumptions and feature suitability.  

## Machine Learning Techniques

The project applies multiple classifiers:

- **Naive Bayes (GaussianNB):** Assumes Gaussian distribution for numeric features; features are conditionally independent.  
- **K-Nearest Neighbors (KNN):** Distance-based classification with no parametric assumptions.  
- **Multinomial Logistic Regression:** Models the probability of each position class; assumes a linear relationship with the log-odds.  
- **Random Forests:** Ensemble method robust to non-linear relationships and interactions; requires no distributional assumptions.  
