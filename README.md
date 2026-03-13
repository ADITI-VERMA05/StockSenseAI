# StockSenseAI
# 📈 Stock Price Trend Prediction using LSTM

Predicting stock market trends using **Deep Learning (LSTM)** based on historical stock data and technical indicators.

---

## 📌 Project Overview

Stock markets generate massive amounts of time-series data every day. Accurately predicting future stock prices can assist investors in making informed decisions.

This project implements a **Long Short-Term Memory (LSTM) neural network** to analyze historical stock price data and predict future trends. The model is trained on past stock prices along with technical indicators like **Moving Average (MA)** and **Relative Strength Index (RSI)** to improve prediction accuracy.

---

## 🎯 Objective

* Fetch historical stock data using Yahoo Finance API
* Preprocess and normalize stock price data
* Extract technical indicators (Moving Average & RSI)
* Build and train an **LSTM deep learning model**
* Predict future stock prices
* Visualize predicted vs actual stock prices
* (Optional) Deploy an interactive dashboard using Streamlit

---

## 🛠️ Tech Stack

| Category             | Tools Used                   |
| -------------------- | ---------------------------- |
| Programming Language | Python                       |
| Deep Learning        | TensorFlow / Keras           |
| Data Processing      | Pandas, NumPy                |
| Visualization        | Matplotlib                   |
| Financial Data       | Yahoo Finance API (yfinance) |
| Technical Indicators | TA library                   |
| Model Deployment     | Streamlit (optional)         |

---

## 📊 Dataset

Stock data is fetched using the **Yahoo Finance API**.

Example Stock Used:

* Apple (AAPL)

Features used for training:

* Closing Price
* 20-Day Moving Average (MA20)
* Relative Strength Index (RSI)

---

## ⚙️ Project Workflow

1️⃣ Data Collection
Fetch historical stock price data using **yfinance API**

2️⃣ Data Preprocessing

* Handle missing values
* Feature selection
* Normalize data using MinMaxScaler

3️⃣ Feature Engineering

* Moving Average (MA)
* Relative Strength Index (RSI)

4️⃣ Dataset Preparation
Convert time-series data into sequences suitable for **LSTM**

5️⃣ Model Development
Build an **LSTM neural network using Keras**

6️⃣ Model Training
Train the model using historical stock data

7️⃣ Model Evaluation
Compare predicted stock prices with actual values

8️⃣ Visualization
Plot predictions vs real stock prices

---

## 🧠 LSTM Model Architecture
```
Input Layer
⬇
LSTM Layer (50 units)
⬇
Dropout Layer
⬇
LSTM Layer (50 units)
⬇
Dense Layer
⬇
Output Layer (Predicted Price)
```
---

## 📈 Results

The model learns historical stock trends and predicts future price movement.

Visualization includes:

* Historical stock price trend
* Moving average indicator
* Predicted vs Actual stock price comparison

Example Output:

```
Actual Price vs Predicted Price Graph
```

*(Add your graph image here once generated)*

---

## 📂 Project Structure

```
stock-price-trend-prediction-lstm
│
├── notebook
│   └── stock_prediction.ipynb
│
├── models
│   └── lstm_stock_model.h5
│
├── data
│   └── stock_data.csv
│
├── streamlit_app
│   └── app.py
│
├── images
│   └── prediction_graph.png
│
├── requirements.txt
└── README.md
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/ADITI-VERMA05/StockSenseAI.git
cd stock-price-trend-prediction-lstm
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Run the Jupyter Notebook

```
stock_prediction.ipynb
```

(Optional) Run Streamlit Dashboard

```bash
streamlit run app.py
```

---

## 📊 Example Visualization

*(Insert images of graphs here)*

* Stock Price Trend
* Moving Average Indicator
* Predicted vs Actual Price

---

## 🔮 Future Improvements

* Multi-stock prediction
* Add more indicators (MACD, Bollinger Bands)
* Use **Bidirectional LSTM**
* Implement **Attention Mechanism**
* Deploy full web app with Streamlit

---

## 👩‍💻 Author

**Aditi Verma**

Data Science | Machine Learning | AI Projects

---

## 📜 License

This project is open-source and available under the **MIT License**.

---

⭐ If you found this project useful, consider giving it a **star** on GitHub!
