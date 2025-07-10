# 📈 Stock Price Prediction Using Machine Learning

This project predicts the *closing price* of Apple Inc. (AAPL) stock using historical stock market data and machine learning models.

---

## 🧠 Objective

To build a machine learning pipeline that predicts the *closing price* of AAPL stock using past historical data.

---

## 📁 Dataset

- *Source*: [Apple (AAPL) Historical Stock Data — Kaggle](https://www.kaggle.com/datasets/tarunpaparaju/apple-aapl-historical-stock-data)
- *Fields Used*:
  - Date
  - Close

---

## 🛠 Tools & Libraries

- Python
- Pandas, NumPy
- Scikit-learn (Linear Regression, Random Forest)
- TensorFlow/Keras (LSTM)
- Matplotlib, Seaborn (visualization)

---

## 🧪 Models Implemented

1. *Linear Regression*
2. *Random Forest Regressor*
3. *LSTM (Long Short-Term Memory Neural Network)*

---

## 🧹 Data Preprocessing

- Parsed dates and sorted by time
- Filled missing values using forward fill
- Scaled Close prices using MinMaxScaler (important for LSTM)
- Converted data to supervised learning format:
  - For traditional models: previous day → next day
  - For LSTM: sequences of 60 timesteps

---

## 📊 Evaluation Metric

- *Root Mean Squared Error (RMSE)* used to evaluate model accuracy

---

## 📈 Results Visualization

A plot showing *Actual vs Predicted* closing prices is provided for each model:
- Linear Regression
- Random Forest
- LSTM

---

## 📌 How to Run

1. Open the Jupyter Notebook (.ipynb) file in *Google Colab*.
2. Upload the AAPL.csv dataset from Kaggle.
3. Run each cell sequentially to train the models and visualize results.

---

## ✅ Output Example

- RMSE comparison
- Time series plot of actual vs predicted prices

---

## 📦 Requirements

Install dependencies using:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn tensorflow
