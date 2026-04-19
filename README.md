# 🚗 Dynamic Pricing for Urban Parking Lots

## 📌 Overview

This project implements a dynamic pricing system for urban parking spaces based on real-time demand factors such as occupancy, queue length, traffic conditions, and competition. The objective is to optimize parking utilization and reduce congestion through adaptive pricing.

---

## 🎯 Objectives

* Dynamically adjust parking prices based on demand
* Prevent overcrowding and underutilization
* Incorporate real-world features like traffic and queue
* Simulate intelligent pricing strategies

---

## ⚙️ Models Implemented

### 🔹 Model 1: Baseline Linear Model

* Price increases with occupancy
* Simple and stable reference model

### 🔹 Model 2: Demand-Based Pricing

Demand is computed using:

* Occupancy rate
* Queue length
* Traffic level
* Special day indicator
* Vehicle type

**Pricing Function:**
Price = BasePrice × (1 + λ × Demand)

---

### 🔹 Model 3: Competitive Pricing

* Uses location (latitude & longitude)
* Adjusts price based on nearby parking lots
* Ensures competitive and realistic pricing

---

## 📊 Results & Insights

### 🔹 Price Behavior

* Model 1 average price: **~12.55**
* Model 2 average price: **~11.99**
* Model 2 shows greater variation due to multiple demand factors

### 🔹 Demand Patterns

* Average occupancy: **~50%**
* Peak occupancy: **>90%**
* Average queue length: **~4.6 vehicles**

### 🔹 Feature Impact

* Higher occupancy and queue → higher prices
* Traffic (avg ~0.8) slightly reduces demand
* Special days (~15%) increase demand spikes

### 🔹 Price Stability

* Model 1 range: **~10.5 – 14.7**
* Model 2 range: **~10.0 – 15.0**
* No extreme fluctuations → smooth pricing behavior

### 🔹 Overall Outcome

* System adapts effectively to demand changes
* Improves parking utilization
* Prevents congestion through pricing control

---

## 📁 Project Structure

Capstone-Project/

├── Dynamic_Pricing_Parking.ipynb
├── dataset.csv
├── results/
│   ├── model1_prices.csv
│   └── model2_prices.csv
├── README.md
└── problem statement.pdf

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Pathway (stream simulation)
* Bokeh / Matplotlib (visualization)

---

## 🚀 How to Run

1. Open notebook in Google Colab
2. Upload `dataset.csv`
3. Run all cells
4. View pricing outputs and plots

---

## 🧠 Key Assumptions

* Higher occupancy → higher demand
* Queue length represents unmet demand
* Traffic reduces accessibility
* Competitor pricing influences user decisions

---

## 🔮 Future Improvements

* Real-time deployment using streaming APIs
* Machine learning-based demand prediction
* Reinforcement learning for pricing optimization
* Integration with navigation systems

---

## 👨‍💻 Author

Sarthak Singh
IIEST Shibpur
