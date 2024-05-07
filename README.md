# Flight Delay Prediction Model

## Overview
This project focuses on predicting flight delays using data mining techniques. Flight delays not only inconvenience passengers but also cause significant financial losses to airlines and nations. By employing a structured prediction system, we aim to assist aviation authorities in reducing aircraft delays and enhancing the efficiency of air travel.

## Problem Statement
Using historical flight data, the challenge is to develop a predictive model that can accurately estimate the likelihood of a flight being delayed. The goal is to analyze past data to discover trends and insights and create a model that provides reliable forecasts, aiding airlines and passengers in planning and responding effectively to delays.

## Data
The datasets used include flight delay data and weather data, merged into a single dataset for processing. The final cleaned dataset contains 11,292,279 rows and 30 features, chosen for their relevance to predicting flight delays.

### Data Sources
- Flight Data: [Google Drive Link](https://drive.google.com/drive/folders/1SG-U-9j-kq79JT3_M3j0wiZBjUTQLaqf)
- Weather Data: [Google Drive Link](https://drive.google.com/drive/folders/1FH3SzcDlcDVy4QkwB7z4VNi1bE18d0JA)

## Key Components
1. **Feature Engineering:** Identification and selection of key features affecting flight delays, including airline, flight schedules, weather conditions, and more.
2. **Model Development:** Utilization of machine learning algorithms and statistical techniques to create the prediction model.
3. **Model Evaluation:** Assessment using metrics like accuracy, precision, recall, F1-score, and ROC curve.
4. **Interpretability:** Analysis of the factors influencing delays to provide actionable insights.

## Models Implemented
- **Classifiers:** Naive Bayes, Logistic Regression, Decision Tree, Random Forest, K-Nearest Neighbour, Neural Network, Linear Discriminant Analysis
- **Regressors:** Linear Regression, Random Forest Regressor, KNN Regressor, Neural Net Regressor

## Results
The Random Forest Classifier outperformed other models with an AUC of 0.88. It demonstrated 85% accuracy in predicting the target class. The Random Forest Regressor was notable among regression models, showing significant gains with an R^2 score of 0.94.

## Impact
- **Improved Predictions:** Enhanced ability to forecast delays, allowing for better planning and operational decisions.
- **Economic Benefits:** Reduced costs related to delays and improved passenger satisfaction.
- **Application Potential:** Development of applications that can inform passengers of potential delays well in advance.

## Future Work
Further improvements can be achieved by collecting more extensive weather data and integrating both models into a cohesive pipeline for enhanced decision-making.

## How to Use
Details on how to set up and run the model can be found in the repository's documentation.

``
