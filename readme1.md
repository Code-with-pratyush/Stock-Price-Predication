# Bitcoin Price Prediction and Trading Strategy 📈💹

## Overview 🌐

This Jupyter Notebook (`finalmodel.ipynb`) showcases a Bitcoin price prediction model using LSTM and a simulated trading strategy based on the predictions.

## Sections 📝

### 1. Data Loading and Preprocessing 📊

- **Libraries Used:**
  - 📚 `numpy`, `pandas`, `sklearn`, `keras`, `matplotlib`, `tensorflow`
- **Data Source:**

  - 📂 Historical Bitcoin price data loaded from a CSV file.

- **Data Preparation:**
  - 🔄 'Close' prices selected for analysis.
  - 🔍 Data normalized using Min-Max scaling.

### 2. LSTM Model Creation and Training ⚙️

- **Model Architecture:**
  - 🏗 Sequential model with Dense layers for regression.
- **Training:**
  - ⏳ Data split into training and validation sets.
  - 🔄 Model compiled using Adam optimizer and mean squared error loss.
  - 🚀 Training executed for a specified number of epochs and batch size.

### 3. Model Evaluation and Prediction Visualization 📉

- **Prediction:**
  - 📈 Model predictions made on the test dataset.
  - 🔙 Predictions inverse-transformed to the original scale.
- **Visualization:**
  - 📊 Actual and predicted prices plotted for visual evaluation.

### 4. Simulated Trading 🤖💰

- **Trading Strategy:**
  - 💼 Simulated trading based on predicted price movements.
  - 📊 Metrics calculated, including net profit, win rate, and more.

### 5. Metrics Calculation 📈📊

- **Trading Metrics:**
  - 💹 Metrics like net profit, win rate, sharpe ratio and max drawdown calculated.

### 6. Testing for Out-of-Sample Dataset 🧪🔄

- **Out-of-Sample Testing:**
  - 📊 Additional dataset loaded for testing.
  - 🔄 Model predictions and actual prices plotted for evaluation.
