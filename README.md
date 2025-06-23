# 📊 Market Sentiment vs Trader Performance Analysis

This project explores how Bitcoin market sentiment — measured using the Fear & Greed Index — affects trader behavior and profitability. We analyze historical trading data from Hyperliquid and match it with daily sentiment classification to derive actionable insights.

---

## 📁 Project Structure

```
market-sentiment-vs-trader-performance/
├── sentiment_analysis.ipynb       ← Full analysis notebook (cleaned + visualized)
├── README.md                      ← Project overview and instructions
├── data/
│   ├── fear_greed_index.csv       ← Daily sentiment classification (Fear/Greed)
│   └── historical_data.csv        ← Hyperliquid trade-level data
├── plots/
│   ├── avg_pnl_by_sentiment.png   ← Bar chart: Avg Closed PnL by sentiment
│   ├── pnl_distribution_boxplot.png ← Box plot of PnL distribution
│   └── avg_size_by_sentiment.png  ← Bar chart: Avg trade size by sentiment
└── reports/
    └── final_report.pdf           ← (Optional) formatted report version
```

---

## 🔍 Objectives

- Merge Bitcoin sentiment data with real trading records
- Analyze how "Fear" or "Greed" influences:
  - Trade size
  - Profitability (Closed PnL)
  - Trader behavior patterns
- Generate visualizations to support findings
- Build a foundation for future predictive modeling

---

## 📊 Key Insights

- Traders performed **better/worse** during periods of **Fear/Greed**
- Trade sizes and leverage usage tend to **increase/decrease** based on sentiment
- Certain accounts consistently **profit/lose** during specific sentiment phases

> ✅ Full visual analysis available in `sentiment_analysis.ipynb`

---

## 🧰 Tools & Libraries

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Git + GitHub for version control
- Optional: Streamlit for dashboard (future scope)

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/market-sentiment-vs-trader-performance.git
cd market-sentiment-vs-trader-performance
```

2. Install dependencies:
```bash
pip install pandas matplotlib seaborn
```

3. Launch the notebook:
```bash
jupyter notebook sentiment_analysis.ipynb
```

---

## 📝 License

This project is open-source under the [MIT License](LICENSE). Feel free to use and adapt for learning or research.

---

## 🙋‍♂️ Author

**Krishna Venugopal**  
*B.Tech AI & ML | Jain University*  
Email: krishnakichuz2004@gmail.com  
LinkedIn: [linkedin.com/in/krishnakichuz](https://linkedin.com/in/krishnakichuz)  
