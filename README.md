# Time Series Data Cleaning and Preparation Script
The "data_cleaning" Python script is designed to clean and prepare time-series data from a CSV file. Its main purpose is to ensure that the data has a complete daily chronological index for a given period and to fill any missing values using the forward-fill `ffill` method. This is particularly useful for financial data (such as commodity prices, stock prices, etc.) where data might only be recorded on trading days, but a complete daily calendar series is required for further analysis or modeling.

# Autoregressive Neural Network
This project implements an Autoregressive Neural Network (ARNN) using Long Short-Term Memory (LSTM) layers to forecast Brent crude oil prices for the next 30 days based on historical trends. The model learns to predict multiple future steps based on a fixed-length window of past data. Each prediction is based on the previous `input_size` days autoregressive in nature, but learned via deep learning.

You can install the library using pip if you haven't already:
```bash
pip install pandas
pip install numpy
pip install tensorflow
pip install matplotlib
pip install sklearn
```

Altough it is recomended to use Google Colab Notebook to run the `main` program, because the GPU usage is still not optimized for low-end GPU. Also ensure your CSV file is available at the specified path.
