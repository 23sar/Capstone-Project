# 🚗 Dynamic Pricing for Urban Parking Lots

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-green?style=for-the-badge&logo=pandas">
  <img src="https://img.shields.io/badge/NumPy-Numerical%20Computing-orange?style=for-the-badge&logo=numpy">
  <img src="https://img.shields.io/badge/Pathway-Streaming-purple?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge">
</p>

---

## 📌 Overview

A data-driven system to dynamically adjust parking prices based on real-time demand factors like occupancy, queue length, traffic, and competition.
The goal is to improve parking utilization and reduce congestion in urban areas.

---

## 🎯 Key Highlights

* 📈 Dynamic pricing based on demand
* ⚡ Real-time-like streaming simulation
* 🧠 Multi-model pricing strategy
* 🌍 Competitive pricing using location
* 📊 Data visualization and analysis

---

## ⚙️ Models Implemented

### 🔹 Model 1 — Linear Pricing

* Price increases with occupancy
* Simple and stable baseline

---

### 🔹 Model 2 — Demand-Based Pricing

Uses:

* Occupancy rate
* Queue length
* Traffic
* Special day
* Vehicle type

📌 Pricing formula:

```
Price = BasePrice × (1 + λ × Demand)
```

---

### 🔹 Model 3 — Competitive Pricing

* Uses latitude & longitude
* Adjusts price based on nearby parking lots
* Prevents overpricing and improves competitiveness

---

## 📊 Results & Insights

### 📈 Price Trends

* Model 1 avg price: **~12.55**
* Model 2 avg price: **~11.99**
* Model 2 shows higher responsiveness

### 📊 Demand Observations

* Avg occupancy: **~50%**
* Peak occupancy: **>90%**
* Queue avg: **~4.6 vehicles**

### ⚖️ Price Stability

* Model 1: **10.5 → 14.7**
* Model 2: **10.0 → 15.0**
* Smooth variations, no extreme spikes

### 🧠 Key Takeaways

* Higher demand → higher price
* Queue = unmet demand signal
* Traffic reduces accessibility
* Competitive pricing improves balance

---

## 📂 Project Structure

```
Capstone-Project/
│
├── Dynamic_Pricing_Parking.ipynb
├── dataset.csv
├── results/
│   ├── model1_prices.csv
│   └── model2_prices.csv
├── README.md
└── problem statement.pdf
```

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Pathway
* Bokeh / Matplotlib

---

## 🚀 How to Run

1. Open notebook in Google Colab
2. Upload dataset.csv
3. Run all cells
4. View pricing outputs and plots

---

## 🔮 Future Improvements

* Real-time deployment
* ML-based demand prediction
* Reinforcement learning pricing
* Smart rerouting system

---

## 👨‍💻 Author

**Sarthak Singh**
IIEST Shibpur
