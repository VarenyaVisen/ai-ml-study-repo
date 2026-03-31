# Chapter 2: Supervised Learning
supervised learning is the type of learning where we have the labeled data i.e for every input we have its corresponding output, we use supervised learning whenever we want to predict a certain outcome from a given input and we have example of both input and output 

There are 2 major types of supervised machine learning problems:
- Classification
- Regression

In classification the goal is to predict class label which is a choice from a predefined list of possibilities 
classification is sometimes separated into binary classification which is the specaial case of distinguishing between 2 classes and multi class classification which is classification between more than 2 classes eg - classifying whether a mail is spam or not, iris flower classification

For regression tasks the goal is to predict a continuos number, or a floating point number eg-  predicitng house prices based on some features like no. of rooms, location, area etc


Some terms in ml:
- Generalization : if a model is able to make accurate predictions on unseen data, we say it is able to generalize from training set to the test set. we want to build a model that is able to generalize as accurately as possible 
- Overfitting : If a model is too complex for the amount of information we have then model overfits, basically it occurs when model fits too perfectly on the training set that it no longer genralizes better on the unseen data
- underfitting :  If a model is too simple that it doesn't perform well even on the training dataset then its called underfitting  

there is a sweet spot between which yeild the best genralization that is what we want to find 

* Relation of model complexity to dataset size
=> model complexity is intimately tied to the variation of inputs contained in your training dataset, the larger the variety of data points data set contains the more complex model can be used without problem of getting overfit
usually collecting more data will yield more variety so larger datasets allow building more complex models 
note - never underestimate the power of more data