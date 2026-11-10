# House Price Prediction Using Linear Regression

## Project Overview

This project focuses on predicting house prices using **Linear Regression** with Python. The main goal was to understand how different house features, such as area, bedrooms, bathrooms, parking, and furnishing status, affect house prices.

I worked with a real-world housing dataset and followed the complete machine learning workflow, from exploring and preparing the data to training and evaluating prediction models.

## Dataset

- **Dataset Name:** Housing Prices Dataset
- **Source:** [Kaggle – Housing Prices Dataset](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset)
- **File Name:** `Housing.csv`
- **Records:** 545 rows
- **Features:** 12 input features
- **Target Variable:** `price`

The dataset contains information about house sizes, rooms, facilities, road access, and furnishing status.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

## Project Workflow

I completed the project through the following steps:

1. **Data Loading:** Imported the housing dataset using Pandas.
2. **Exploratory Data Analysis (EDA):** Checked the dataset structure, missing values, descriptive statistics, and house price distribution.
3. **Feature Selection:** Selected relevant house features that could help predict prices.
4. **Data Preprocessing:** Handled missing values and converted categorical features using One-Hot Encoding.
5. **Correlation Analysis:** Created a correlation heatmap to explore relationships between features and house prices.
6. **Train-Test Split:** Divided the dataset into 80% training data and 20% testing data.
7. **Model Training:** Built a Linear Regression model using Scikit-learn.
8. **Model Evaluation:** Evaluated predictions using MSE, RMSE, and R² score.
9. **Visualisation:** Created actual vs. predicted price and residual plots.
10. **Coefficient Analysis:** Explored which features had the highest positive and negative coefficients.
11. **Model Comparison:** Compared Linear Regression with Ridge Regression.

## Model Performance

I compared two regression models using the same train-test split.

| Evaluation Metric | Linear Regression | Ridge Regression |
|---|---:|---:|
| MSE | 1.7543 × 10¹² | 1.7567 × 10¹² |
| RMSE | 1,324,507 | 1,325,417 |
| R² Score | 0.6529 | 0.6524 |

**Result:** Linear Regression performed slightly better than Ridge Regression on this dataset, with a higher R² score and lower RMSE.

The Linear Regression model achieved an R² score of approximately **65.29%**, showing that it explains around 65% of the variation in house prices in the test data.

## Key Learnings

Through this project, I gained practical experience in:

- Exploring and understanding a real-world dataset.
- Handling missing values and categorical data.
- Applying One-Hot Encoding.
- Understanding feature correlations.
- Training a machine learning regression model.
- Evaluating model performance.
- Visualising actual and predicted values.
- Understanding model coefficients.
- Comparing Linear Regression and Ridge Regression.

## Conclusion

This project was a great learning experience and helped me understand how machine learning can be used to solve real-world problems.

It also gave me hands-on practice with Python, data preprocessing, visualisation, and regression models. While the model produced useful predictions, there is still room to improve its performance by exploring additional features and trying other algorithms.

---
