# Decision_tree

## 📌 Overview
This repository contains two small projects that demonstrate the use of *Decision Tree Classifiers* for classification tasks:
1. *Predicting High Salary (>100k)* – Predict whether a person earns more than 100k per year using label encoding.
2. *Predicting Titanic Survival* – Classifying whether a passenger survived the Titanic disaster based on personal and travel details.

## 📖 About Decision Trees
A Decision Tree is a *supervised learning algorithm* used for both classification and regression.  
It works by splitting data into branches based on feature values, creating a tree-like structure where:
- *Nodes* represent features
- *Edges* represent decision rules
- *Leaves* represent output labels

The model selects splits that maximize *information gain* (classification) or minimize *variance* (regression).

## 🛠 Technologies Used
- Python 
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn

## 📂 Projects Included
### 1️⃣ Predicting High Salary (>100k)
- *Goal*: Predict whether a person earns more than 100k/year.
- *Process*:
  - Load dataset
  - Encode categorical variables using *LabelEncoder*
  - Train Decision Tree Classifier
  - Predict and evaluate results
  

### 2️⃣ Predicting Titanic Survival
- *Goal*: Predict whether a passenger survived the Titanic shipwreck.
- *Process*:
  - Load Titanic dataset
  - Preprocess data (handle missing values, encode categories)
  - Train Decision Tree Classifier
  - Predict and evaluate results
  
