# Project-2-Group-4

## Estimating Obesity Levels from Eating Habits and Physical Activity

### Project Overview

- This machine learning project aims to predict obesity levels based on individuals' eating habits and physical activity. By developing an accurate model, we seek to provide valuable insights into the factors contributing to obesity, potentially aiding in public health initiatives and personalized health recommendations.

### Dataset
- We utilized the "Estimation of Obesity Levels Based on Eating Habits and Physical Condition" dataset from the UCI Machine Learning Repository
- This dataset contains 2,111 records with various features related to eating habits, physical condition, and demographic information.Data Processing

### Extraction and Cleaning
- We employed a Jupyter notebook to extract, clean, and transform the dataset. The process involved:Dropping null values using dropna()
- Encoding categorical variables into numerical format
- Splitting the data into training and testing sets
- The cleaned data was saved as CSV files for further analysis

### Exploratory Data Analysis
- Initial data exploration was conducted to understand:
  1. Feature distributions
  2. Correlations between variables
  3. Class balance in the target variable (obesity levels)

### Model Development

#### Training and Evaluation

- We created a Python script to initialize, train, and evaluate various machine learning models. Our target was to achieve a classification accuracy of at least 75% or an R-squared value of 0.801

#### Models Trained
  1. Logistic Regression
  2. Support Vector Machines (SVM)
  3. Random Forests
  4. K-Nearest Neighbors (KNN)
  5. Gradient Boosting
  6. Adaptive Boosting
  7. Decision Trees
  8. Extra Trees
     
### Hyperparameter Tuning
- After selecting Random Forests as our best-performing model, we conducted hyperparameter tuning using:
  1. Randomized Search CV
  2. Grid Search CV
     
- This process helped us identify the optimal parameters for our Random Forest model
### Results
The Random Forest model with tuned hyperparameters achieved the best performance. Key metrics include:
- Accuracy: 95%
- Precision: 96%
- Recall: 97%
- F1-Score: 98%
