# Mercado Libre Prophet Challenge

---

## Overview

This repository contains the solution to the Mercado Libre Prophet Challenge, which focuses on analyzing the company's Google search traffic and stock price data to predict future trends. The project leverages the Prophet forecasting model to analyze seasonality and its correlation with stock price patterns. 

---

## Key Tasks

The analysis consists of the following major tasks:

1. **Data Retrieval:**
	- Fetching hourly Google search traffic data related to Mercado Libre.
	- Importing stock price data for Mercado Libre during the year 2020.

2. **Data Cleaning and Preparation:**
	- Slicing the Google search data for the month of May 2020 to correlate with Mercado Libre's quarterly financial results.
	- Ensuring the data is properly formatted for time series analysis, with correct datetime formatting.
	- Calculating total search traffic and comparing it to monthly medians to identify unusual patterns.

3. **Data Analysis:**
	- Analyzing search traffic for seasonality, including hourly, weekly, and yearly trends.
	- Investigating the correlation between lagged search trends and stock price volatility or returns.
	- Using Prophet to model and forecast search traffic for Mercado Libre.

4. **Results Export:**
	- Exporting the results of the time series forecasts, including lower and upper bounds of predictions, for future analysis.
	- Plotting the individual time series components like daily, weekly, and yearly trends.

---

## How to Run

Clone the Repository:
git clone https://github.com/CCIEMikeG/prophet-challenge.git
cd prophet-challenge

1. **Set Up the Environment:**
	- Ensure Python 3.x is installed.
	- Install required libraries:
	pip install -r requirements.txt

2. **Run the Notebook:**
	- Open the `forecasting_net_prophet.ipynb` notebook using Jupyter Notebook or VS Code.
	- Execute each cell sequentially to replicate the analysis and view the results.

---

## Dependencies:

Ensure the following Python libraries are installed:

	- pandas
	- numpy
	- matplotlib
	- prophet
	- requests

You can install these libraries with:
pip install pandas numpy matplotlib prophet requests

---

## Results

The analysis successfully:

	- Retrieved and cleaned Google search traffic and stock price data.
	- Identified seasonal trends in the Google search data.
	- Built a time series model using Prophet for predicting future trends.
	- Visualized and interpreted key time series components, including daily, weekly, and yearly patterns.

---

## License

This project is licensed under the MIT License.