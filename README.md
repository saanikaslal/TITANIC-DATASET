🛳 Titanic Survival Prediction using SVM

This project predicts Titanic passenger survival using Support Vector Machine (SVM) with the famous Titanic dataset.

📌 Project Overview

The Titanic dataset is a binary classification problem:

Survived = 1 → Passenger survived

Survived = 0 → Passenger did not survive

We preprocess the dataset (handle missing values, encode categorical features, scale numeric data).

We train an SVM classifier (sklearn.svm.SVC) with an RBF kernel.

Finally, we evaluate the model using accuracy, precision, recall, and F1-score.

📂 Dataset

Typical columns include:

PassengerId – ID of passenger

Pclass – Ticket class (1st, 2nd, 3rd)

Name – Passenger name (dropped)

Sex – Gender

Age – Age in years (missing values filled with median)

SibSp – # of siblings/spouses aboard

Parch – # of parents/children aboard

Ticket – Ticket number (dropped)

Fare – Passenger fare

Cabin – Cabin number (dropped)

Embarked – Port of embarkation (C, Q, S)
