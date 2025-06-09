# CNC_MLE3 – Task 3: Simple Regression Model

## 📌 Task Objective:
To build a simple linear regression model using the Iris dataset. The model is trained to predict the **petal width (cm)** based on **petal length (cm)**.

## 📊 Dataset Used:
- Dataset: [Iris Dataset](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html)
- Format: CSV (`iris_dataset.csv`)
- Target for prediction: `petal width (cm)`
- Feature used: `petal length (cm)`

## 🛠️ Technologies Used:
- Python
- Pandas
- Scikit-learn (LinearRegression, train_test_split, mean_squared_error)
- NumPy
- Matplotlib (for visual output)

## 📂 Files in this Repository:
- `Task3_Regression_Visual.py` – Python script for training and visualizing the regression model
- `iris_dataset.csv` – Cleaned dataset used for model training

## 📈 Output:
- Root Mean Squared Error (RMSE) of the regression
- Coefficient (slope) and Intercept
- Regression line plotted against test data

## 📷 Sample Output Graph:
The code displays a graph showing:
- Blue dots: Actual values from test data
- Red line: Predicted values (regression line)

## ✅ Conclusion:
This task demonstrates the ability to:
- Use a regression algorithm on real-world data
- Evaluate the model with metrics
- Visualize predictions with Matplotlib
