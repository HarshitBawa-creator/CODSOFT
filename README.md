Iris Flower Classification using Random Forest
This project implements a machine learning model to classify iris flowers into species (Setosa, Versicolor, Virginica) using the classic Iris dataset. The classification is done using a Random Forest algorithm.
Project Overview
    Dataset: Iris dataset (sepal length, sepal width, petal length, petal width)
    Model: Random Forest Classifier
    Goal: Predict the species of an iris flower based on its measurements
    Tools & Libraries: Python, pandas, seaborn, matplotlib, scikit-learn

How to Run
    Clone the repository:

git clone https://github.com/HarshitBawa-creator/irisflowerclassification.git
cd irisflowerclassification

Install the required packages:
pip install pandas seaborn matplotlib scikit-learn

Run the script:
python main.py

Code Summary
    Load Dataset: The Iris dataset is loaded from a public URL.
    Explore Data: Display first 5 rows and species distribution.
    Visualize Data: Pairplot of features colored by species.
    Prepare Data: Split into features (X) and labels (y).
    Train-Test Split: Dataset split into training and testing sets.
    Train Model: Random Forest Classifier is trained on training data.
    Predict: Model makes predictions on the test set.
    Evaluate: Accuracy and classification report are printed.
