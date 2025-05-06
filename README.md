# Air Quality Prediction using LSTM

This project predicts PM2.5 levels using a deep learning model (LSTM) trained on historical air pollution and weather data.

## 📌 Problem
Air pollution is a serious threat to health. Predicting PM2.5 levels helps issue early warnings and reduce risks.

## 🔍 Methodology
- Data: Hourly air pollution dataset (Delhi, India)
- Features: PM2.5, TEMP, PRESSURE, DEWP
- Model: LSTM (Long Short-Term Memory)
- Evaluation: Mean Absolute Error (MAE), Root Mean Squared Error (RMSE)

## 📈 Results
The LSTM model accurately forecasts short-term PM2.5 trends and shows strong performance compared to traditional methods.

## 🚀 How to Run
1. Clone the repo
2. Install libraries: pip install -r requirements.txt
3. Run air_quality_lstm.ipynb in Jupyter or Colab

## 📊 Sample Output
Visual comparison of predicted vs actual PM2.5 values.

## 🧠 Libraries Used
TensorFlow, Keras, pandas, matplotlib, scikit-learn

## 📂 Dataset Source
Air Quality dataset from [Kaggle](https://www.kaggle.com/datasets)

## 📜 License
MIT License
