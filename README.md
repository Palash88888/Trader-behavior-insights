# Trader-behavior-insights
Trader Behavior Insights Based on Market Sentiment  This project analyzes trader behavior in the context of crypto market sentiment. Using historical trading data and sentiment classifications (Fear, Greed, Neutral, etc.), we merge and visualize the relationship between market emotions and actual trading outcomes. 

#  Trader Behavior Insights – Market Sentiment vs. Trader Performance

##  Objective

To analyze how Bitcoin market sentiment (Fear/Greed) affects trader behavior and performance, using real-world trading and sentiment data.

---

##  Approach

- **Step 1:** Cleaned and standardized column names across datasets.
- **Step 2:** Converted timestamps to datetime and aligned formats.
- **Step 3:** Merged Bitcoin market sentiment with trader activity based on trade dates.
- **Step 4:** Grouped trades by market sentiment (Fear/Greed) and calculated key performance metrics like average and total PnL.
- **Step 5:** Visualized average PnL per sentiment category using Seaborn.

---

##  Tools Used

- Python 
- Pandas 
- Matplotlib & Seaborn 
- Jupyter Notebook

---

## Insights Found

- 📈 **Greed** days tend to have higher average trader PnL than **Fear** days.
- 📉 The number of trades during **Fear** periods may be higher, but profitability per trade tends to drop.
- 🔄 Market sentiment can serve as a **useful signal** when analyzing trader performance patterns.

---

##  Files Included

- `Trader_Behavior_Insights.ipynb` – Jupyter Notebook with full analysis
- `avg_pnl_by_sentiment.png` – Screenshot of PnL bar plot
- `summary_table.png` – Screenshot of grouped PnL table
