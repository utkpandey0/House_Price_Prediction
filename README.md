# House_Price_Prediction
his project focuses on predicting the price of a house based on various features such as the number of bedrooms, bathrooms, area (in square feet), location, year built, and other relevant factors. The goal is to build a machine learning model that can accurately estimate house prices to assist buyers, sellers, and real estate agents.

We start with a dataset containing historical housing data. The data is cleaned and preprocessed by handling missing values, converting categorical variables (like location or house type), and scaling numerical features when necessary.

Several regression models are used for training, including:

Linear Regression

Support Vector Regression (SVR)

K-Nearest Neighbors (KNN)

Random Forest Regressor

The models are evaluated using metrics like R² score, Mean Absolute Error (MAE), and Mean Squared Error (MSE).

To make the project user-friendly, we also build a web app using Gradio, where users can input house features and get an instant price prediction.

