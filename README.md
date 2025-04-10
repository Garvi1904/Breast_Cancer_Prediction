# Breast_Cancer_Prediction




🩺 Breast Cancer Prediction using Logistic Regression


This project implements Logistic Regression to predict whether a tumor is benign (B) or malignant (M) using clinical data from a .csv file.


---------------------------------------------------------------------------------


📊 Dataset


File Used: breast-cancer.csv

Each row represents medical data of a breast cancer case.

Contains features like:

radius_mean, texture_mean, area_mean, etc.

Target column: diagnosis (M = Malignant, B = Benign)


-----------------------------------------------------------------------------------


🛠️ Tools & Libraries


Python

Pandas & NumPy – Data handling

Scikit-learn – ML model & metrics

Matplotlib & seaborn – Visualizations

Jupyter Notebook – Development environment


----------------------------------------------------------------------------------


🔍 Workflow Overview


Load and Explore Data

Read the CSV using Pandas

Understand the structure and check for null values

Preprocessing

Encode the diagnosis column (M → 1, B → 0)

Feature scaling (if needed)

Split dataset into training and testing sets

Model Training

Use LogisticRegression from sklearn.linear_model

Fit model on training data

Evaluation

Accuracy score

Classification report (precision, recall, F1-score)


-----------------------------------------------------------------------------------



📈 Results


Achieved an accuracy of 99.12% on the test set using Logistic Regression.

Training Accuracy : 0.9868131868131869

Testing Accuracy : 0.9912280701754386

F1 Score : 0.9894736842105263

Recall : 1.0
Precision : 0.9791666666666666
