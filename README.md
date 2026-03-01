# Trader Behavior & Market Sentiment Analysis

## Project Objective
Analyze how market sentiment impacts trader performance and build predictive + behavioral models.

---

## Dataset
- Trader transaction data
- Daily sentiment classification (Fear/Greed Index)

---

## Methodology
1. Data cleaning and preprocessing
2. Feature engineering (daily PnL, win rate, volatility proxy)
3. Sentiment-based regime analysis
4. Statistical testing
5. KMeans clustering (behavioral archetypes)
6. Logistic regression model for next-day profitability prediction

---

## Key Insights
- Performance differs significantly between Fear and Neutral regimes.
- Frequent traders underperform during Extreme Fear.
- Distinct behavioral clusters exhibit different risk profiles.

---

## Strategy Recommendations
- Reduce trade frequency during Fear regimes.
- Adjust position sizing dynamically based on sentiment.
- Avoid aggressive scaling in Extreme Greed.

---

## How to Run

1. Install dependencies:
   pip install -r requirements.txt

2. Run notebook:
   jupyter notebook analysis.ipynb

3. (Optional) Run dashboard:

   streamlit run app.py


## Data Note

Due to file size limitations, the raw dataset is not included in this repository.
Please contact me if access to the dataset is required.

