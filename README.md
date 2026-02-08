# 📈 Stock Price Prediction using Linear Regression

This project demonstrates a **basic stock price prediction model** using **Linear Regression** in Python. It uses historical stock closing prices and dates to train a regression model, evaluate its performance, visualize predictions, and forecast a future stock price.

---

## 🚀 Features

* Uses **pandas** for data handling
* Applies **scikit-learn** for machine learning
* Converts dates into **ordinal numeric values** for regression
* Evaluates the model using:

  * Mean Squared Error (MSE)
  * R² Score
* Visualizes **actual vs predicted stock prices** using **matplotlib**
* Predicts stock price for a future date

---

## 🧠 How It Works

1. Historical stock data (Date & Close price) is loaded into a DataFrame.
2. Dates are converted into ordinal numeric values to make them usable for linear regression.
3. The dataset is split into training and testing sets.
4. A **Linear Regression** model is trained on the training data.
5. Predictions are made on the test set.
6. Model performance is evaluated using MSE and R² score.
7. A line plot compares actual vs predicted prices.
8. The model predicts the stock price for a future date.

---

## 📂 Project Structure

```
├── stock_price_prediction.py
├── README.md
```

---

## 🛠️ Requirements

Make sure you have Python installed and install the required libraries:

```bash
pip install pandas scikit-learn matplotlib
```

---

## ▶️ How to Run

1. Clone the repository or download the script.
2. Navigate to the project directory.
3. Run the Python file:

```bash
python stock_price_prediction.py
```

---

## 📊 Sample Output

* Displays the stock price dataset
* Prints:

  * Mean Squared Error (MSE)
  * R² Score
* Shows a graph comparing actual and predicted prices
* Predicts stock price for a future date (e.g., **2022-01-11**)

---

## ⚠️ Disclaimer

This project is **for educational purposes only**. It uses a very small and synthetic dataset. Real-world stock price prediction requires:

* Large historical datasets
* Advanced time-series models (LSTM, ARIMA, Prophet, etc.)
* Consideration of market indicators and external factors

---


## 👨‍💻 Author

**Abdullah Ali**
Learning Python & Machine Learning 🚀

---

⭐ If you find this project helpful, feel free to star the repository!
