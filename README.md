 # 📊 Trader Intelligence Dashboard

A data-driven application that analyzes trader behavior based on market sentiment (Fear vs Greed) and predicts trading outcomes.

---

## 🚀 Live App
👉 https://sentiment-trading-dashboard.streamlit.app/

---

## 🎯 Objective

To analyze how market sentiment impacts trader behavior and performance, and derive actionable trading strategies.

---

## 📂 Dataset

- Bitcoin Fear & Greed Index
- Hyperliquid Trader Data

---

## ⚙️ Features

### 🔮 1. Trade Outcome Prediction
Predicts whether a trade is likely to be profitable using:
- Trade size
- Direction (Long/Short)
- Sentiment (Fear/Greed)
- Historical performance metrics

---

### 📈 2. Next-Day Profitability Prediction
Classifies traders into:
- Loss
- Neutral
- Profit

---

### 👥 3. Trader Clustering
Segments traders into:
- Conservative
- Aggressive
- High-frequency

---

## 🧠 Models Used

- Random Forest Classifier
- KMeans Clustering
- StandardScaler (feature normalization)

---

## 🛠️ Tech Stack

- Python
- Pandas / NumPy
=======
# Trader Performance vs Market Sentiment

## 🔍 Objective
Analyze how market sentiment (Fear/Greed) influences trader behavior and profitability.

---

## 🚀 Live Application
👉 https://your-app.streamlit.app

---

## 🧠 Key Features
- Trade Outcome Prediction (ML)
- Next-Day Profit Forecasting
- Trader Behavioral Clustering
- Interactive Streamlit Dashboard

---

## 🧪 Methodology
- Data cleaning & alignment (daily level)
- Feature engineering (behavioral + sentiment)
- Segmentation analysis
- ML models: Logistic Regression, Random Forest, KNN

---

## 📈 Key Insights
- Greed → higher returns but higher volatility  
- High-frequency trading → lower win rate  
- Large trades ≠ guaranteed profitability  

---

## 🎯 Strategy Recommendations
- Reduce exposure during Fear periods  
- Control leverage during Greed phases  
- Avoid overtrading for stable performance  

---

## ⚙️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Streamlit

---

 ## 📦 Deployment Strategy

Model files are **not stored in GitHub** due to size constraints.

Instead, they are:
- Hosted on Google Drive
- Downloaded dynamically at runtime

---

## ▶️ How to Run Locally

=======
## ▶️ Run Locally
```bash
pip install -r requirements.txt
streamlit run app.py