# Machine-learning-tutorial-assignment
# Decision Trees and Overfitting Tutorial: Breast Cancer Classification

## Table of Contents
- Introduction
- Dataset
- Workflow:
- Results and Visualizations
- License
---
## Introduction
This project:
1. Builds a Decision Tree Classifier to classify breast cancer as Malignant (M) or Benign (B).
2. Explores overfitting by training trees with increasing depth.
3. Optimizes the Decision Tree using hyperparameters like max_depth and min_samples_split.
4. Visualizes the decision tree and evaluates its performance.


## Dataset
The dataset used is the Breast Cancer Dataset, available as a CSV file:

1. Features: Measurements like radius, texture, perimeter, area, etc.
2. Target: diagnosis column, mapped as:
3. M → Malignant (1)
4. B → Benign (0)

## Workflow:
1. Loads the dataset and preprocesses it.
2. Splits the data into training and testing sets.
3. Trains a Decision Tree Classifier and evaluates its performance.
4. Visualizes the decision tree and confusion matrix.
5. Demonstrates overfitting using a deeper tree and mitigates it with an optimized model.
6 Plots accuracy vs tree depth to illustrate overfitting.

## Results and Visualizations
1. Decision Tree Visualization
Displays the trained tree with features and decision rules:

2. Confusion Matrix
Illustrates the model's performance on test data:

3. Depth vs Accuracy
Shows the impact of tree depth on training and testing accuracy:

## License
This project is licensed under the MIT License. See the LICENSE file for details.

---
