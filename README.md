# 📈 Google Stock Price Predictor (LSTM)

This project uses a **Recurrent Neural Network (RNN)** with **Long Short-Term Memory (LSTM)** layers to predict the **closing stock price of Google (Alphabet Inc.)**.  
The dataset is taken from **Kaggle** and the model is built using **Keras & TensorFlow**.

---

## 🚀 Project Description

- The model is trained on historical stock price data of Google.
- It predicts the **future closing stock price** based on the previous 60 days.
- Uses **MinMaxScaler** for normalization and **LSTM layers** for time-series prediction.
- Visualizes actual vs predicted prices to evaluate model performance.
  
## ⚙️ Dependencies

Install the required Python libraries:

```bash
pip install numpy pandas matplotlib scikit-learn keras tensorflow pandas-datareader
