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

* **Identified key sales patterns across time**



<img width="592" height="491" alt="Date wise sale trends " src="https://github.com/user-attachments/assets/aa783bf3-d74f-4edf-9b67-a6b96dd1b758" />


<img width="605" height="505" alt="Monthly Sales Pattern" src="https://github.com/user-attachments/assets/ee1654bf-d717-4bd3-94c1-2c0df8fa7aa1" />


<img width="576" height="455" alt="Average Quarterly Sales" src="https://github.com/user-attachments/assets/181ac896-4209-43e8-a2bb-1221ccb2f042" />





* **Discovered top-performing products and stores**


<img width="580" height="525" alt="Average Daily Revenue by Store" src="https://github.com/user-attachments/assets/9898dea3-c2ae-4a35-bbe4-5b149025356a" />

<img width="573" height="455" alt="Yearly Sales - Bob&#39;s dinner " src="https://github.com/user-attachments/assets/1f0e7c0c-58c9-46a6-b643-47b027b1e9f0" />
<img width="554" height="525" alt="Total Sales by Restaurant" src="https://github.com/user-attachments/assets/51e1cc51-7fad-489b-981e-4f9e9f4f9f8d" />
<img width="605" height="612" alt="Top 10 Most Popular Items" src="https://github.com/user-attachments/assets/8dcf9f51-3888-4b70-b9e0-028f4b6e2679" />



* **Compared Root Mean Square Error (RMSE) of ML models**

<img width="639" height="280" alt="Compare Model Performance" src="https://github.com/user-attachments/assets/1c0e0c24-bfbc-4969-be7a-a0c6c6b60a60" />


* **Generated reliable next 3 months sales forecasts**

<img width="570" height="435" alt="3-Month Sales Forecast using RELU" src="https://github.com/user-attachments/assets/6a172aa0-3167-42b8-9053-53123d80784b" />
<img width="570" height="435" alt="3-Month Sales Forecast using ELU" src="https://github.com/user-attachments/assets/4fcd1c3e-db20-4b85-a8e2-779c1a324b3a" />


* **Sales Forecast for Next Year**

<img width="595" height="455" alt="Sales Forecast for Next Year" src="https://github.com/user-attachments/assets/f6bda414-97e9-4187-8a87-9077115371a8" />


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
