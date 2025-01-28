# Impact of New iPhone Releases on Apple Stock Prices (2023-2024)

## Introduction
The primary goal of this project was to analyze the impact of new iPhone releases in **2023** and **2024** on Apple’s stock prices. By combining historical stock price data and additional information from web scraping, we sought to identify trends, correlations, and insights surrounding Apple's major product launches.

## Research Question
**What is the impact of new iPhone model releases in 2023 and 2024 on Apple’s stock prices?**

## Dataset Selection
We used Apple’s historical stock price data as the primary dataset, focusing on:
- **Stock metrics:** Opening price, closing price, daily high/low, and trading volume.
- **Timeframe:** Years 2023 and 2024.

The dataset was augmented using web scraping to collect information on:
- Dates of iPhone releases.
- News headlines and market sentiment surrounding the launches.

## Data Cleaning and Preparation
To ensure the dataset was ready for analysis, we performed the following steps:
1. **Removed extraneous rows and columns.**
2. **Handled missing values** by filling or removing incomplete data points.
3. **Converted data types** (e.g., dates to `datetime`, numeric fields to `float`).
4. **Standardized stock metrics** to include only relevant features.

## Analysis and Visualization
### Stock Price Trends
We plotted the stock prices over time to visualize any noticeable fluctuations around iPhone release dates. Key observations:
- **Short-term spikes**: Stock prices often increased in the days leading up to a launch.
- **Post-launch corrections**: Slight dips were observed after the excitement subsided.

### Volume Analysis
We analyzed trading volume to assess investor activity. Observations included:
- **Higher trading volume** on release days, indicating increased market interest.

### Correlation with News Sentiment
Using web scraping, we gathered news headlines and classified them as positive, neutral, or negative. Positive sentiment often aligned with upward trends in stock prices.

## Tools Used
- **Data Analysis:** Python (Pandas, Matplotlib, Seaborn)
- **Web Scraping:** BeautifulSoup and Requests
- **Version Control:** Git and GitHub
- **Documentation:** Markdown for reporting

## Findings
1. **Price Increase Before Launches:** Investors showed optimism leading up to iPhone releases, resulting in pre-launch price hikes.
2. **Slight Dips Post-Launch:** After the initial hype, stock prices stabilized or slightly decreased.
3. **High Volume on Release Days:** Significant trading activity was observed on and around release dates.
4. **Sentiment Alignment:** Positive market sentiment and news coverage amplified the stock's upward momentum.

## Conclusion
The analysis highlights a consistent pattern of increased investor interest and market activity surrounding Apple’s iPhone launches. While stock prices typically rise before a launch, post-launch stabilization is common. Understanding these patterns can provide valuable insights for investors and market analysts.

## Next Steps
1. Extend the analysis to include other Apple product launches.
2. Incorporate advanced machine learning models to predict stock movements based on sentiment and historical data.
3. Analyze the impact of broader market conditions on Apple's stock performance during product releases.

---

**Authors:**
- Davi Alencar
- Lucas Duarte

**Repository:** [GitHub Link](https://github.com/Lucasdua/Datamodeling)
