# RockMinePrediction
This project implements a Machine Learning classification model to predict whether an object detected by sonar signals is a Rock (R) or a Mine (M).

It is a beginner-friendly project that demonstrates the complete ML workflow, from data preprocessing to model evaluation.

Sonar systems are used to detect objects underwater by sending sound waves and analyzing their reflections. This project uses those reflected signals as input features to classify objects.

----------------------------------------------------------------------------------------------------------------------------------------------

#Overview

Problem Type: Binary Classification
Labels:
  R → Rock
  M → Mine
Algorithm Used: Logistic Regression

----------------------------------------------------------------------------------------------------------------------------------------------

#Dataset Information

The dataset consists of numeric values representing sonar signal strengths
Each row corresponds to a single object
The last column contains the target label (Rock or Mine)

----------------------------------------------------------------------------------------------------------------------------------------------

#Project Workflow

1. Import Libraries :
   NumPy, Pandas, Scikit-learn
   
3. Load Dataset : 
   Dataset loaded into a Pandas DataFrame
   
4. Data Preprocessing :  
   Separate features (X) and target labels (Y)
   Convert labels into usable format
   
5. Train-Test Split :
   Split data into training and testing sets
   Use stratification to maintain class balance
   
6. Model Training : 
   Logistic Regression model trained on training data

7. Model Evaluation :
   Accuracy score calculated
   Predictions tested on unseen data

----------------------------------------------------------------------------------------------------------------------------------------------

#Technologies Used
  Python 
  NumPy
  Pandas
  Scikit-learn

----------------------------------------------------------------------------------------------------------------------------------------------

#Results
  The model successfully classifies sonar signals into rocks and mines
  Achieves good accuracy on both training and testing data
  Demonstrates the effectiveness of Logistic Regression for structured data
