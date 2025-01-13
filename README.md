# Binance_Trade_Data_Analysis
Analysis of historical trade data from Binance accounts over a 90-day period, calculating financial metrics such as Return On Investment (ROI) , Profit and Loss (PnL) , Sharpe Ratio, and Maximum Drawdown (MDD) to rank accounts based on performance.

# Binance_Trade_Data_Analysis
![Binance Trade Data Analysis](https://github.com/user-attachments/assets/analysis_cover_image.png)

## Table of Contents
- Problem Statement
- Steps Followed
  - Data Exploration and Cleaning
  - Feature Engineering
  - Ranking Algorithm
  - Insights and Visualizations
- Key Learnings

---

## Problem Statement:
This project involves analyzing 90 days of historical trade data from Binance accounts to calculate key financial metrics:
- **Return on Investment (ROI)**  
- **Profit and Loss (PnL)**  
- **Sharpe Ratio**  
- **Maximum Drawdown (MDD)**  
- **Win Rate**  
The objective is to rank accounts based on performance and provide actionable trading insights.

---

## Steps Followed:

### 1. Data Exploration and Cleaning:
- Split raw data into structured columns.
- Removed unnecessary headers and columns.
- Converted timestamps into human-readable format.
- Handled null values, duplicates, and data type inconsistencies.
- Renamed columns for clarity.

### 2. Feature Engineering:
- Calculated metrics such as ROI, PnL, Sharpe Ratio, and MDD using standard financial formulas.
- Classified trades by type (BUY/SELL, LONG/SHORT).
- Engineered features to evaluate trading performance across multiple dimensions.

### 3. Ranking Algorithm:
- Accounts were scored using a weighted system prioritizing:
  - ROI
  - Sharpe Ratio
  - PnL
  - Win Rate
- Top 20 accounts were identified based on composite scores.

### 4. Insights and Visualizations:
- Scatter plot: Win Rate vs. PnL.
- Histogram: Sharpe Ratio and MDD distributions.
- Correlation heatmap: Relationship between key metrics.
- Scatter plot: ROI vs. Sharpe Ratio.

---

## Key Learnings:
- **Data Manipulation**: Mastered cleaning and organizing large datasets.
- **Financial Metrics**: Gained an understanding of risk-adjusted returns and trading performance.
- **Visualization**: Created clear, impactful visualizations with libraries like Matplotlib and Seaborn.
- **Ranking System**: Developed a methodology to score and rank accounts.
- **Documentation**: Improved project reporting and documentation skills.

---

## Visualizations:
### Sample Visuals
![Win Rate vs. PnL](https://github.com/user-attachments/assets/win_rate_pnl.png)
![ROI vs. Sharpe Ratio](https://github.com/user-attachments/assets/roi_sharpe.png)
![Sharpe Ratio Distribution](https://github.com/user-attachments/assets/sharpe_ratio_histogram.png)
![MDD Distribution](https://github.com/user-attachments/assets/mdd_histogram.png)

---

## Future Work:
- Incorporate trade duration and asset-specific performance for deeper insights.
- Use predictive modeling to forecast account performance.

---

## Contact Information:
**Shripad Kulkarni**  
- Email: [shripadkulkarni2212@gmail.com](mailto:shripadkulkarni2212@gmail.com)  
- LinkedIn: [Shripad Kulkarni](https://www.linkedin.com/in/shripad-kulkarni-candoit)  
- GitHub: [Shripad Kulkarni](https://github.com/shripadk1999)  

