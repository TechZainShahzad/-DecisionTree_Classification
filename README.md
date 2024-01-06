# Decision Tree Classification for Diabetes Prediction

## Overview
This GitHub repository contains a Python project for predicting diabetes using a Decision Tree Classification model. The project utilizes the popular machine learning library scikit-learn to implement the classification algorithm. The dataset used for training and testing the model consists of various health-related features, and the goal is to predict whether a person has diabetes or not.

## Dataset
The dataset used in this project is loaded from a CSV file ('diabetes.csv') and includes columns such as 'Pregnant', 'Glucose', 'BP' (Blood Pressure), 'Skin', 'Insulin', 'BMI' (Body Mass Index), 'Pedigree', 'Age', and 'label' (target variable indicating diabetes presence or absence).
![Screenshot (2)](https://github.com/TechZainShahzad/DecisionTree_Classification/assets/136337895/02c75dbe-47fb-4673-8abc-a4b2b3edc96f)


## Project Structure
- **diabetes_classification.ipynb**: Jupyter Notebook containing the code for the Decision Tree Classification project.
- **diabetes.csv**: CSV file containing the dataset used for training and testing.

## Code Highlights
- The Python script uses the pandas library to load and explore the dataset.
- Features and labels are defined based on the dataset columns.
- The dataset is split into training and testing sets using the `train_test_split` function from scikit-learn.
- A Decision Tree Classifier is employed to train the model on the training data.
- The accuracy of the model is evaluated using the `accuracy_score` metric from scikit-learn.\
![Screenshot (1)](https://github.com/TechZainShahzad/DecisionTree_Classification/assets/136337895/0d23c0fc-cddb-47e9-9116-16f30b3e96c6)


## Getting Started
1. Clone the repository to your local machine.
   ```bash
   git clone https://github.com/TechZainShahzad/DecisionTree_Classification
   cd decisionTree_Classification
   ```
2. Ensure you have the required dependencies installed (pandas, scikit-learn).
   ```bash
   pip install pandas scikit-learn
   ```
3. Run the Jupyter Notebook (`diabetes_classification.ipynb`) to explore and execute the code.

## Results
The current implementation achieves an accuracy of approximately 70.13% on the test set. You can further fine-tune the model, experiment with different features, or explore additional algorithms to improve performance.

Feel free to contribute, provide feedback, or use this project as a starting point for your own diabetes prediction models.
