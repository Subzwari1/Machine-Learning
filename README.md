# Machine-Learning

## House Prices Prediction Project

### Overview

This project is part of my Master's degree work, focusing on predicting house prices using various machine learning algorithms. The dataset used for this project is derived from the California Census data. The goal is to implement, evaluate, and compare different machine learning models to predict housing prices accurately.

### Project Structure

- **README.md**: Project overview and instructions.
- **requirements.txt**: Python libraries and dependencies needed to run the project.

### Dataset
The dataset used in this project consists of various features like 'PropertyType', 'RoofMatl', 'RoofStyle', 'SaleCondition', 'SaleType', 'ScreenPorch', GarageArea', 'GarageCars', 'GarageCond', 'GarageFinish','Street'. T

This project explores the following machine learning algorithms:

1. **Decision Tree Classifier**
   - **C4.5 Algorithm**: A decision tree algorithm that builds a tree by splitting nodes based on the highest information gain.
   - **Classification and Regression Trees (CART)**: An algorithm that builds binary trees based on the Gini impurity metric.

2. **Gaussian Naive Bayes**
   - A probabilistic classifier based on Bayes' Theorem, assuming that the features follow a Gaussian distribution.

3. **Neural Network (MLP Classifier)**
   - A multi-layer perceptron (MLP) classifier, a type of feedforward artificial neural network model that maps sets of input data onto appropriate outputs.

### Usage
1. **Data Preprocessing:**

   -The data preprocessing steps are detailed in the notebook house_prices_project.ipynb. This includes handling missing values, feature    scaling, and encoding categorical variables.

2. **Model Training:**

   -Train the models by running the notebook available. Above mentioned algorithms are tested in the same notebook together. 
   
3. **Model Evaluation:**

   -The performance of each model is evaluated using metrics such as accuracy, precision, recall, and F1-score. The evaluation results are documented in the notebook and can be found in the final sections.
   
4. **Running Predictions:**

   -Use the trained models to make predictions on new test data.

### Results

The performance of the models was evaluated based on their accuracy in predicting house prices. Here are the summarized results:

   -Decision Tree Classifier (C4.5 and CART): Achieved a good balance between interpretability and performance.

   -Gaussian Naive Bayes: Performed well with a lower computational cost but slightly less accurate due to its assumptions.

   -Neural Network (MLP Classifier): Provided the highest accuracy but required more computational resources and careful tuning of hyperparameters.
