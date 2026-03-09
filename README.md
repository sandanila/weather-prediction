# weather-prediction
# Weather Data Analysis & Prediction 🌦️

This project focuses on analyzing a weather dataset and building a **Multi Linear Regression** model to predict specific weather parameters. The core of the project involves extensive data cleaning, handling non-numeric data, and outlier mitigation to ensure high model accuracy.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** * **Pandas & NumPy:** For data manipulation and matrix operations
    * **Scikit-Learn:** For data scaling, splitting, and model training
    * **Matplotlib & Seaborn:** For data visualization

## 📊 Key Workflow

1. **Data Preprocessing:** Handled non-numeric columns like `Date/Time` by dropping or converting them to ensure compatibility with the Linear Regression model.
2. **Outlier Detection:** Used the **Interquartile Range (IQR)** method to identify and remove anomalies that could skew the model's predictions.
3. **Feature Scaling:** Implemented `StandardScaler` to normalize the numeric features, ensuring all variables contribute equally to the model.
4. **Model Implementation:** Divided the data into training and testing sets using `train_test_split` and trained a `LinearRegression` model.
5. **Evaluation:** Evaluated performance using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R2) score.

## 📈 Model Performance
Based on the final evaluation, the model achieved the following results:
* **MAE:** 0.5045
* **MSE:** 0.4148
* **RMSE:** 0.6441
* **R2 Score:** 0.2785
