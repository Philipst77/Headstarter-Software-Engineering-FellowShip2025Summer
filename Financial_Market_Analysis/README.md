# 📈 Market Anomaly Detection Tool

**Developed for the Headstarter AI Accelerator Program**  
**By Philip Stavrev**

## 🚀 Overview

This project is an intelligent anomaly detection platform built to identify unusual behaviors in financial markets using classical machine learning techniques. Designed as part of the **Headstarter AI Accelerator**, it provides traders, investors, and data scientists with a powerful interface to visualize outliers, analyze anomalies, and explore AI-driven insights and investment suggestions.

## 🎯 Objectives

- Detect and flag anomalous price behaviors in financial datasets.
- Visualize anomalies on interactive time series plots.
- Offer AI-powered investment insights through a financial chatbot.
- Enable strategic decision-making using market signals.

## 🛠 Features

### ✅ Anomaly Detection Models

- Isolation Forest  
- One-Class SVM  
- Local Outlier Factor (LOF)  

Each model helps detect price spikes, drops, or irregular movements in market data.

### 📊 Visualization

- **Anomaly Timeline Plot**: Shows outliers across the time series.
- **Anomaly Score Plot**: Visualizes the likelihood of each data point being an anomaly.

### 📈 Strategy Suggestions

- Offers preliminary investment strategies like **Buy**, **Sell**, or **Hold** based on anomaly trends *(experimental feature)*.

### 🤖 AI Financial Chatbot *(Powered by OpenAI GPT)*

- Responds to financial queries and explains anomalies.
- Assists users in making informed trading or investment decisions.

## 📂 Data Input

- Upload CSV or Excel files containing market data (e.g., stock prices, index data, trading volumes).
- Data is preprocessed automatically:
  - Missing values filled using column mean.
  - Data standardized using `StandardScaler`.

## 💻 How to Run

1. **Clone the repo**
   ```bash
   git clone https://github.com/Philipst77/financial-market-anomaly-detection.git
   cd financial-market-anomaly-detection
2. **Install Dependencies**

pip install -r requirements.txt

3. **Launch Streamlit app**
streamlit run app.py

4. **Use the app**

Upload your data (CSV/Excel).

Choose the detection model.

Adjust anomaly sensitivity with the slider.

View visualizations and use the chatbot for insight

## 🧠 Tech Stack

- **Python 3.x**
- **Scikit-learn** – anomaly detection models
- **Streamlit** – app interface
- **Plotly** – interactive visualizations
- **OpenAI GPT** – chatbot advisor
- **Pandas, NumPy** – data preprocessing
