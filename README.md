# Time Series Analysis and Modeling

This project focuses on performing time series analysis and modeling on stock price data using Python. It includes various techniques such as data preprocessing, visualization, moving average, seasonal decomposition, auto-regressive integrated moving average (ARIMA), and evaluation metrics.

## Dependencies

To run this code, make sure you have the following dependencies installed:

- pandas
- matplotlib
- sklearn
- statsmodels
- numpy

You can install these dependencies using pip:

```
pip install pandas matplotlib sklearn statsmodels arch pmdarima numpy
```

## Dataset

The code uses three stock price datasets: 'stein', 'mrp', and 'shop'. The dataset files are assumed to be in CSV format and are loaded using the `pd.read_csv()` function. You need to specify the correct file paths for each dataset file in the code.

## Usage

1. Make sure you have the required dependencies installed.

2. Download the stock price dataset files ('stein.csv', 'mrp.csv', 'shop.csv') and place them in the specified file paths in the code.

3. Open the project code in a Python environment, such as Jupyter Notebook or any Python IDE.

4. Customize the code as needed:
   - Update the file paths in the lines where datasets are loaded if the dataset files are located in different directories.
   - Modify the code to suit your specific time series analysis requirements.

5. Run the code cells in sequential order to execute the time series analysis and modeling.

6. Explore the generated visualizations, results, and evaluation metrics to gain insights into the stock price data.

Feel free to experiment with different parameters, techniques, and models to enhance the analysis and modeling of the time series data.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the [Apache License 2.0](http://www.apache.org/licenses/).
