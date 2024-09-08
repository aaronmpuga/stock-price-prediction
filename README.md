# Project Summary
This project predicts the closing stock price of Apple Inc. (Ticker Symbol: AAPL) using historical stock price and financial data. The analysis is performed using a Jupyter Notebook and involves data preprocessing, feature engineering, and model training.

# Overview
- Data Collection and Preparation:
Utilized various datasets including financial fundamentals and historical stock prices.
Cleaned and merged data to create a comprehensive dataset for analysis.
- Feature Engineering:
Added key features such as the Simple Moving Average (SMA) to enhance model inputs.
Conducted correlation analysis to identify influential factors affecting stock prices.
- Model Building:
Applied Ridge Regression to predict stock prices, focusing on minimizing prediction errors.
Performed hyperparameter tuning using GridSearchCV to optimize the model's performance.
- Evaluation:
Assessed model performance using metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared.
Implemented K-Fold Cross Validation to ensure robust and reliable model performance.

# Files
The data used in ths project was taken from [Kaggle](https://www.kaggle.com/datasets/dgawlik/nyse/data?select=prices.csv)

Majority of stock data was collected from 2010 to 2016 (varies by company)

- `fundamentals.csv`: Contains fundamental financial data of companies.
- `prices.csv`: Contains daily stock prices of companies.
- `prices-split-adjusted.csv`: Contains split-adjusted stock prices.
- `securities.csv`: Contains additional company information.

