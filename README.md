## Stock and Revenue Analysis: Tesla & GameStop

This project uses Python to extract historical stock data with yfinance, scrape revenue data from HTML tables, clean the data with pandas, and visualize stock prices and revenue together using interactive Plotly graphs. The main focus is on Tesla (TSLA) and GameStop (GME).

## What this project does?
-  Downloads full historical stock data for TSLA and GME using yfinance.
-  Scrapes quarterly revenue data for both companies from HTML tables using pandas.read_html and requests.
-  Cleans the revenue data by removing currency symbols, commas, empty strings, and missing values.
-  Uses a reusable make_graph function with Plotly to plot:
     1.  Stock closing price over time.
     2.  Revenue over time in a second subplot sharing the same date axis.

### Main technologies
-  Python, Jupyter Notebook
-  yfinance, pandas, requests, beautifulsoup4 (optional), plotly

Note: If the interactive graphs do not appear in your viewer, check the saved static screenshots of the final Tesla and GameStop graphs as Plot Tesla Stock Graph.png and Plot GameStop Stock Graph.png respectively are included in this repository.
