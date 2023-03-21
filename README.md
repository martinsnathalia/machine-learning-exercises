![DALL·E 2023-03-16 16 11 14 2](https://user-images.githubusercontent.com/89808695/225728782-990f2e98-56f8-4b22-ad6d-fdbe07908f91.png)

# Machine Learning Exercises

This repo is about activities for implementing techniques and practicing Machine Learning algorithms.

These activities were given in machine learning classes, and tasks that required the implementation of ML's algorithms on the Information Security Residency program at Federal University of Ceara.

There are 2 folders relative to code and data:
- In the data folder, there are some ".csv" files were used on the code. Some datasets are too large and therefore could not be made available on github.
- In the code folder, there are scripts with proposed tasks and the execution of the code. 


## Summarization of the files

File | Description | Libraries | Algorithms | Dataset | Metrics
:-----:|:----------:|:---------:|:----------:|:--------:|:-------:
linear-regression.ipynb | Linear regression, polynomial and regularization | Numpy, Matplotlib | Ordinary Least Squares (OLS), Gradient Descent (GD), Stochastic Gradient Descent (SGD) | artificial.csv, california.csv | MSE, RMSE
ensemble-random-forest-gs.ipynb | Use Random Forest and grid search for parameters optimization | Numpy, Scikit-learn, Matplotlib, Warnings | Random Forest | enron_spam_data_prep.csv | Accuracy, recall, precision, f1-score, ROC curve, precision-recall curve
svm-gridserach.ipynb | Use Support Vector Machine (SVM) and grid search for parameters optimization | Numpy, Scikit-learn, Matplotlib, Warnings | Support Vector Machine (SVM) | enron_spam_data_prep.csv | Accuracy, recall, precision, f1-score, ROC curve, precision-recall curve
artificial-neural-network.ipynb | Use validation set to adjust hyperparameters | Numpy, Scikit-learn, Matplotlib, Seaborn, Warnings | Multilayer Perceptron Classifier (MLP) | edge_iiot.csv | Cost function curve, Accuracy, Confusion Matrix
kfold-models-metrics.ipynb | KFold, statistical methods and algorithms | Numpy, Scikit-learn, Warnings | Logistic Regression, Gaussian Discriminant Analysis, Gaussian Naive Bayes, KNN, Decision Tree | jsvulnerability_balanced.csv | Mean value and standard deviation of accuracy, recall, precision and F1-score
kfold-feature-selection.ipynb | Test at least 5 algorithms and feature selection methods (Variance Threshold, SelectKBest, SelectPercentile, RFE) with k-fold | Pandas, Numpy, Warnings, Scikit-learn, Time | Decision Tree, XGBoost, Random Forest, Logistic Regression, Gaussian Naive Bayes, MLP Classifier | iot23_combined.csv | Accuracy, precision, recall, f1-score 
deep-learning.ipynb | Classify the presence of malware | Pandas, Sciki-learn, Warnings, Keras | SVM, Logistic Regression, Random Forest, MLP Classifier, Neural Network: Sequential Model | kaggle: Android Malware Dataset for Machine Learning | Accuracy, Precision, Recall, F1-score, Confusion Matrix 


