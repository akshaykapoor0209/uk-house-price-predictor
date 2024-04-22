# UK House Price Predictor

## Overview
The UK House Price Predictor project aims to utilize data-driven techniques to analyze and forecast changes in residential property values in the UK housing market. The project primarily focuses on leveraging the UK House Price Index (UK HPI) dataset, a comprehensive collection of sales data, to predict average house prices using machine learning techniques.

## Abstract
The project involves various stages, including data preprocessing, exploratory data analysis, feature selection, modeling using Random Forest Regression, and dimensionality reduction using Principal Component Analysis (PCA). By following a systematic approach, the project demonstrates how data science methodologies can extract valuable insights from large datasets to predict real-world phenomena.

## Key Features
- Utilization of the UK House Price Index (UK HPI) dataset for analysis and prediction.
- Data preprocessing techniques, including handling missing values, outliers, and feature selection.
- Implementation of Random Forest Regression for house price prediction.
- Dimensionality reduction using Principal Component Analysis (PCA) to streamline the dataset.
- Evaluation of model performance using R-squared, Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
- Deployment considerations and suggestions for future improvements.

## Directory Structure
data.csv - Data used for the following project.
HousePricePrediction.ipynb - Python notebook with code.

## Results
- Random Forest Regression applied after data transformation
- High R-squared score close to one indicates good fit
- Relatively low RMSE values suggest accurate predictions
- K-fold Cross-Validation applied to further evaluate the model
- Evaluation after K-fold Cross-Validation
  - Slight change in RMSE, but R-squared remains high
  - Model consistently performs well across different splits
- Decision to reduce dimensionality using PCA
- PCA applied after data standardization, reducing dimensions to seven components
- Explained Variance Ratio and Cumulative Explained Variance Ratio plotted which illustrates that over 80% of variance is accounted for by PC1, followed by 10% by PC2
- Residual 10% of variance attributed to remaining PCA components
- Random Forest Regression applied again, this time using PC1 and PC2 as essential features

## Contributions and Feedback
Contributions and feedback are welcome! If you have any suggestions, enhancements, or bug fixes, feel free to open an issue or submit a pull request.

