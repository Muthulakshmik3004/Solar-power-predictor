# 🔆 Solar Power Generation Forecasting App

This project is a **machine learning-based web app** built using **Streamlit** that predicts the amount of solar power (in kW) generated based on environmental and meteorological conditions.

---

## 🚀 Live Demo

👉 [Launch the App](https://your-app-link.streamlit.app) *(after deployment)*

---

## 📊 Problem Statement

With increasing reliance on renewable energy, predicting solar power generation in real time helps optimize energy distribution and grid operations.

This project aims to:
- Use environmental parameters to predict solar power output
- Provide a simple and accurate forecasting tool for solar farms or energy managers

---

## 🧠 Machine Learning Model

- **Algorithm Used:** Random Forest Regressor
- **Evaluation Metrics:**
  - MAE (Mean Absolute Error)
  - RMSE (Root Mean Squared Error)
  - R² Score

---

## 📦 Tech Stack

| Tool | Purpose |
|------|---------|
| `Streamlit` | Web UI for input and prediction |
| `Scikit-learn` | ML model building and evaluation |
| `Pandas` & `NumPy` | Data preprocessing |
| `Matplotlib/Seaborn` | EDA & visualization |
| `Joblib` | Save/load ML model |

---

## 🖥️ Features

✅ Real-time prediction of solar power  
✅ Input interface for 20+ environmental parameters  
✅ Clean and responsive UI with CSS styling  
✅ Lightweight, runs in browser  
✅ No external API needed  

---

## 📁 Files

- `app.py` – Streamlit frontend
- `solar_power_model.pkl` – Trained ML model
- `requirements.txt` – Python dependencies
- `spg.csv` – Dataset used (optional, not needed to run the app)
- `README.md` – Project description

---

## ⚙️ How to Run Locally

```bash
git clone https://github.com/your-username/solar-power-forecast.git
cd solar-power-forecast
pip install -r requirements.txt
streamlit run app.py
