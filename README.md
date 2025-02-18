# Big-Mart-Sales-Project

# Project Description

This project aims to predict the sales of products in various Big Mart stores based on historical data. The model leverages machine learning techniques to analyze factors like item visibility, type, and store attributes to forecast sales accurately.

# Dataset

The dataset used for this project consists of sales data from multiple Big Mart stores. The key features include:

Item Identifier: Unique product ID

Item Weight: Weight of the product

Item Fat Content: Type of fat content (Low Fat/Regular)

Item Visibility: Percentage visibility of the item

Item Type: Category of the item

Item MRP: Maximum retail price

Outlet Identifier: Unique ID for each store

Outlet Establishment Year: Year the store was established

Outlet Size: Size of the store (Small/Medium/Large)

Outlet Type: Type of store (Supermarket/Grocery Store)

Item Outlet Sales: Target variable representing sales

# Installation

To run this project locally, follow these steps:

Clone this repository:

git clone https://github.com/yourusername/BigMartSalesPrediction.git
cd BigMartSalesPrediction

Install required dependencies:

pip install -r requirements.txt

Run the Jupyter Notebook:

jupyter notebook

# Model & Methodology

Data Preprocessing: Handling missing values, encoding categorical variables, and feature scaling.

Exploratory Data Analysis (EDA): Visualizing data distributions, correlations, and outliers.

Model Selection: Comparing multiple regression models including Linear Regression, Random Forest, and XGBoost.

Hyperparameter Tuning: Optimizing model parameters using Grid Search and Random Search.

# Usage

Load the dataset and preprocess the data.

Train the machine learning model using the provided scripts.

Evaluate the model using RMSE, R-squared, and other metrics.

Predict sales for new data.

# Results

The model achieved a competitive RMSE score.

Feature importance analysis showed that Item MRP, Outlet Type, and Item Visibility significantly impact sales.

The best-performing model was XGBoost with optimized hyperparameters.
