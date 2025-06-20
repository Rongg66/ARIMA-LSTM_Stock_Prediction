# Nikkei 225 Stock Price Prediction using ARIMA and LSTM

## 🔍 Project Overview
This project aims to predict Nikkei 225 stock prices using both ARIMA and LSTM models, and compare their performance.

## 📊 Techniques Used
- ARIMA (AutoRegressive Integrated Moving Average)
- LSTM (Long Short-Term Memory)
- Python (Pandas, NumPy, Matplotlib, Statsmodels, PyTorch)

## 📁 Repository Structure
- `notebooks/`: Jupyter notebooks for EDA and model training
- `scripts/`: Python scripts to clean data and train models
- `results/`: Prediction visualizations and RMSE comparison

## 📈 Results
- RMSE of ARIMA: 1702.7590975217995
- RMSE of LSTM: 1641.1808758336801
- LSTM outperformed ARIMA due to its ability to capture long-term dependencies.

## 📌 How to Run
```bash
pip install -r requirements.txt
python scripts/train_arima.py
python scripts/train_lstm.py
