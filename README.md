# Sales-Analysis-Forecasting-using-Machine-Learning-Deep-Learning
This project focuses on end-to-end sales analysis and forecasting across multiple restaurants. It combines data preprocessing, exploratory data analysis (EDA), machine learning, and deep learning (LSTM) to uncover insights and predict future sales trends.


---

## 🎯 Objectives

* Analyze sales data across time, stores, and products
* Identify key business insights and trends
* Build ML and DL models for accurate forecasting
* Compare model performance using evaluation metrics

---

## 🔍 Methodology

### 1. 🧹 Data Preparation

* Imported and examined datasets for structure and outliers
* Merged datasets into a unified dataset containing:

  * Date, Item ID, Price, Sales Amount
  * Item Name, Calories (kcal)
  * Store ID and Store Name

---

### 2. 📊 Exploratory Data Analysis (EDA)

* Analyzed **date-wise sales trends**
* Studied **weekly, monthly, and quarterly patterns**
* Compared restaurant performance across time
* Identified:

  * Most popular items overall and per store
  * Top-performing stores by revenue
  * Relationship between sales volume and revenue
  * Most expensive items and their calorie values

---

### 3. 🤖 Machine Learning Forecasting

* Engineered time-based features:

  * Day, Month, Year, Quarter, Day of Week
* Built and compared models:

  * Linear Regression
  * Random Forest
  * XGBoost
* Used last 6 months as test data
* Evaluated models using **RMSE**
* Selected best model for next-year forecasting

---

### 4. 🧠 Deep Learning Forecasting (LSTM)

* Used **sales amount** as the target variable
* Defined train and test time series
* Generated synthetic data for the last 12 months
* Built and trained an **LSTM (Long Short-Term Memory)** model
* Predicted sales on test data
* Evaluated performance using **MAPE (Mean Absolute Percentage Error)**
* Trained a final model on the full dataset
* Forecasted sales for the **next 3 months**

---

## 📊 Results & Insights

* Identified key sales patterns across time and locations
* Discovered top-performing products and stores
* Compared ML and LSTM models for forecasting accuracy
* Generated reliable short-term and long-term forecasts

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* XGBoost
* TensorFlow / Keras (LSTM)

---

## 📁 Project Structure

```bash
├── Data set_sale forecasting
├── Sale_forecasting.ipynb
├── Output_visualization/...
└── README.md
```

---

## 👤 Author

**Ujjwal Manikya Nath**
Data Science | Machine Learning | Computer Vision
