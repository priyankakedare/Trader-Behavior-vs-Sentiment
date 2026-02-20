📊 Trader Performance vs Market Sentiment Analysis
🎯 Objective

This project analyzes how Bitcoin market sentiment (Fear/Greed Index) impacts trader behavior and performance on Hyperliquid.

The objective is to identify behavioral patterns across sentiment regimes and derive actionable, sentiment-aware trading strategies.

⚙️ Methodology
1️⃣ Data Preparation

Cleaned and validated trader and sentiment datasets

Checked for missing values and duplicates

Converted timestamps and aligned both datasets at a daily level

Engineered key metrics:

Daily Closed PnL

Win Rate

Trade Frequency

Average Position Size

2️⃣ Sentiment-Based Analysis

Compared profitability across sentiment regimes

Analyzed PnL volatility using distribution analysis

Evaluated behavioral changes in:

Trade frequency

Risk exposure (position size)

Long/Short directional bias

3️⃣ Trader Segmentation

Traders were segmented to examine differential behavior across sentiment regimes:

Large vs Small Position Traders

Frequent vs Infrequent Traders

Consistent vs Inconsistent Traders

Performance and risk sensitivity were analyzed across these segments.

4️⃣ Predictive Modeling (Bonus)

A Logistic Regression model was developed to predict daily profitability using:

Sentiment regime

Trade frequency

Average position size

📈 Model Accuracy: 79%

This demonstrates that sentiment combined with behavioral metrics has measurable predictive power.

🔎 Key Insights

Profitability is highest during Extreme Fear periods.

Greed phases show lower average returns despite slightly higher win rates.

Traders increase activity and exposure during Fear regimes.

Market sentiment has statistically meaningful predictive influence on daily profitability.

🚀 Strategy Recommendations
Strategy 1 — Controlled Aggression During Extreme Fear

Increase position size selectively during Extreme Fear periods while maintaining disciplined risk management.

Strategy 2 — Risk Reduction During Greed Phases

Reduce exposure and avoid excessive trading during Greed and Extreme Greed regimes to prevent overextension.
