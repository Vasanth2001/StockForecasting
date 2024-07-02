# StockForecasting
Analyzed stock data using Python's tools: calculated daily returns and sales volume, visualized trends with matplotlib and seaborn. Used pandas for data manipulation including moving averages. Developed LSTM and ANN models for accurate stock price forecasting, leveraging machine learning for insightful trend analysis.

# Introduction
The project focuses on leveraging machine learning (ML) techniques to forecast stock prices, particularly focusing on tech giants such as Apple, Amazon, Microsoft, and Google. The goal is to analyze historical stock data, visualize key parameters, and develop robust forecasting models using Artificial Neural Networks (ANN) and Long Short-Term Memory (LSTM) networks. By harnessing the power of data analytics and deep learning, the project aims to predict future stock prices with accuracy and efficiency.

# Objectives
Data Analysis and Measurement:
Analyze on-hand stock data to measure parameters like daily returns and sales volume. Utilize pandas for data manipulation to derive metrics such as moving averages and daily returns.
Visualization:
Utilize matplotlib and seaborn to create clear and informative infographics of stock price trends and metrics. Visualizations aid in understanding historical trends and patterns in stock prices.
Machine Learning Models:
Develop an efficient ANN model to predict the closing price of stocks. Implement an LSTM model to forecast future stock prices based on historical data. Evaluate and compare model performance using metrics like mean squared error and root mean squared error.

# Problem Statement
The project aims to collect and utilize stock price data from Yahoo Finance, spanning over a period of 10.5 years for tech companies. Focus will primarily be on Apple's stock price for training and validating ML models. The challenge lies in training models that can effectively learn from past stock movements to accurately forecast future closing prices. The project hypothesizes that ML and deep learning models can capture complex patterns in stock data, providing reliable predictions beyond manual analysis capabilities.
Methodology
Data Collection and Preprocessing: Collect historical stock price data from Yahoo Finance for Apple and other selected companies. Clean and preprocess the data to remove inconsistencies and prepare it for analysis and model training.
Feature Engineering:
Generate relevant features such as daily returns and moving averages using pandas. Prepare the data for input into the ML models, ensuring compatibility with ANN and LSTM architectures.
Model Development: Implement an ANN model to predict daily stock closing prices based on historical data features. Utilize LSTM networks to model sequential dependencies in stock price data for accurate forecasting.
Model Evaluation: Assess model performance using statistical metrics like mean squared error (MSE) and root mean squared error (RMSE). Compare the effectiveness of ANN and LSTM models in capturing and predicting stock price trends.

# Results and Conclusion
The project concludes that ML-driven forecasting models, particularly LSTM for sequential data and ANN for regression tasks, are effective in predicting stock prices with high accuracy. The use of data visualization tools like matplotlib and seaborn enhances the interpretability of stock price trends, aiding in informed decision-making for investors. Future work could explore enhancements in model robustness, scalability, and application to broader datasets and market conditions.
