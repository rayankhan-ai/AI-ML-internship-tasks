# 📈 Task 2: Stock Price Prediction (Short-Term)

## 🎯 Objective
To predict the next day's closing price of Apple stock using historical market data and machine learning models.

---

## 📊 Dataset Used
- **Source:** Yahoo Finance (via yfinance library)
- **Stock:** Apple Inc. (AAPL)
- **Time Period:** Jan 2023 – Jan 2024
- **Features Used:**
  - Open
  - High
  - Low
  - Volume
- **Target:**
  - Close Price

---

## ⚙️ Steps Performed

### 🔹 Data Collection
- Retrieved stock data using `yfinance` API
- Loaded into a pandas DataFrame

### 🔹 Data Inspection
- Checked dataset shape, columns
- Verified missing values and duplicates
- Used `.info()` and `.describe()` for summary

### 🔹 Feature Engineering
- Selected features: Open, High, Low, Volume
- Target variable: Close
- Applied StandardScaler for normalization

### 🔹 Train-Test Split
- 80% training data
- 20% testing data

---

## 🤖 Models Applied

### 1. Linear Regression
- Simple regression model
- Accuracy: ~99%

### 2. Random Forest Regressor
- Ensemble learning model
- Accuracy: ~99.8%
- Performed better than Linear Regression

---

## 📈 Model Evaluation
- Metrics used:
  - Mean Squared Error (MSE)
  - R² Score
  - Accuracy

### Results:
- Random Forest achieved lower error and higher accuracy
- Predictions closely matched actual stock prices

---

## 📊 Visualizations
- Actual vs Predicted Prices (Linear Regression)
- Actual vs Predicted Prices (Random Forest)
- Combined comparison plot

---

## 📌 Key Findings
- Strong relationship between input features and closing price
- Random Forest model provided the most accurate predictions
- Predictions closely follow real market trends

---

## 🛠️ Tools & Libraries
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- yfinance  

---

## 📂 Project Structure
task2_stock_prediction/
│── stock_prediction.py  
│── README.md  

---

## 🚀 Conclusion
This project demonstrates how machine learning models can be applied to financial data for short-term stock price prediction, with Random Forest outperforming Linear Regression.
