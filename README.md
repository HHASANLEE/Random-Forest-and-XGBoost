# California Housing Price Prediction Comparison

This repository contains a Python script that compares the performance of Random Forest Regressor and XGBoost Regressor models for predicting housing prices in California.

## Overview

The script uses the California Housing dataset from scikit-learn to train and evaluate two popular regression algorithms:
- Random Forest Regressor
- XGBoost Regressor

Both models are compared in terms of:
- Prediction accuracy (MSE and R² metrics)
- Training time
- Prediction time

The results are visualized through scatter plots comparing predicted values against actual values.

## Requirements

```
numpy
matplotlib
scikit-learn
xgboost
```

## Dataset

The California Housing dataset contains information about housing in California from the 1990 census. Each record represents a census block group and includes features such as:
- Median income
- Housing median age
- Average number of rooms
- Average number of bedrooms
- Population
- Average occupancy
- Latitude
- Longitude

The target variable is the median house value for California districts.

## Code Structure

The script performs the following steps:
1. Loads the California Housing dataset
2. Splits data into training and testing sets
3. Initializes and trains both Random Forest and XGBoost models
4. Measures and compares training and prediction times
5. Evaluates model performance using MSE and R² metrics
6. Visualizes prediction results with scatter plots

## Results

The comparison between Random Forest and XGBoost highlights:
- Performance differences in prediction accuracy
- Trade-offs between training time and prediction speed
- Visual representation of prediction quality with reference lines for perfect prediction and standard deviation bounds

## Usage

Simply run the script to train both models on the California Housing dataset and visualize the comparison results:

```python
python california_housing_comparison.py
```

## License

[Add your chosen license here]
