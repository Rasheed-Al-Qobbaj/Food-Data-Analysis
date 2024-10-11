# Food Data Analysis

This repository contains a Jupyter Notebook that analyzes Food and currency rates over the 2020 Gaza Strip dataset and performs various data manipulations and visualizations.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Data Analysis](#data-analysis)
  - [Currency Rate Over Time](#currency-rate-over-time)
  - [Unified Price Calculation](#unified-price-calculation)
  - [Maximum Prices](#maximum-prices)
    - [Commodities Measured by Weight](#commodities-measured-by-weight)
    - [Commodities Measured by Volume](#commodities-measured-by-volume)

## Introduction

This project analyzes currency rates and commodity prices. It includes visualizations of currency rates over time and calculations of unified prices for commodities measured by weight and volume.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Rasheed-Al-Qobbaj/currency-rate-analysis.git
    ```
2. Navigate to the project directory:
    ```sh
    cd currency-rate-analysis
    ```
3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Open the Jupyter Notebook:
    ```sh
    jupyter notebook Report.ipynb
    ```
2. Run the cells in the notebook to perform the analysis.

## Data Analysis

### Currency Rate Over Time

The notebook includes a plot of currency rates over time, showing trends and fluctuations.

### Unified Price Calculation

A new column called `unified_price` is created to represent the price in USD per kilogram for commodities measured by weight and the price per liter for commodities measured by volume.

### Maximum Prices

#### Commodities Measured by Weight

The most expensive commodity measured by weight is a kilogram of Goat Meat with a price of 17.31 USD.

#### Commodities Measured by Volume

The most expensive commodity measured by volume is a liter of Fuel (petrol-gasoline) with a price of 2.05 USD.
