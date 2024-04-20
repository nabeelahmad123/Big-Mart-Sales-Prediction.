# Big Mart Sales Prediction

## Introduction
This project aims to predict the sales of products in Big Mart outlets. It utilizes machine learning techniques to analyze various factors such as item weight, item visibility, item type, outlet size, etc., to predict the sales accurately. The dataset used for this project contains information about different products and their sales in Big Mart outlets.

## Required Libraries
- numpy
- pandas
- matplotlib
- seaborn
- sklearn
- xgboost

Ensure all required libraries are installed in your Python environment.

## Data Collection and Preprocessing
The dataset is loaded from a CSV file into a pandas DataFrame. Initial exploration of the dataset is performed to understand its structure and features. Missing values in the 'Item_Weight' and 'Outlet_Size' columns are filled using appropriate methods. Data visualization techniques such as histograms and count plots are employed to understand the distribution of various features in the dataset.

## Model Training
The dataset is split into training and testing sets using the train_test_split function from sklearn. An XGBoost regressor model is trained on the training data to predict the sales of the products. The trained model's performance is evaluated using the R-squared metric on both the training and testing datasets.

## How to Use
1. **Dependencies:** Install required libraries using pip:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn xgboost
