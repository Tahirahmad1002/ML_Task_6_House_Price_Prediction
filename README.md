# AI/ML Internship - Task 6: House Price Prediction

## 🎯 Objective
The goal of this project is to build a regression model that can predict the market price of a house based on demographic and property features such as Area Income, House Age, and Number of Rooms.

## 📊 Dataset
**USA Housing Dataset (Kaggle)**
- **Features:** Avg. Area Income, Avg. Area House Age, Avg. Area Number of Rooms, Avg. Area Number of Bedrooms, Area Population.
- **Target Variable:** Price.

## 🛠️ Methodology
1. **Data Cleaning:** Checked for missing values and removed the non-numerical 'Address' column.
2. **Feature Scaling:** Applied `StandardScaler` to normalize the data for better model performance.
3. **Data Splitting:** Divided the data into 80% Training and 20% Testing sets.
4. **Model:** Implemented **Linear Regression**.

## 📈 Key Results
- **Mean Absolute Error (MAE):** $80,879.10
- **RMSE:** $100,444.06
- **Accuracy:** ~93.49% (Error Rate of only 6.51%)
- **Insights:** The strongest predictor of house price in this dataset was **Avg. Area Income**, followed by **House Age**.

## 🚀 How to Run
1. Open the `.ipynb` file in Google Colab.
2. Upload the `USA_Housing.csv` file.
3. Run all cells.
