# Trader Performance & Market Sentiment Analysis

## 📊 Project Overview
This project analyzes high-frequency trading performance to determine if market sentiment (measured by the Fear & Greed Index) acts as a reliable filter for trading strategies. By merging trade logs with sentiment data, we identify specific conditions where the strategy outperforms.

## 📂 Files Included
* `Trader_Performance_Analysis.ipynb`: The main analysis code.
* `historical_data.csv`: Anonymized trading logs (PnL, Time, Direction).
* `fear_greed_index.csv`: Daily market sentiment values.

## 🛠️ Tech Stack
* Python 3.11+
* Pandas (Data manipulation)
* Matplotlib / Seaborn (Visualization)

## 💡 Key Insights
1.  **Optimal Long Entry:** The strategy is most profitable on Long positions during **Extreme Fear** (Buy the dip).
2.  **Optimal Short Entry:** Short positions perform best during **Neutral** sentiment (Rejection/Choppiness).
3.  **Highest Consistency:** The highest win rate (88.1%) occurs during **Extreme Greed**.

## 🚀 How to Run
1.  Clone the repository.
2.  Ensure both CSV files are in the same directory as the notebook.
3.  Run `Trader_Performance_Analysis.ipynb` in Jupyter Lab or VS Code.
