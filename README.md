# Analyzing Historical Stock and Revenue Data

## Project Overview
This project demonstrates data extraction and visualization techniques for analyzing stock market data. It focuses on extracting historical stock prices and revenue information for Tesla (TSLA) and GameStop (GME), then creating interactive visualizations to display the trends.

## Description
This data analysis project extracts essential stock and revenue data from various sources and displays it through interactive graphs. The project showcases practical data science skills including API usage, web scraping, data cleaning, and data visualization - all critical competencies for making data-driven decisions.

## Technologies Used
- **Python 3.7+**
- **yfinance** (0.1.67) - For extracting stock price data
- **pandas** - For data manipulation and analysis
- **requests** - For HTTP requests and web scraping
- **BeautifulSoup4** (4.10.0) - For parsing HTML and extracting revenue data
- **Plotly** - For creating interactive visualizations
- **nbformat** (4.2.0) - For Jupyter notebook operations

## Features
- Extract historical stock price data using yfinance API
- Web scrape quarterly revenue data from online sources
- Clean and process financial data
- Create interactive dual-axis graphs showing:
  - Historical share price trends
  - Historical revenue trends
- Compare Tesla and GameStop stock performance

## Project Structure
```
.
├── Final Assignment.ipynb    # Main Jupyter notebook with complete analysis
└── README.md                  # Project documentation
```

## Installation & Setup

1. Clone this repository:
```bash
git clone <repository-url>
cd analyzing_historical_stock-revenue_data_IBM_DA
```

2. Install required dependencies:
```bash
pip install yfinance==0.1.67
pip install beautifulsoup4==4.10.0
pip install pandas
pip install requests
pip install plotly
pip install nbformat==4.2.0
```

## Usage

1. Open the Jupyter notebook:
```bash
jupyter notebook "Final Assignment.ipynb"
```

2. Run all cells to:
   - Extract Tesla (TSLA) stock data
   - Scrape Tesla revenue data
   - Extract GameStop (GME) stock data
   - Scrape GameStop revenue data
   - Generate interactive visualizations

## Analysis Components

### Question 1: Tesla Stock Data Extraction
Uses yfinance to extract maximum historical stock data for Tesla (TSLA).

### Question 2: Tesla Revenue Data Extraction
Performs web scraping to extract Tesla's quarterly revenue from online sources.

### Question 3: GameStop Stock Data Extraction
Uses yfinance to extract maximum historical stock data for GameStop (GME).

### Question 4: GameStop Revenue Data Extraction
Performs web scraping to extract GameStop's quarterly revenue from online sources.

### Question 5: Tesla Stock Visualization
Creates an interactive graph displaying Tesla's historical share price and revenue trends.

### Question 6: GameStop Stock Visualization
Creates an interactive graph displaying GameStop's historical share price and revenue trends.

## Key Learnings
- Extracting financial data using APIs (yfinance)
- Web scraping techniques with BeautifulSoup
- Data cleaning and preprocessing (removing special characters, handling missing values)
- Creating multi-subplot visualizations with Plotly
- Working with time-series financial data

## Data Sources
- Stock price data: Yahoo Finance (via yfinance API)
- Revenue data: IBM Skills Network cloud storage

## Notes
- The visualizations display data up to June 2021
- Revenue figures are in USD millions
- Stock prices are in USD

## Author
IBM Developer Skills Network Course Project

## Acknowledgments
- Joseph Santarcangelo (PhD in Electrical Engineering)
- Azim Hirjani
- IBM Skills Network

## License
© IBM Corporation 2020. All rights reserved.

## Change Log
| Date | Version | Changed By | Change Description |
|------|---------|------------|-------------------|
| 2022-02-28 | 1.2 | Lakshmi Holla | Changed the URL of GameStop |
| 2020-11-10 | 1.1 | Malika Singla | Deleted the Optional part |
| 2020-08-27 | 1.0 | Malika Singla | Added lab to GitLab |
