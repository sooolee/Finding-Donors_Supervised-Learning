# Finding Donors Using Supervised Learners

In this project, I use AdaBoost, Naive Bayes (Multinomial), SVM (LinearSVC) algorithms to predict individuals' income using data collected from the 1994 U.S. Census. 

Preprocessing techniques used in this project include logarithmic transformation, one-hot encoding and normalizing. 

Accuracy and F-score are used to assess the performance of the models. 

![performance_metrics]


I further optimize AdaBoost with Decision Trees to best model the data. Fine-tunung the hyperparameters are performed using GridSearch. 

With feature selections (reduced number of features to 5 from 13), the model produced a little bit lower scores for both Accuracy and F-score, but not significantly. 

![feature_selection]
