# autoregressive-neuralnetwork

# Time Series Data Cleaning and Preparation Script
The "data_cleaning" Python script is designed to clean and prepare time-series data from a CSV file. Its main purpose is to ensure that the data has a complete daily chronological index for a given period and to fill any missing values using the forward-fill (`ffill`) method. This is particularly useful for financial data (such as commodity prices, stock prices, etc.) where data might only be recorded on trading days, but a complete daily calendar series is required for further analysis or modeling.

Prerequisites:
* Python 3.x
* Pandas library

You can install the Pandas library using pip if you haven't already:
```bash
pip install pandas
pip install numpy
pip install tensorflow
pip install matplotlib
pip install sklearn
pip install tensorflow
```
Altough it is recomended to use Google Colab Notebook to run the `main` program, because the GPU usage is still not optimized for low-end GPU.
