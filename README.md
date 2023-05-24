# TFG-Miriam-Colino-Ruiperez

This repository contains the code used on the final degree thesis by Miriam Colino Ruipérez: Detection of network and information systems attacks using Deep Learning techniques on the year 2022/2023 at ICAI School of Engineering.

The dataset used for this proyect was CSE-CIC-IDS2018 (https://registry.opendata.aws/cse-cic-ids2018/). 4 types of attacks were analyzed: Benign, Brute Force - Web, Brute Force - XSS and SQL injection.

TFGMiriamColinoRuiperez.ipynb is a Jupyter Notebook file in which several Machine Learning and Deep Learning models are built, trained and tested and its ability to classify the 4 types of attacks is analyzed. In addition, for each model an adjustment of its hyperparameters has been made.
The file consists of the following parts: 
- Data filtering
- SMOTE and separation in set train and test
- SGD model
- Logistic Regression Model
- Decision Tree Model
- Random forest model
- KNN model
- Neural network
- Ensemble model formed by the three models with the highest accuracy. 

For each model several performance evaluation metrics are used:
- Confusion matrix and classification report.
- ROC curve
- Accuracy per class 
- Feature importance (in Decision Tree and Random forest)
- Comparative graphs between models (execution time and accuracy)

