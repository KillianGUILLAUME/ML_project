# ML_project
Machine Learning Project


The objective of this notebook is to effectively detect and predict a minority class (label 1) in a tabular dataset (data.csv) by comparing several classification algorithms, while managing class imbalance.

Class imbalance is managed using SMOTE (Synthetic Minority Over-sampling Technique).
Overview of the classifiers used:
-SGDClassifier
-KNN
-Random Forest, XGBoost (specific for class imbalance)
Each model is encapsulated in a scikit-learn pipeline, allowing for clear chaining with scaling and SMOTE, then subjected to hyperparameter search (GridSearchCV).
