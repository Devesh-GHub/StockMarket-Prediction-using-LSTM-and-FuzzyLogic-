# 📈 Stock Market Prediction & Trading Recommendation System 🚀

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)
![Fuzzy Logic](https://img.shields.io/badge/Fuzzy--Logic-Neuro%20Inspired-brightgreen?style=flat-square)
![LSTM](https://img.shields.io/badge/LSTM-NeuralNet-orange?style=flat-square)
![License](https://img.shields.io/github/license/yourusername/repo-name)
![Stars](https://img.shields.io/github/stars/yourusername/repo-name?style=social)

> ⚡ **Hybrid soft computing model that uses LSTM + Fuzzy Logic to predict stock trends and make smart trading decisions.**  
> 📊 Technical indicators + deep learning + fuzzy rules = next-gen portfolio intelligence!

---

## 🔥 Features

✅ Predicts future stock prices using an LSTM model  
✅ Uses fuzzy logic on RSI, MACD, ADX, and OBV to analyze market sentiment  
✅ Makes real-time trading decisions (BUY / SELL / HOLD)  
✅ Accepts live input for current price  
✅ Includes test scenarios (bullish, bearish, neutral)  
✅ Modular code, easy to extend and plug in more features  

---

## 💡 Project Idea

This project is built on the idea of **combining neural networks and fuzzy inference systems** for a **more human-like** trading decision engine. While the LSTM predicts the next price, fuzzy logic interprets market indicators like an expert trader would.

The goal?  
> 📈 **“Buy low, sell high” - with logic, not luck.**

---

## 🧠 Technologies Used

| Tool/Library      | Role                      |
|------------------|---------------------------|
| `scikit-fuzzy`    | Fuzzy logic system        |
| `TensorFlow/Keras`| LSTM prediction model     |
| `NumPy`, `Pandas` | Data handling             |
| `Matplotlib`      | Visualization (optional)  |
| `yfinance`        | Stock data (optional)     |

---

## 🔁 System Workflow

```mermaid
graph TD
A[📉 Technical Indicators] --> B[Fuzzy Logic System]
A2[LSTM Input Window] --> C[LSTM Model]
C --> D[📈 Predicted Price]
B --> E[Fuzzy Output Score]
D --> F[Price Change %]
E --> G[Decision Logic]
F --> G
G --> H[📢 Final Action: BUY / HOLD / SELL]
