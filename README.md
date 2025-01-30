# Impact of New iPhone Releases on Apple Stock Prices (2023-2024)

## Introduction
This project analyzes the impact of new iPhone launches on the stock price of Apple Inc. (AAPL) in **2023 and 2024**. The objective is to understand how the release of new iPhone models affects AAPL's stock price, volume, and overall market sentiment. This analysis is focused on the launch dates of new iPhones, with a specific comparison of stock prices and volume trends before and after the launches.

## Research Question
**What is the impact of new iPhone model releases in 2023 and 2024 on Apple’s stock prices?**

## Data Sources
- **Apple Stock Price Data**: Historical stock price data for Apple Inc. was retrieved using the [Yahoo Finance API](https://www.yfinance.io/). The data includes the closing prices, open prices, high and low prices, and trading volume.
  
- **iPhone Launch Dates**: Information about the launch dates of iPhone models was scraped from [Wikipedia](https://en.wikipedia.org/wiki/IPhone) using web scraping techniques. These dates are used to identify the impact of new iPhone releases on stock prices.

## Steps

## 1. Data Collection

- **Stock Data**: Stock data for Apple was retrieved using the `yfinance` library. The dataset includes historical data from January 2023 to January 2025, which was saved as a CSV file.
  
- **iPhone Launch Data**: Using web scraping techniques with BeautifulSoup, the launch dates of iPhone models were extracted from the Wikipedia page dedicated to iPhones. This data was saved into a CSV file for later analysis.

## 2. Data Cleaning and Preparation
To ensure the dataset was ready for analysis, we performed the following steps:
1. **Removed extraneous rows and columns.**
2. **Handled missing values** by filling or removing incomplete data points.
3. **Formatting the numerical data to two decimal places for consistency.**
4. **Converted data types** (e.g., dates to `datetime`, numeric fields to `float`).
5. **Standardized stock metrics** to include only relevant features.

## 3. Data Analysis and Visualization
### Stock Price Trends
We plotted the stock prices over time to visualize any noticeable fluctuations around iPhone release dates. Key observations:
- **Short-term spikes**: Stock prices often increased in the days leading up to a launch.
- **Post-launch corrections**: Slight dips were observed after the excitement subsided.

### Volume Analysis
We analyzed trading volume to assess investor activity. Observations included:
- **Higher trading volume** on release days, indicating increased market interest.

## Tools Used
- **Data Analysis:** Python (Pandas, Matplotlib, Seaborn)
- **Web Scraping:** BeautifulSoup and Requests
- **Version Control:** Git and GitHub
- **Documentation:** Markdown for reporting

## Findings
1. **Price Increase Before Launches:** Investors showed optimism leading up to iPhone releases, resulting in pre-launch price hikes.
2. **Slight Dips Post-Launch:** After the initial hype, stock prices stabilized or slightly decreased.
3. **High Volume on Release Days:** Significant trading activity was observed on and around release dates.


## Conclusion
The analysis highlights a consistent pattern of increased investor interest and market activity surrounding Apple’s iPhone launches. While stock prices typically rise before a launch, post-launch stabilization is common. Understanding these patterns can provide valuable insights for investors and market analysts.



To run the analysis, the following Python packages are required:

- `pandas`
- `matplotlib`
- `requests`
- `beautifulsoup4`
- `yfinance`

**Authors:**
- Davi Alencar
- Lucas Duarte

**Repository:** [GitHub Link](https://github.com/Lucasdua/Datamodeling)
