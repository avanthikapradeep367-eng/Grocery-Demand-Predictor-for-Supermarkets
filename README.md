# 🛒 Grocery Demand Predictor for Supermarkets

A machine learning–based system that predicts **7-day grocery demand** for multiple products and generates **reorder recommendations** to prevent stock-outs. The project uses historical sales patterns along with contextual signals such as weather, holidays, and promotional offers, and presents insights through an interactive dashboard.

---

## 📌 Problem Statement
Supermarkets often face inventory challenges such as overstocking or stock-outs due to fluctuating demand. This project addresses the problem by forecasting short-term demand and recommending timely reorders using data-driven techniques.

---

## 🚀 Key Features
- Predicts **7-day future demand** for grocery products
- Trains **separate machine learning models per product**
- Generates **reorder alerts** based on current stock levels
- Visualizes historical trends and forecasts
- Interactive **Streamlit dashboard** for decision support
- Compares forecasted demand with historical averages

---

## 🛠 Tech Stack
- **Python**
- **Pandas**
- **Scikit-learn**
- **Matplotlib**
- **Streamlit**

---

## 🧾 Products Included
- Rice  
- Milk  
- Bread  

---

## ⚙️ Machine Learning Details
- **Training Data**:  
  Auto-generated dataset covering **1 year (365 days × 3 products)**
- **Model Used**:  
  Random Forest Regressor (one model per product)
- **Prediction Horizon**:  
  7 days
- **Inputs**:
  - Historical demand
  - Temperature
  - Holiday indicator
  - Offer/discount indicator

---

## 📊 Dashboard Capabilities
- Set temperature, holiday, and offer status for the next 7 days
- View demand forecast for each product
- Display **“OK”** or **“REORDER”** alerts
- Visualize 1-year historical sales trends
- Compare forecast vs historical average demand

---

## ▶️ How to Run Locally

### 1. Install dependencies
```bash
pip install -r requirements.txt

