# Chicago Crime Rate Prediction

Author: Gaurav Kumar Singh

## Overview
This project aims to predict future crime rates in the city of Chicago using time series forecasting techniques. The dataset used contains information about reported crimes in Chicago from 2001 to 2017 and is sourced from the Chicago Police Department's CLEAR (Citizen Law Enforcement Analysis and Reporting) system. The project utilizes Facebook Prophet, an open-source forecasting tool, to analyze historical crime data and make predictions about future crime rates.

## Dataset
- **Source:** The dataset used in this project is available on Kaggle: [Chicago Crime Dataset](https://www.kaggle.com/currie32/crimes-in-chicago).
- **Features:** The dataset includes various columns, such as crime IDs, case numbers, dates, location details, arrest information, and more.
- **Data Preprocessing:** Data preprocessing and cleaning are performed to ensure that the dataset is suitable for time series forecasting. This includes setting the date-time column as the index and aggregating data as needed.

## Predictive Model
- **Facebook Prophet:** Facebook Prophet is used for time series forecasting. It is particularly well-suited for data with strong seasonal patterns and multiple seasons of historical data. Prophet can capture non-linear trends, seasonality, and holiday effects in the time series data.

## Installation and Setup
If you wish to run this project on your local machine, follow these steps:

1. Clone this repository to your local machine: `git clone <repository-url>`

2. Install the required dependencies using pip: `pip install -r requirements.txt`


3. Run the Jupyter Notebook to execute the code and perform crime rate predictions.

## Usage
- Open the Jupyter Notebook and run the cells in the provided order to load the dataset, preprocess the data, train the forecasting model, and generate predictions.

## Results
- The project provides forecasts of future crime rates in Chicago, along with visualizations to illustrate the predicted trends and bounds.

## Acknowledgments
- This project is made possible by the Chicago Police Department's CLEAR system and the contributors of the dataset on Kaggle.

## License
This project is open-source and available under the [MIT License](LICENSE).

For detailed code implementation and step-by-step instructions, refer to the Jupyter Notebook in this repository.

Feel free to adapt and use this project for your own research or analysis. If you have any questions or suggestions, please don't hesitate to reach out.

Happy forecasting!

