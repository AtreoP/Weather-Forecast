# Daily Delhi Climate Analysis

This repository contains Python code for analyzing and visualizing daily climate data for Delhi. The data used in this analysis is sourced from the "DailyDelhiClimateTrain.csv" dataset.

## Table of Contents

- [Introduction](#introduction)
- [Data Overview](#data-overview)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Relationship Between Temperature and Humidity](#relationship-between-temperature-and-humidity)
- [Temperature Change Over the Years](#temperature-change-over-the-years)
- [Time Series Forecasting](#time-series-forecasting)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project utilizes Python libraries such as pandas, numpy, matplotlib, seaborn, Plotly, and Facebook Prophet to analyze and visualize climate data for Delhi. It includes exploratory data analysis, data visualization, and time series forecasting using the Prophet library.

## Data Overview

The dataset used in this analysis, "DailyDelhiClimateTrain.csv," contains daily climate data for Delhi, including mean temperature, humidity, and wind speed, over a period of time.

### Data Description

```python
# Load and describe the data
import pandas as pd

data = pd.read_csv("DailyDelhiClimateTrain.csv")
print(data.head())
print(data.describe())
print(data.info())
```

## Exploratory Data Analysis

### Mean Temperature Over the Years

![Mean Temperature in Delhi Over the Years](link_to_your_mean_temperature_plot)

### Humidity Over the Years

![Humidity in Delhi Over the Years]
![image](https://github.com/AtreoP/Weather-Forecast/assets/97874269/16693680-7c39-44d9-ba41-9c506c5e29c8)


### Wind Speed Over the Years

![Wind Speed in Delhi Over the Years](link_to_your_wind_speed_plot)

## Relationship Between Temperature and Humidity

This scatter plot shows the relationship between temperature and humidity in Delhi:

![Temperature-Humidity Scatter Plot](link_to_your_temperature_humidity_scatter_plot)

## Temperature Change Over the Years

This line plot visualizes the change in temperature in Delhi over the years, grouped by month:

![Temperature Change Over the Years](link_to_your_temperature_change_plot)

## Time Series Forecasting

We used Facebook Prophet to make time series forecasts of mean temperature in Delhi.

![Prophet Forecast Plot](link_to_your_prophet_forecast_plot)

## Getting Started

To run this analysis on your local machine, follow the instructions below.

### Installation

1. Clone this repository to your local machine using `git clone`.

2. Install the required Python libraries using `pip`:

   ```bash
   pip install pandas numpy matplotlib seaborn plotly prophet
   ```

### Usage

1. Run the Jupyter Notebook or Python script containing the analysis.

2. Customize the analysis and visualization as needed for your specific use case.

## Contributing

Contributions to this project are welcome! If you have any suggestions or improvements, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

