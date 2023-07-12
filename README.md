# Tunisian Water Level Prediction

This project is a Jupyter Notebook that implements a Time Series model for predicting the water level in multiple dams across Tunisia. The goal of the project is to provide accurate and timely predictions to help monitor and manage water resources in the country.

## Table of Contents
- [Introduction](#introduction)
- [Data](#data)
- [Methodology](#methodology)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Water scarcity and effective management of water resources are critical issues for Tunisia. This project aims to address these challenges by developing a predictive model that can forecast the water level in multiple dams across the country. The model is based on time series analysis and provides valuable insights for decision-makers and water resource managers.

## Data

The dataset used for this project includes historical water level data from various dams in Tunisia. The data is collected at regular intervals, and each observation consists of the dam's location, date, and the corresponding water level,it was given for free by the Tunisian government. The dataset is preprocessed and cleaned to remove any missing or erroneous values before being used for model training and evaluation.

## Methodology

The Time Series model employed in this project is based on the xgbregressor model. Xgbregressor is a powerful tool to provide accurate predictions.

The methodology used in this project can be summarized as follows:
1. Data preprocessing: Cleaning the dataset, handling missing values, and formatting the data for analysis.
2. Exploratory data analysis: Understanding the characteristics of the data, identifying patterns, and visualizing the time series.
3. Model training: Using the Prophet library to train the time series model on the historical data.
4. Model evaluation: Assessing the performance of the trained model using appropriate evaluation metrics.
5. Forecasting: Generating future predictions of water levels based on the trained model.

## Installation

To run the Jupyter Notebook and reproduce the results, follow these steps:

1. Clone the repository:

   ```
   https://github.com/mehdixlabetix/Weather-Time-Series
   ```

2. download the Dataset:

   ```
   https://catalog.data.gov.tn/fr/dataset/barrages
   ```

3. Launch Jupyter Notebook:

   ```
   jupyter notebook
   ```

4. Open the notebook  and execute the cells sequentially.

Note: Make sure you have Python 3.x and Jupyter Notebook installed on your system.

## Usage

The Jupyter Notebook provides detailed documentation and code comments to guide you through the project. Each step is explained in a clear and concise manner, making it easy to understand and modify the code according to your specific needs.

You can customize the model parameters, such as the time range, number of training periods, and seasonality components, to experiment with different configurations. Additionally, the notebook includes sections for visualizing the results and evaluating the model's performance.

## Results

The project generates accurate predictions of water levels in multiple dams across Tunisia. The results can be visualized using interactive plots and graphs, allowing users to easily interpret and analyze the forecasted data. The model's performance can also be evaluated Root Mean Squared Error (RMSE).

## Contributing

Contributions to this project are welcome. If you have any suggestions, bug reports, or feature requests, please open an issue on the GitHub repository. You can also fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this code for personal and commercial purposes. See the [LICENSE](LICENSE) file for more details.

