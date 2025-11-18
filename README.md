# Stock-Forecasting

In this project, I developed an **LSTM-based time-series model** to predict future stock values. I trained the model on about **11 years of historical data**, allowing it to learn long-term trends and sequential patterns. After training, I saved the model and used it for **inference**, where I provided a **50-day input window** to forecast the **next two days’ closing prices**. This workflow let the model capture temporal dependencies and generate short-term, data-driven forecasts.

## Dependencies

This project has been developed using the following libraries:

- [NumPy](https://numpy.org): A library for numerical computing with Python.
- [Pandas](https://pandas.pydata.org): A library for data manipulation and analysis.
- [scikit-learn](https://scikit-learn.org): A library for machine learning and data preprocessing.
- [TensorFlow](https://www.tensorflow.org): An open-source machine learning framework.
- [Keras](https://keras.io): A high-level deep learning framework.
- [Pickle](https://docs.python.org/3/library/pickle.html): A library for object serialization.

Please ensure that you have these libraries installed or include them in your project environment before running the code.

### Modules and Classes Used

- `numpy`: Imported as `np` to perform numerical computations.
- `pandas`: Imported as `pd` to handle data manipulation and analysis.
- `sklearn.preprocessing.MinMaxScaler`: Used for feature scaling.
- `tensorflow.keras.models.load_model`: Used to load a saved model.
- `keras.models.Sequential`: Used to create a sequential model.
- `keras.layers.Dense`: Used to add dense layers to the model.
- `keras.layers.LSTM`: Used to add LSTM layers to the model.
- `pickle`: Used for object serialization.
- `sklearn.metrics.mean_squared_error`: Used to calculate the mean squared error.

## Objective
Develop a ML model to accurately predict the closing price of a stock, enabling informed investment decision.

## Approach

• Adopted LSTM model, a powerful RNN to capture and learn complex temporal dependencies in stock data.

• Train the model using a comprehensive historical stock info, ensuring a thorough analysis of trends and patterns.

• Implement advanced data preprocessing techniques including normalization, scaling, and handling missing
values and feature engineering to optimize the model’s performance and enhance prediction accuracy.

## Outcome

•  Attained 95.3% Directional Accuracy in LSTM model’s future value prediction by minimizing the MSE of predictions, indicating accurate predictions of stock price.

• Built an LSTM-based time-series model to forecast stock prices, generating actionable insights that supported risk assessment, portfolio decisions, and overall investment planning.
