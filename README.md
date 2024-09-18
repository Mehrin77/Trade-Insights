# TradeVolumeAnalysis

Made for LankaBangla Securities Ltd by Mehrin Khan 

This Shiny app facilitates the analysis of financial trading data by combining user-uploaded CSV files with real-time data scraped from the Dhaka Stock Exchange website. The app provides dynamic visualizations for various stock symbols, allowing users to analyze trading activity and market trends.

## Features
- **Upload CSV Files**: Supports up to 5 CSV files for trading data analysis.
- **Data Scraping**: Scrapes real-time data from the Dhaka Stock Exchange.
- **Data Cleaning**: Automatically cleans trading data by removing irrelevant symbols and unwanted characters.
- **Dynamic Plots**: Visualizes trading pressures (buy/sell) across price levels using bar charts.
- **Custom Symbol Filtering**: Allows users to filter plots based on selected stock symbols.
- **Real-Time Refresh**: Users can refresh scraped data for up-to-date market insights.

## How to Use
1. Upload up to 5 CSV files with trading data.
2. Select the stock symbols to analyze.
3. Scrape the latest market data or refresh the data at any time.
4. View dynamic bar plots showing total quantities of shares bought/sold at different price points.
5. Explore detailed information for specific symbols based on scraped data.

## Installation
1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Install the required R packages:
   ```
   install.packages(c("shiny", "tidyverse", "dplyr", "ggplot2", "rvest", "plotly"))
   ```
3. Run the Shiny app:
   ```R
   shiny::runApp()
   ```
