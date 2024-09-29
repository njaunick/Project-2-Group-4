#Estimating Obesity Levels from Eating Habits and Physical Activity
 
**Overview**
This project aims to predict obesity levels based on individuals’ eating habits and physical activity using machine learning techniques. Our goal is to develop a model that can accurately estimate obesity levels, providing insights into the factors that contribute to obesity.

**Dataset**
*Source:* UCI Machine Learning Repository
*Name:* Estimation of Obesity Levels Based on Eating Habits and Physical Condition
*Records:* 2,111 entries

**Data Processing**
*Extraction and cleaning:*
We used a Jupyter notebook to extract, clean, and transform the dataset. The cleaned data is saved as CSV files for further analysis.
*Exploration:* 
Initial data exploration to understand the distribution and relationships within the data.

**Model Development**
*Training and Evaluation*: 
A Python script was created to initialize, train, and evaluate our machine learning model. We aimed for a classification accuracy of at least 75% or an R-squared value of 0.80.

**Model Training**
*Trained the following:*
Logistic Regression
SVM
Random Forests
KNN
Gradient Boosting
Adaptive boosting
Decision Tree
Extra Trees
Hyperparameter tuning( after picking random forests)
          a. Used Randomized Search CV
          b. Grid Search CV
Found out the best parameters and got classification report
*Optimization:*
The model was iteratively optimized, with each change documented to show its impact on performance.

**Repository Management**
*Clean Structure:*
The GitHub repository is organized, with unnecessary files excluded using a .gitignore file.
*Documentation:* This README provides a polished overview of the project, and additional documentation is available within the repository.

**Summary**
*Data Prep and cleaning:*
We used dropna() to drop all the null values.
We used replace to replace string to int - encoding our data.
Split into train and test.

*Methodology:*
A Python script was created to initialize, train, and evaluate our machine learning model. We aimed for a classification accuracy of at least 75% or an R-squared value of 0.80.

*Future Work:*
?

*Results:*
Key findings and conclusions from the analysis.

*Slides:*
A professional and visually appealing slide deck to present the project.
