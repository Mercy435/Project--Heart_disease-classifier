# End-to-end  Heart Disease Classfication

### This project is a classification problem that tells whether a patient has heart disease or not

### a variety of calssification models is used here and `LogisticRegression` performed best

### An accuracy of 95% is the basis for evaluation in this project

### The steps carried out in this project are:

1. The problem is defined

2. The data can be gotten from https://archive.ics.uci.edu/ml/datasets/heart+Disease
There is also a version of it on kaggle. https://www.kaggle.com/ronitf/heart=disease-uci

3. the metrics for evaluation is defined and the features of the data studied

4. the workplace is made ready by importing all of the necessary libraries needed: `NUMPy` ,`Pandas`, `matplotlib`, 
   `seaborn` and 'sklearn` 

5. the data is loaded using `pd.read_csv("heart-disease.csv")` and exploratory data analysis _EDA_ is done on the it

6. the data is then split into train and test set 

7. a models dictionary which contains three different models is created, and a function is created to pass the data 
   through the model to get the best one
   
8. the models are compared and hyperparameters are tuned by hand, `RandomizedSearchCV` and `GridSearchCV`
   
9. the trained classifier is evaluated on other metrics such as: `ROC curve`, 'Confusion matrix', `Percusion`, `Recall1`
   `f1 score`. 
10. predictions are then made on the test data
