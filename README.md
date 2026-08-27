# Gurgaon Real Estate Price Prediction

## Project Overview

This project focuses on predicting residential property prices in Gurgaon using machine learning regression techniques.

The project uses real estate property features such as area, location, BHK, bathrooms, property type and other available attributes to build a price prediction model.

## Project Objective

The main objectives of this project are:

- To understand and clean Gurgaon real estate data.
- To perform exploratory data analysis.
- To identify important factors affecting property prices.
- To preprocess numerical and categorical data.
- To build machine learning regression models.
- To compare different regression algorithms.
- To evaluate models using MAE, RMSE and R² Score.
- To identify the best-performing regression model.

## Dataset

The project uses a Gurgaon real estate dataset containing property-related information.

Important features may include:

- Property Price
- Area
- Location / Sector
- BHK
- Bathrooms
- Balconies
- Property Type
- Furnishing Status
- Society / Builder
- Other available property attributes

The exact dataset structure and source are documented in the Jupyter Notebook.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Google Colab
- GitHub

## Machine Learning Models

The following regression algorithms were implemented:

1. Linear Regression
2. Decision Tree Regression
3. Random Forest Regression

## Data Preprocessing

The following preprocessing steps were performed:

- Removed duplicate records.
- Checked missing values.
- Cleaned column names.
- Converted price values into numerical format.
- Converted area values into numerical format where applicable.
- Handled missing numerical values.
- Handled categorical values.
- Applied One-Hot Encoding to categorical features.
- Split the dataset into training and testing sets.

## Exploratory Data Analysis

The project includes:

- Property price distribution
- Area vs price analysis
- Correlation analysis
- Correlation heatmap
- Actual vs predicted price analysis
- Residual analysis

## Model Evaluation

The models were evaluated using:

### Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted prices.

### Root Mean Squared Error (RMSE)

Measures prediction error while giving greater importance to larger errors.

### R² Score

Measures how well the model explains the variation in property prices.

The detailed model results are available in:

`model_results.csv`

## Project Structure

```text
gurgaon-real-estate-regression/
│
├── Gurgaon_Real_Estate_Regression.ipynb
│
├── model_results.csv
│
├── Gurgaon_Real_Estate_Regression_Project_Report.docx
│
├── Gurgaon_Real_Estate_Regression_Presentation.pptx
│
└── README.md
