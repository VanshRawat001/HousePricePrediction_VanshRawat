# House Price Prediction using Machine Learning

## Overview

This project focuses on predicting house prices using machine learning techniques on the Kaggle Housing Dataset. The objective is to analyze the factors affecting property prices and build predictive models for estimating house values.

## Dataset

The dataset contains 545 residential properties with features such as:

- Area
- Bedrooms
- Bathrooms
- Stories
- Main Road Access
- Guest Room
- Basement
- Air Conditioning
- Parking
- Preferred Area
- Furnishing Status

## Methodology

The project follows the following workflow:

1. Data Cleaning and Preprocessing
2. Feature Encoding
3. Exploratory Data Analysis (EDA)
4. Correlation Analysis
5. Model Training
6. Performance Evaluation
7. Feature Importance Analysis

## Models Used

### Linear Regression
Used as a baseline regression model for predicting house prices.

### Random Forest Regressor
Used to capture more complex relationships between features and house prices and to analyze feature importance.

## Results

| Model | R² Score |
|---------|----------|
| Linear Regression | ~65% |
| Random Forest Regressor | ~61% |

The results indicate that Linear Regression performed slightly better on this dataset.

## Key Findings

- Property area is the most important factor influencing house prices.
- Bathroom count has a significant impact on valuation.
- Air conditioning positively affects property value.
- Houses in preferred locations generally have higher prices.
- Main road access contributes to increased property value.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

## Repository Structure

```text
House-Price-Prediction/
│
├── House_Price_Prediction.ipynb
├── Housing.csv
├── README.md
├── requirements.txt
├── Summary.docx
└── Project_Report.pdf
```

## Future Improvements

The model can be improved by incorporating additional features such as:

- Property age
- Exact location information
- Renovation history
- Interior condition
- Neighborhood characteristics

## Author

Vansh Rawat
