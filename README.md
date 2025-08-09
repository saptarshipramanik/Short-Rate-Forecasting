# Short Rate Forecasting with Vasicek and CIR Models using LSTM

## 📌 Overview
This project simulates short-term interest rate paths using the **Vasicek** and **Cox-Ingersoll-Ross (CIR)** models and applies an **LSTM neural network** to forecast future rates. The goal is to demonstrate both **quantitative finance modeling** and **machine learning forecasting**.

---

## 📊 Models Used

### Vasicek Model
Mean-reverting model allowing negative rates.

### CIR Model
Mean-reverting model that ensures positive rates.

---

## 🔬 Methodology
1. Simulate interest rate paths from Vasicek and CIR models.
2. Format the simulated data for time-series forecasting.
3. Train an LSTM neural network for one-step-ahead prediction.
4. Evaluate forecasts with MAE, RMSE, and MAPE.
5. Visualize predictions against true values.

---

## 🚀 How to Run
1. Install dependencies:
pip install -r requirements.txt
2. Open the notebook:
jupyter notebook Short_Rate_Forecasting_Vasicek_CIR.ipynb
3. Run all cells in order.

---

## 📈 Results
You will see:
- Error metrics for Vasicek and CIR forecasts.
- Plots comparing predicted vs true short rates.

---

## 🛠 Future Improvements
- Calibrate parameters using real-world interest rate data.
- Compare with other ML models (e.g., GRU, ARIMA).
- Extend to pricing bonds or interest rate derivatives.

---

## 📜 License
This project is for educational purposes.
