# Web3 Trading Team - Data Science Assignment

## Trader Behavior vs Market Sentiment Analysis

This repository contains the complete data science assignment analyzing the relationship between trader behavior and market sentiment using Bitcoin Fear & Greed Index and Hyperliquid trading data.

---

## 📊 Project Overview

**Objective:** Analyze how trading behavior (profitability, risk, volume, leverage) aligns or diverges from overall market sentiment (fear vs greed).

**Key Finding:** Strong positive correlation (0.8061) between market sentiment and trading volume, indicating sentiment-driven trading behavior.

---

## 📁 Repository Structure

```
ds_ragha/
├── notebook_1.ipynb              # Main analysis notebook (Google Colab)
├── csv_files/                    # Data outputs directory
│   ├── daily_sentiment.csv
│   ├── daily_trading_stats.csv
│   └── merged_analysis_data.csv
├── outputs/                      # Visualization outputs
│   ├── sentiment_trading_analysis.png
│   ├── sentiment_over_time.png
│   ├── volume_sentiment_correlation.png
│   ├── pnl_sentiment_analysis.png
│   └── trading_metrics_by_sentiment.png
├── ds_report.pdf                 # Final analysis report
├── README.md                     # This file
└── requirements.txt              # Python dependencies
```

---

## 🔗 Google Colab Notebook

**Main Analysis Notebook:** [Web3_Trading_Analysis_Ragha](https://colab.research.google.com/drive/1sWFBPKvKNULceV68gbBNzlhi0Vb0RK4Q)

- Access: Anyone with the link can view
- Contains: Data loading, EDA, analysis, visualizations, and comprehensive report

---

## 📈 Key Findings

### 1. Sentiment & Trading Volume Correlation
- **Correlation: 0.8061** (Strong Positive)
- As market sentiment increases (fear to greed), trading volume increases significantly
- Traders are more active during bullish (greedy) market periods

### 2. Trading Frequency vs Sentiment
- **Correlation: -0.1783** (Weak Negative)
- Higher sentiment correlates with fewer but larger trades
- Risk management: More frequent smaller trades during fear periods

### 3. Profitability Analysis
- **Correlation: -0.0020** (Nearly Zero)
- Traders maintain consistent returns regardless of market sentiment
- Indicates effective risk management across all market conditions

### 4. Sentiment Classification Breakdown
- **Extreme Fear:** Sentiment Value 18.22
- **Fear:** Sentiment Value 31.90
- **Neutral:** Sentiment Value 49.89
- **Greed:** Sentiment Value 68.47
- **Extreme Greed:** Sentiment Value 79.33

---

## 📊 Datasets Used

1. **Bitcoin Market Sentiment Dataset** (2,644 records)
   - Columns: Date, Classification (Fear/Greed), Sentiment Value
   - Source: [Drive Link](https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing)

2. **Historical Trader Data from Hyperliquid** (211,224 transactions)
   - Columns: Account, Symbol, Execution Price, Size, Side, Timestamp, PnL, Leverage, etc.
   - Source: [Drive Link](https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing)

---

## 🔧 Setup Instructions

### Prerequisites
- Python 3.7+
- Google Colab (for interactive analysis)
- Required Libraries: pandas, numpy, matplotlib, seaborn

### Quick Start

1. **Access the Analysis:**
   - Open the [Google Colab Notebook](https://colab.research.google.com/drive/1sWFBPKvKNULceV68gbBNzlhi0Vb0RK4Q)
   - All code is ready to run
   - Datasets are automatically loaded from Google Drive

2. **Run Locally (Optional):**
   ```bash
   # Clone repository
   git clone https://github.com/raghav1902/ds_ragha.git
   cd ds_ragha
   
   # Install dependencies
   pip install -r requirements.txt
   
   # Run analysis
   jupyter notebook notebook_1.ipynb
   ```

---

## 📈 Analysis Highlights

### Correlation Analysis
```
Sentiment vs Trading Volume:     0.8061 ✓ Strong Positive
Sentiment vs Trade Frequency:   -0.1783   Weak Negative  
Sentiment vs Total PnL:         -0.0718   Near Zero
Sentiment vs Average PnL:       -0.0020   Near Zero
```

### Trading Statistics
- **Analysis Period:** 449 days of merged data
- **Total Transactions:** 211,224 trades analyzed
- **Average Daily Volume:** ~47,000 tokens
- **PnL Performance:** Consistent across sentiment cycles

---

## 📊 Visualizations

Four comprehensive visualizations included:

1. **Market Sentiment Over Time** - Line chart with min/max range
2. **Sentiment vs Trading Volume** - Scatter plot showing strong correlation
3. **Daily PnL Over Time** - Color-coded by sentiment classification
4. **Average PnL by Sentiment** - Bar chart comparing performance

---

## 🎯 Strategic Insights

1. **Sentiment-Driven Volume:** Strong correlation suggests sentiment-aware trading strategies are viable
2. **Risk Management:** Consistent profitability indicates effective risk distribution
3. **Trading Behavior:** Position-sizing adjusts based on market conditions
4. **Market Timing:** Volume and trade count divergence suggests position-sizing opportunities

---

## 📝 Requirements

```
pandas>=1.3.0
numpy>=1.21.0
matplotlib>=3.4.0
seaborn>=0.11.0
```

---

## ✅ Submission Compliance

This repository follows all assignment requirements:

- ✓ Root directory named `ds_ragha`
- ✓ Google Colab notebook with "Anyone with the link can view" access
- ✓ CSV files directory with processed data
- ✓ Outputs directory with visualizations (PNG/JPG)
- ✓ Comprehensive README with setup instructions
- ✓ All code shared as Google Colab links
- ✓ Repository structure matches assignment specification

---

## 📧 Contact & Information

**Candidate:** Raghav Kakrania
**Email:** 2023btechaidsraghav15996@poornima.edu.in
**GitHub:** [raghav1902](https://github.com/raghav1902)
**Assignment:** Web3 Trading Team - Data Science Position

---

## 📄 License

This project is part of the Web3 Trading Team hiring process.

---

**Last Updated:** December 30, 2025

**Status:** ✅ Complete and Ready for Evaluation
