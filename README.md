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

Library Imports:
The following Python libraries are used:

numpy
pandas
matplotlib
sklearn (for ensemble models including RandomForestClassifier, AdaBoostClassifier, GradientBoostingClassifier, and XGBClassifier)
xgboost

Installation:
Ensure Python is installed. Install the required libraries using pip:

pip install pandas numpy matplotlib seaborn scikit-learn xgboost

Usage and Results:

Data Preprocessing
We cleaned up the dataset to make sure it's ready for use. This means fixing any missing values, getting rid of weird data, and making sure everything is in the right format. 

Model Building and Optimization
We used three different types of models to try and guess if someone earns more or less than 50K, based on their info:

Random Forest Model: This one uses simple models with decision trees to get a better overall prediction. 

AdaBoost Model: This model tries harder where it's more difficult to get the right answer. It changes its focus based on what it got wrong before to get better over time.

Gradient Boosting and XGB Model: These models learn from the mistakes of the model before them to improve. XGB, in particular, stands out for its efficiency and performance, offering fast and accurate predictions.

Predictive Analysis
After we figured out the best settings for our models, we tested them with our data to see if they could accurately tell us who makes more than 50K and who doesn't. We did this by:

Putting the clean data into our models to see what they predict.
Checking how accurate these predictions are.
Trying the models on new data that they haven't seen before to see how well they do.

