# YoungDevInterns_Machine_Learning_Task_6
 Create a Classification Report  Task: Generate a detailed classification report.  Details:  Use scikit-learn to train a classification model.  Produce a report including precision, recall, and F1-score for each class

📌 Task Overview
This task involves training a Logistic Regression model on cereal nutritional data and evaluating its performance using a detailed classification report.

📊 Dataset
File: preprocessed_cereal.csv

Target: rating_class – Derived from converting continuous ratings into three classes:

Low

Medium

High

🧠 Key Steps
Preprocessing

Converted the rating column into categorical classes using pd.cut()

Used LabelEncoder to convert class labels into integers

Model Training

Split data using train_test_split (with stratification)

Trained LogisticRegression with max_iter=1000

Evaluation

Generated a classification report using Scikit-learn’s classification_report()

Ensured consistent labels across train/test sets

Reported Precision, Recall, F1-Score, and Support for each class
