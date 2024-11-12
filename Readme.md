# **Bitcoin Predictive Analytics** 📊🔮

Welcome to the **Bitcoin Predictive Analytics** project! This project utilizes predictive analytics techniques to forecast Bitcoin price movements. By leveraging both **numerical data** (time series) and **textual data** (sentiment analysis), we integrate these features into **machine learning models** to enhance forecasting accuracy. The models developed here utilize **Facebook Prophet** and other advanced techniques for robust price prediction.

---

## **Project Overview**

### **🔹 Model 1: Numerical Data Forecasting**

Model 1 utilizes only the **numerical features** from the Bitcoin dataset, such as historical prices, trading volume, and other key metrics. The primary goal of this model is to predict future Bitcoin prices based on **historical data patterns**.

- **Data Features Used**:
  - Price
  - Trading Volume
  - Open, High, Low
  - Other numerical time series data
- **Technique Used**:
  - **Facebook Prophet**: A powerful tool for time series forecasting that accounts for **trends**, **seasonality**, and **holiday effects**.
- **Objective**:
  - Develop a **baseline model** for Bitcoin price prediction using only numerical features.

---

### **🔹 Model 2: Numerical Data with Lag and Moving Average Variables**

Model 2 enhances Model 1 by incorporating additional features such as **lag variables** and **moving averages**. These features help identify trends and patterns in the time series data over different periods, thereby improving the accuracy of the forecast.

- **Additional Features**:

  - **Lag variables** (previous time steps)
  - **Moving averages** (Simple Moving Average & Exponential Moving Average)

- **Objective**:
  - Improve prediction accuracy by considering past time steps and smoothing data with moving averages.
- **Technique Used**:
  - **Facebook Prophet**: With advanced feature engineering techniques, including lag and moving averages.

---

## **Installation**

To get started with this project, follow the installation instructions below:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/Bitcoin-Predictive-Analytics.git
   ```

2. **Install the necessary dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

---

## **Usage**

### **1. Load the dataset** (`cleaned_data.csv`) into the script:

```python
import pandas as pd
data = pd.read_csv('cleaned_data.csv')
```

### **2. Model Execution**

- **For Model 1**: Run the baseline time series forecasting using **Facebook Prophet**. Follow the steps in `model_1.py`.

- **For Model 2**: Run the enhanced model with **lag and moving average features**. Follow the steps in `model_2.py`.

### **3. Observe the predictions for Bitcoin prices**.

---

## **Results**

- **Model 1**: Provides **baseline predictions** based solely on historical data.
- **Model 2**: Improves **predictive accuracy** by incorporating lag and moving average features.

---

## **Contributing** 🤝

Feel free to **fork** the repository, open **issues**, and submit **pull requests**. Your contributions are always welcome!

---

## **License** 📄

This project is licensed under the **MIT License**. See the [LICENSE] file for details.
