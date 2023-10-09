Stock Data Visualization with Candlestick Chart and MACD Indicator

This Python script allows you to download historical stock data from Yahoo Finance, visualize it with a candlestick chart, and add the MACD (Moving Average Convergence Divergence) indicator using Plotly. The candlestick chart provides insights into the stock's price movements, while the MACD indicator helps in analyzing potential trends and reversals.

Prerequisites

Before running the script, ensure you have the following prerequisites installed:

- Python 3.x
- Required Python packages (you can install them using pip):
  - requests
  - yfinance
  - pandas
  - numpy
  - plotly
  - python-dotenv

Usage

1. Clone this repository to your local machine:

   git clone https://github.com/HarshP0818/TradeZodia.git

2. Navigate to the project directory:

   cd Project-TradeZodia

3. Create a .env file and add your Alpha Vantage API key:

   API_KEY=your_api_key_here

   Replace your_api_key_here with your actual Alpha Vantage API key.

4. Run the Python notebook:

    via each cell
   

5. Follow the prompts to enter the stock symbol, start and end dates, and timeframe.

6. The script will download the stock data, calculate the MACD indicator, and generate an interactive HTML file (candlestick_chart_with_macd.html) with the candlestick chart and MACD indicator.

7. Open the generated HTML file in a web browser to visualize and analyze the stock data.

Features

- Download historical stock data from Yahoo Finance based on user input.
- Visualize the stock data using an interactive candlestick chart.
- Calculate and display the MACD line, Signal line, and MACD Histogram below the candlestick chart.

Acknowledgments

- This project uses Plotly for creating interactive data visualizations.
- Special thanks to the Plotly, Yahoo Finance, and Alpha Vantage communities for their contributions.

Please feel free to contribute to this project or provide feedback. If you have any questions or issues, please open an issue at https://github.com/HarshP0818/TradeZodia/issues.

Happy stock data analysis!