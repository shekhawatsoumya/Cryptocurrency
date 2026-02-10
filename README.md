# Cryptocurrency Dashboard Analysis

Live Cryptocurrency Data Analysis Using Power BI

## Project Overview
This project provides a comprehensive analysis of the cryptocurrency market using live data from CoinGecko API. The analysis includes real-time market metrics, historical performance trends, and comparative analysis of major cryptocurrencies with advanced visualizations and interactivity.

---

## 📊 Data Source

**Source**: [CoinGecko API](https://api.coingecko.com)
- **Endpoint**: `/api/v3/coins/markets`
- **Parameters**: 
  - `vs_currency=usd` (USD pricing)
  - `order=market_cap_desc` (sorted by market cap)
  - `per_page=100` (top 100 cryptocurrencies)
  - `price_change_percentage=24h,7d` (price change metrics)

**Data Type**: Live, Real-time cryptocurrency market data
**Update Frequency**: Near real-time updates

---

## 🧹 Data Cleaning & Preparation

**Tool**: Power BI / Power Query Editor

### Data Transformation Process:
1. **Data Import**: Extracted cryptocurrency market data from CoinGecko API
2. **Data Validation**: Cleaned and validated currency values, price points, and market cap figures
3. **Formula Creation**: Applied M language formulas to:
   - Convert JSON API responses to tabular format
   - Parse and normalize cryptocurrency identifiers (1-100 rank)
   - Standardize price and percentage fields
   - Handle null values and data inconsistencies
4. **Calculated Columns**: Created derived metrics for:
   - Price change percentages (24hr, 7d)
   - Market capitalization calculations
   - Performance indicators
5. **Data Relationships**: Established relationships between cryptocurrency entities and their metrics
6. **Data Type Optimization**: Ensured proper data types for numerical, currency, and date fields

---

## 📈 Analysis Performed

### Key Performance Indicators (KPIs)
The dashboard displays prominent metric cards showing:
- **Coin Count**: Total number of cryptocurrencies analyzed (Top 100)
- **Market Cap (USD)**: Total combined market capitalization
- **Price Change Percentage (24hr)**: Real-time 24-hour price movement
- **Price Change Percentage (7d)**: 7-day price trend analysis
- **Current Price (USD)**: Live cryptocurrency prices

### 1. Time-Series Analysis
- **All Time High (ATH) by Year**: Line charts tracking historical performance peaks
- **Yearly Trend Analysis**: Visualizes how major cryptocurrencies have performed across different time periods
- **Historical Price Movement**: Identifies seasonal patterns and long-term trends
- **Performance Benchmarking**: Compares cryptocurrencies based on ATH volatility and growth

### 2. Ranking & Comparative Analysis
- **Top Cryptocurrencies Ranking**: Table-based comparison of major assets (e.g., Wrapped Bitcoin, Lido Staked Ether)
- **All Time Low (ATL) Analysis**: Comparative metrics showing lowest historical prices
- **All Time High (ATH) Comparison**: Ranking by historical peaks
- **Market Cap Distribution**: Analyzing market dominance among different cryptocurrencies

### 3. Advanced Filtering & Interactivity
Dynamic filter controls enabling:
- **By Cryptocurrency Name**: Filter dashboard to view specific coins or staked/wrapped versions
- **By All Time High Year**: View assets that reached their peak in specific years
- **Multi-select Filtering**: Analyze multiple cryptocurrencies simultaneously
- **Real-time Dashboard Refresh**: Updates reflect latest market conditions

### 4. Data Aggregation & Insights
- **Multi-source Data Integration**: Combines pricing, market cap, and performance data
- **Market Overview**: Provides snapshot of top 100 cryptocurrencies
- **Comparative Metrics**: Benchmarks wrapped and staked assets against base cryptocurrencies
- **Volatility Analysis**: Captures price fluctuations to identify investment risks/opportunities

---

