# 📈 Apple Stock Price Prediction using LSTM

A deep learning project that predicts Apple (AAPL) stock prices using historical data from 2015 to 2024, leveraging a stacked LSTM model.

## 🚀 Features
- Data from Yahoo Finance using `yfinance`
- Preprocessing with scaling and time-series windowing
- Stacked LSTM model using TensorFlow/Keras
- RMSE evaluation for training and test sets
- Predicts next 30 days of prices
- Beautiful visualizations for model predictions

## 🧠 Tech Used
- Python
- TensorFlow / Keras
- yfinance / pandas / numpy
- MinMaxScaler (sklearn)
- Matplotlib

## 📊 Model Architecture
- 3 stacked LSTM layers (50 units each)
- 1 Dense output layer
- Trained for 100 epochs with batch size of 64

## 📈 Results
- RMSE on training and test sets
- Next 30 days predicted and plotted

## 📚 What I Learned
- Time-series forecasting with LSTM
- Sequence generation for supervised learning
- Scaling and inverse transformations
- Recursive prediction logic

## 🔮 Future Improvements
- Use more features (Volume, Open, High, Low)
- Hyperparameter tuning
- Use GRU or attention mechanisms
- Deploy with Streamlit for UI

## 🧑‍💻 How to Run
```bash
pip install yfinance pandas matplotlib scikit-learn tensorflow
python stock_lstm.py
