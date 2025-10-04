Titanic Survival Prediction
Project Overview
This project tackles the classic Kaggle data science challenge: predicting passenger survival on the RMS Titanic. The goal is to build a machine learning model that analyzes a passenger's features—such as their age, gender, and passenger class—to determine whether they survived the infamous disaster. This project serves as a comprehensive demonstration of a full machine learning workflow, from initial data exploration to final model evaluation and submission.

Dataset
The dataset is the official Titanic dataset provided by Kaggle. It is split into three core files:

train.csv: Contains detailed information for a subset of passengers, including personal details (Age, Sex), travel information (Passenger Class, Fare), and the crucial ground truth label, Survived. This file is used to train and validate the model.

test.csv: Contains the same passenger information as the training set but omits the Survived label. This file is used to test the final model's predictive power.

gender_submission.csv: An example file that shows the correct format for submitting predictions.

Tools and Libraries
This project was developed in a Google Colab environment using Python. The key libraries utilized for this analysis are:

Data Analysis and Manipulation: Pandas, NumPy

Data Visualization: Matplotlib, Seaborn

Machine Learning: Scikit-learn
