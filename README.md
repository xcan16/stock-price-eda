# Stock Price Analysis Project

A comprehensive stock price analysis project using Python. Features include technical indicators (RSI, MACD, Bollinger Bands), statistical analysis, and visualizations. Implements data validation, outlier detection, and correlation analysis with interactive visualizations.

## 📊 Project Overview

This project provides a comprehensive exploratory data analysis (EDA) of a stock price dataset, including:
- Technical indicators calculation and analysis
- Time series pattern detection
- Statistical analysis and visualization
- Data validation and quality checks

## 📈 Features

### Dataset
- 1857 rows, 21 columns
- Features: price (open, high, low, close, adjclose), volume, RSI, returns, lagged features, trend (target)

### Analysis Components
1. **Data Validation and Quality Checks**
   - Price logic validation
   - Missing data detection
   - Duplicate checks

2. **Technical Analysis**
   - RSI (Relative Strength Index)
   - MACD (Moving Average Convergence Divergence)
   - Bollinger Bands
   - Volume analysis

3. **Statistical Analysis**
   - Outlier detection (Z-score and IQR methods)
   - Correlation analysis
   - Time series patterns

## 🔍 Key Findings

- High data quality with no duplicates or logic errors
- Technical indicators provide useful trend signals
- Return-based features show meaningful correlations
- Volume spikes and outliers are properly detected

## 📸 Visualizations

All visualizations are saved in the `figures/` directory:
- Bollinger Bands analysis
- Technical indicators distribution
- Correlation matrix
- Volume and price trends

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/xcan16/stock-price-eda.git
```

2. Install required packages:
```bash
pip install pandas numpy matplotlib seaborn
```

3. Run the Jupyter notebook to see the analysis

## 📝 Results

The analysis provides a robust foundation for:
- Trading strategy development
- Market pattern analysis
- Risk assessment
- Technical indicator optimization

For detailed analysis and code, please refer to the Jupyter notebook in this repository.
