# **Tree-Based classifiers on Mushroom Dataset**
This repository attempts to apply two tree models to determine which features indicate whether a mushroom is poisonous or edible.
## Overview
The approach in this project formulates the problem as a classification task, using Decision Trees, Random Forests, and XGBoost models to predict the target class based on the dataset's features. Feature engineering included label encoding categorical variables and refining feature selection to reduce overfitting. All models achieved a perfect accuracy score of 1.0, highlighting their ability to effectively fit the training data and generalize to the test data. At the time of writing, achieving perfect classification accuracy across multiple models suggests minimal variance in the dataset and a potentially straightforward decision boundary.

## Summary of work done
Data: Categorical data (8124, 23) all in mushrooms.csv(374 kB)
Data Clean-up: There were no null values, no outliers, and some features were dropped 'veil-type', 'stalk-color-below-ring', 'stalk-surface-above-ring', 'cap-shape', 'gill-spacing', 'cap-surface'.
All data was label-encoded as tree-based models are not sensitive to how variables are represented. 

## Visualization
Tree-based models, such as Decision Trees can highlight feature importance by evaluating how much each feature contributes to reducing impurity.
<img width="602" alt="image" src="https://github.com/user-attachments/assets/82f04f70-fc51-43fe-b183-c7d54720ce1e" />

## Conclusions and Future Work
With all models obtaining perfect accuracy, it determines how strongly tied the features are to the target. In the future, I would introduce more data so that the model can capture underlying patterns that may go unseen due to lack of information. 

## Citations
https://www.kaggle.com/datasets/uciml/mushroom-classification

https://towardsdatascience.com/the-search-for-categorical-correlation-a1cf7f1888c9
