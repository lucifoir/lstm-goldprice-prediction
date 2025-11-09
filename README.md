# Gold Price Prediction using LSTM

This project predicts **daily gold futures (GC=F)** prices using **LSTM-based deep learning architectures** to model temporal dependencies in financial time series data.

---

## Best Model
**Vanilla LSTM** — Test RMSE: **54.52**, MAPE: **1.50 %**

---

## Overview
Using historical gold price data from **Yahoo Finance**, this notebook demonstrates:

- Time-series preprocessing and normalization  
- Sequence generation for supervised learning  
- Training and evaluation of multiple architectures:
  - Vanilla LSTM  
  - Bidirectional LSTM  
  - LSTM with Attention  
- Visualization of predicted vs. actual prices  
- Comparative performance analysis (RMSE & MAPE)

---

## Frameworks
TensorFlow · Keras · Scikit-learn · Pandas · Matplotlib · Seaborn · yFinance

---

## Dataset
[Gold Futures (GC=F) — Yahoo Finance](https://finance.yahoo.com/quote/GC=F)  
Daily prices (Open, High, Low, Close, Volume) from **2001–2025**.  
Only the **Close** price is used as the prediction target.

---

## Contents
- `1_LSTM_GoldPricePrediction.ipynb` — main notebook  
- `requirements.txt` — dependencies  
- `README.md` — project overview  
- `.gitignore` — ignored files for clean commits

---

### Insights
- **Vanilla LSTM** achieved the best overall performance and stability.  
- **Bidirectional LSTM** captures turning points better but with slightly higher error.  
- **LSTM + Attention** underperformed in this setup, indicating the need for further tuning.

---

© 2025 — Developed using Python & TensorFlow
