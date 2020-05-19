# Supervised-Machine-Learning

In this project, I used supervised learning techniques on data collected for the U.S. census to help CharityML (a fictitious charity organization) identify people most likely to donate to their cause.

At first, data explored to identify the population earn more than $50000. Next, a series of transformations and preprocessing techniques performed to manipulate the data into a workable format(log transformation, feature scaling and one-hot encoding) .

After that, the data divided to test and split sets and several machine learning algorithms were tested ( Naive Bayes, SVM, AdaBoost, RandomForest). The best classifier was AdaBoost Classifier based on the speed, accuracy and f-beta score.
The algorithm parameters were fine tuned using GridSearchCV.

At the end, feature importance were extracted and feature selection was performed for simplification.
