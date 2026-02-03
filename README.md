# Amazon Stock Price Prediction (Machine Learning)

This project explores **machine learning–driven time-series prediction** using historical daily stock data for Amazon (AMZN). The goal is to demonstrate an end-to-end ML workflow—from data preprocessing and feature engineering to model training and evaluation—on real financial data.

This repository is designed to showcase **practical ML fundamentals** relevant to machine learning and data science internships.

---

## Problem Statement

Financial time-series data is noisy, non-stationary, and difficult to model. This project investigates:

* How historical price data can be transformed into ML-ready features
* How baseline models perform on stock price prediction
* The limitations of naive predictive approaches in financial markets

---

## Repository Structure

```
amazon-prediction/
│
├── data/
│   └── AMAZON_daily.csv        # Raw daily Amazon stock data
│
├── Amazon_Pred.ipynb           # End-to-end ML notebook
│
└── README.md
```

---

## Data

* **Asset:** Amazon (AMZN)
* **Frequency:** Daily
* **Features:** Open, High, Low, Close, Volume
* **Target:** Price-based prediction task (documented in notebook)

The dataset is intentionally kept raw to demonstrate **data cleaning and preprocessing steps explicitly**.

---

## Machine Learning Workflow

The notebook follows a structured ML pipeline:

1. **Data Loading & Cleaning**

   * Handling missing values
   * Type casting and date parsing

2. **Exploratory Data Analysis**

   * Price trends and volatility visualization
   * Distribution analysis

3. **Feature Engineering**

   * Lag-based features
   * Rolling statistics
   * Target variable construction

4. **Modeling**

   * Baseline predictive model
   * Train/test split respecting time-series ordering
   * Performance evaluation

5. **Evaluation**

   * Error-based metrics
   * Visual comparison of predictions vs. actual values

---

## Key Takeaways

* Simple models struggle with financial time-series noise
* Feature engineering plays a larger role than model complexity
* Proper temporal validation is critical in time-series ML

---

## Future Improvements

* Add technical indicators (returns, volatility, RSI, moving averages)
* Experiment with tree-based models (XGBoost, Random Forest)
* Implement deep learning models (LSTM, NHITS)
* Extend to multi-asset prediction or portfolio-level analysis
* Introduce walk-forward validation

---

## Why This Project Matters

This project demonstrates:

* Applied machine learning on real-world data
* Strong understanding of ML fundamentals
* Awareness of modeling pitfalls in finance
* Clean, reproducible, well-documented workflow

---

## Author

**Toye Salami**
Industrial Engineering @ Georgia Tech
Interests: Machine Learning, Data Science, Quantitative Modeling
