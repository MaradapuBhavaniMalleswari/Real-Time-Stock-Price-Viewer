# Real-Time Stock Price Viewer

## Overview

This project is a Real-Time Stock Price Viewer developed using Python's Dash and Plotly libraries. It allows users to select a stock symbol from a predefined list, fetch real-time stock data, and visualize it in an interactive dashboard.

## Features

- **Interactive Dashboard:** Visualize real-time stock prices using line and bar charts.
- **Stock Symbol Selection:** Choose from a list of predefined stock symbols.
- **Time Period Selection:** View stock data over different time periods (1 day, 5 days, 1 month, etc.).
- **Real-Time Data:** Fetch real-time stock data using the Yahoo Finance API.
- **Dynamic Interface:** Includes animations and random background colors for enhanced user experience.
- **Simulated Future Prices:** Predict future stock prices using linear regression.

## Technologies Used

- **Dash:** For creating the interactive web application.
- **Plotly:** For dynamic and interactive graphs.
- **Yahoo Finance (yfinance):** For fetching real-time stock data.
- **Dash Bootstrap Components (dbc):** For styling the UI with Bootstrap.
- **Pandas and Numpy:** For data manipulation and numerical operations.

## How to Run

1. Clone the repository:
   ```sh
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```sh
   cd real-time-stock-price-viewer
   ```
3. Create a virtual environment:
   ```sh
   python -m venv venv
   ```
4. Activate the virtual environment:
   - On Windows:
     ```sh
     .\venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```sh
     source venv/bin/activate
     ```
5. Install the required libraries:
   ```sh
   pip install -r requirements.txt
   ```
6. Run the application:
   ```sh
   python stockprice.py
   ```
