# Prodigy InfoTech Data Science Internship — Task 3

## Decision Tree Classifier

This project is part of my Data Science Internship at Prodigy InfoTech.

### Task Objective

The objective of this task is to build a Decision Tree Classifier to predict whether a customer will subscribe to a term deposit based on demographic and behavioral data.

The Bank Marketing dataset from the UCI Machine Learning Repository is used for this classification problem.

## Dataset

**Dataset:** Bank Marketing Dataset  
**Source:** UCI Machine Learning Repository

The dataset contains information about customers contacted during a bank marketing campaign.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Project Workflow

1. Import required libraries
2. Load the Bank Marketing dataset
3. Explore the dataset
4. Check data quality and missing values
5. Preprocess categorical variables
6. Split the dataset into training and testing sets
7. Build and train a Decision Tree Classifier
8. Make predictions
9. Evaluate the model
10. Visualize the confusion matrix and decision tree
11. Analyze the final results

## Machine Learning Model

A **Decision Tree Classifier** was used with:

- Criterion: Gini
- Maximum Depth: 5
- Test Size: 20%
- Random State: 42

## Results

The model achieved approximately:

**Accuracy: 89.96%**

### Confusion Matrix

```text
[[7816  169]
 [ 739  319]]
