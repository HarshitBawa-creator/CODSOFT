#  Sales Prediction using Linear Regression

This project is part of my **Data Science Internship at CODSOFT**.

The goal of this project is to build a machine learning model that predicts sales based on the TV advertising budget. The dataset is simple and ideal for practicing linear regression.

---

# Dataset

- Source: [Advertising Dataset](https://raw.githubusercontent.com/selva86/datasets/master/Advertising.csv)
- Features:
  - TV (Advertising spend in thousands)
  - Sales (Product sales in thousands of units — Target variable)
- Total Records: 200

---

# Tools and Libraries

- Python
- Pandas
- Scikit-learn
  - LinearRegression
  - Train-test split
  - Evaluation metrics
- Matplotlib
- Google Colab

---

# Steps Performed

1. Loaded the dataset
2. Selected "TV" as the independent variable and "sales" as the target
3. Split the data into training and test sets
4. Trained a linear regression model
5. Evaluated it using:
   - Mean Squared Error (MSE)
   - R² Score
6. Visualized predictions with a regression line

---

# Model Results

- **Mean Squared Error:** ~10.2
- **R² Score:** ~0.67
- The model shows a decent positive correlation between TV ads and sales.

