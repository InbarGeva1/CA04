# CA04
Overview

In this assignment, we explore the power of ensemble methods to enhance model performance. Leveraging a dataset from the Census Bureau, we use and analyze three distinct ensemble models: Random Forest, AdaBoost, and Gradient Boosting, including XGBoost. Our primary objective is to predict salary categories using demographic data, with an emphasis on optimizing the number of estimators for each model to achieve the best possible accuracy and AUC metrics.

Data Source
The dataset used in this assignment is sourced from the Census Bureau. It consists of 48,842 instances (rows) with seven demographic attributes, aimed at classifying individuals into two salary categories: '>50K' and '<=50K'.

Data source URL: Census Bureau Dataset

Features
Target Classes: '>50K', '<=50K' (Labels: 1, 0)
Number of Instances (Rows): 48,842
Number of Attributes (Columns): 7
The dataset is split into "Training Data" and "Testing Data" as indicated by a specific column.

Library Imports
The following Python libraries are used:

numpy
pandas
matplotlib
sklearn (for ensemble models including RandomForestClassifier, AdaBoostClassifier, GradientBoostingClassifier, and XGBClassifier)
xgboost

Installation
Ensure Python is installed. Install the required libraries using pip:
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
