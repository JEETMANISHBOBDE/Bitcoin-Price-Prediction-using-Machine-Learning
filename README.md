# Bitcoin Price Prediction Using Machine Learning
This project explores predicting Bitcoin prices using machine learning techniques on historical data. Bitcoin, known for its volatility, makes it a challenging yet interesting asset to predict. By leveraging the yfinance library, we fetch Bitcoin's historical data and apply a Linear Regression model to predict the next day's price.

Dataset

The data is retrieved from Yahoo Finance using yfinance. It includes daily information about Bitcoin's market activity—Open, High, Low, Close, Adjusted Close, and Volume—spanning from January 1, 2015, to December 31, 2023.

Methodology

Data Preprocessing:
The Close price is selected as the main feature for our model.
A new column, Target, is created to represent the next day's closing price.
After cleaning the data and handling missing values, it’s split into a training set (80%) and a testing set (20%).
Model Training:
We use a Linear Regression model to train on the data and predict the next day’s closing price.
The model is tested on the testing set to see how well it performs.
Evaluation:
To assess the model, we calculate performance metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
A plot comparing actual vs. predicted prices helps visualize how well the model does.
Prediction:
After training, the model is used to predict the next day’s Bitcoin price based on the most recent closing value in the dataset.
Results

While the Linear Regression model offers a basic approach, its accuracy may vary due to Bitcoin's unpredictable market behavior. However, this project serves as a good starting point for more complex models and gives a glimpse into predicting financial data.

Tools and Libraries

Libraries: Python, Scikit-learn, Pandas, Numpy, Matplotlib, Yfinance.
Environment: Google Colab or Jupyter Notebook.
This project demonstrates how machine learning can be used to predict financial data, specifically Bitcoin prices.
