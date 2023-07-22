# Price-Estimation-Model-for-Used-Household-Items
A machine learning model accurately predicts household item prices for major e-commerce retailers using a dataset of 1,000,000 transactions. Achieving 77% accuracy, the model empowers retailers to optimize pricing strategies, attract customers with competitive pricing, and adapt to the dynamic e-commerce landscape.


# Price Estimation Model for Household Items Using Machine Learning
# Overview
This project presents a machine learning model developed to predict prices for household items sold on major e-commerce retailers.
The model is based on analyzing over 1,000,000 transactions from e-commerce website datasets and uses various classification, regression, and clustering algorithms from the sci-kit-learn library.
## Project Period
August 2020 – August 2021
# Motivation
Pricing is a critical aspect of selling products online, and accurately determining the right price can be challenging.
The motivation behind this project was to develop a price prediction model that utilizes basic principles of machine learning to predict the accurate pricing of household items based on various parameters.
Data and Preprocessing
The dataset used consists of 1,000,000 rows, and important features like category name, brand name, and item description were considered for prediction.
Data preprocessing techniques, such as label encoding and data cleaning, were applied to handle missing values and transform textual data into a numerical format.
Prediction Algorithms
Three predictive algorithms were implemented: Ridge Regression, Light Gradient Boosting Machine (LGBM) Regression, and XGBoost Regression.
These algorithms were trained and tested to predict the average price of household items.
Results and Observations
The models were evaluated using Mean Squared Error (MSE) and R-squared (R2) metrics.
Advanced Text Preprocessing significantly improved the accuracy of all three models, with Ridge Regression showing the best performance.
# File Structure
markdown
Copy code
- Price_Estimation_Model/
    - Data/
        - ecommerce_data.csv
    - Code/
        - price_estimation_model.ipynb
    - README.md
How to Use
Clone the repository
Install the required dependencies
Run the Jupyter notebook "price_estimation_model.ipynb" to train and test the model.
Future Scope
Future improvements can include integrating image classification to further enhance the accuracy of the model by considering product images.
Additionally, incorporating seller profile verification can be explored to refine the prediction model.
