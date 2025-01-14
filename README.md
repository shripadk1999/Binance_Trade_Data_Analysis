# Binance_Trade_Data_Analysis
Analysis of historical trade data from Binance accounts over a 90-day period, calculating financial metrics such as Return On Investment (ROI) , Profit and Loss (PnL) , Sharpe Ratio, and Maximum Drawdown (MDD) to rank accounts based on performance.

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
![Corelation Heat Map](https://github.com/user-attachments/assets/f104b9a0-ab41-4b94-b29f-6b36eb04bb0a)
![Distribution of MDD](https://github.com/user-attachments/assets/1c3e8672-2b43-4a85-ada9-e8524a8402ec)
![Distribution of Sharpe Ration](https://github.com/user-attachments/assets/f4830a24-3b4c-4ee1-b5d9-ff27328925c3)
![MDD vs PnL](https://github.com/user-attachments/assets/1f6cbeef-fdd4-4787-b660-8186431d06fb)
![ROI vs Sharpe Ratio](https://github.com/user-attachments/assets/86332172-862e-4d46-b69b-d6322805c7f6)
![Win Rate vs PnL ](https://github.com/user-attachments/assets/92929a65-7c9d-4fee-86c2-2c9f3cad9d42)
![Win Rate vs ROI](https://github.com/user-attachments/assets/0fd07e81-55c4-45ab-b6cd-6e9bf0c9695b)
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

