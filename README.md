# 🎯 Student Performance Prediction: Hours vs Percentage

This beginner-friendly project uses **Simple Linear Regression** to predict student scores based on the number of hours studied. It demonstrates how machine learning can find patterns and make predictions using minimal data.

---

## 📁 Dataset
- Source: [http://bit.ly/w-data](http://bit.ly/w-data)
- Features:
  - `Hours`: Number of hours a student studies per day
  - `Scores`: Percentage score obtained by the student

---

## 📊 Objective
To predict the percentage score of a student based on the number of study hours using Linear Regression.

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- scikit-learn

---

## 📌 Steps Involved

### 1. Data Exploration
- Loaded dataset from URL using Pandas
- Inspected data shape, types, and summary statistics

### 2. Data Visualization
- Used `matplotlib.pyplot` to plot a scatter plot
- Observed a linear relationship between `Hours` and `Scores`

### 3. Model Training
- Split the data into training and test sets
- Trained a Linear Regression model using `sklearn.linear_model.LinearRegression`

### 4. Prediction and Evaluation
- Used `regressor.predict()` to make predictions on the test data
- Compared Actual vs Predicted scores
- Visualized both Training and Test results using line plots

### 5. Custom Prediction
Predicted the score for a student studying 2.5 hours/day:
```python
If the student studies for 2.5 hours/day, the score is [26.8422321].
