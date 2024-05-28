# LinearRegression_CanadaPerCapitaIncome

## Overview
This repository contains code for a simple linear regression model to predict Canada's per capita income based on historical data. The model is built using Python and the scikit-learn library.

## Dataset
The dataset used for training the model is included in the repository as `canada_per_capita_income.csv`. It contains two columns:
- `year`: The year (in numerical format).
- `per_capita_income`: The per capita income for that year in US dollars.

## Dependencies
To run the code in this repository, you'll need the following dependencies:
- Python (version 3.x)
- scikit-learn
- pandas
- matplotlib (for visualizing data)

You can install the dependencies using pip.

## Result
We know that the formuls is y = a * x + b. a is coefficient which I found it with "reg.coef_" code. b is interception which I found it with "reg.intercep_" code:
a = 828.46507522
b = -1632210.7578554575
If we want to find the income in 2024, our x will be 2025.
y = 828.46507522 * 2025 + (-1632210.7578554575) and y will be 44602.55439531 as the result in the given example.
