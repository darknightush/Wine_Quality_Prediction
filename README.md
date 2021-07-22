# 🍷 Wine_Quality_Prediction 🍷


### Input variables 📥 (based on physicochemical tests):

1 - fixed acidity
2 - volatile acidity
3 - citric acid
4 - residual sugar
5 - chlorides
6 - free sulfur dioxide
7 - total sulfur dioxide
8 - density
9 - pH
10 - sulphates
11 - alcohol

### Output variable ⏫ (based on sensory data):

12 - quality (score between 0 and 10)

### Tips <br>
What might be an interesting thing to do, is aside from using regression modelling, is to set an arbitrary cutoff for your dependent variable (wine quality) at e.g. 7 or higher getting classified as 'good/1' and the remainder as 'not good/0'.
This allows you to practice with hyper parameter tuning on e.g. decision tree algorithms looking at the ROC curve and the AUC value.
Without doing any kind of feature engineering or overfitting you should be able to get an AUC of .88 (without even using random forest algorithm).


### Live demo link using Heroku :  https://winequality123.herokuapp.com/




# Acknowledgements 📚 :

This dataset is also available from the UCI machine learning repository, https://archive.ics.uci.edu/ml/datasets/wine+quality , I just shared it to kaggle for convenience. (I am mistaken and the public license type disallowed me from doing so, I will take this down at first request. I am not the owner of this dataset.


# How the app looks like:

## 🎯 Inference demo

![wn1](https://github.com/darknightush/Wine_Quality_Prediction/blob/Master/pic2.PNG)
![wn1](https://github.com/darknightush/Wine_Quality_Prediction/blob/Master/pic1.PNG)
![wn1](https://github.com/darknightush/Wine_Quality_Prediction/blob/Master/pic3.PNG)
