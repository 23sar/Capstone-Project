# 🚗 Dynamic Pricing for Urban Parking Lots

## 📌 Overview

This project implements a dynamic pricing system for urban parking spaces using real-time demand factors. The goal is to optimize parking utilization by adjusting prices based on occupancy, queue length, traffic conditions, and nearby competition.

---

## 🎯 Objectives

* Dynamically adjust parking prices in real-time
* Avoid overcrowding and underutilization
* Incorporate demand and competitive factors
* Simulate real-world pricing strategies

---

## ⚙️ Models Implemented

### 🔹 Model 1: Baseline Linear Model

* Price increases linearly with occupancy
* Serves as a simple reference model

### 🔹 Model 2: Demand-Based Pricing

Demand is calculated using:

* Occupancy rate
* Queue length
* Traffic level
* Special day indicator
* Vehicle type

📈 Price is updated using normalized demand:

```
Price = BasePrice × (1 + λ × Demand)
```

---

### 🔹 Model 3: Competitive Pricing Model

* Considers nearby parking lots using latitude & longitude
* Adjusts pricing based on competitor prices
* Helps maintain competitiveness in high-demand areas

---

## 📊 Features

* Real-time-like simulation using streaming logic
* Dynamic price updates at each time step
* Competitive pricing adjustments
* Data visualization using Bokeh

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Pathway (for streaming simulation)
* Bokeh (for visualization)

---

## 📈 Results & Insights

* Prices increase with higher occupancy and queue length
* Traffic conditions influence demand negatively
* Competitive pricing prevents overpricing and improves utilization
* System adapts smoothly without abrupt price changes

---

## 🚀 How to Run

1. Open the notebook in Google Colab
2. Upload `dataset.csv` when prompted
3. Run all cells sequentially
4. Observe dynamic pricing outputs and visualizations

---

## 📁 Project Structure

```
Capstone-Project/
│
├── Dynamic_Pricing_Parking.ipynb
├── dataset.csv
└── README.md
```

---

## 🧠 Key Assumptions

* Higher occupancy indicates higher demand
* Queue length represents unmet demand
* Traffic affects accessibility and reduces demand
* Competitor prices influence user choice

---

## 🔮 Future Improvements

* True real-time deployment using streaming APIs
* Advanced ML models for demand prediction
* Integration with navigation/routing systems
* Reinforcement learning for pricing optimization

---

## 👨‍💻 Author

Sarthak Singh
IIEST Shibpur
