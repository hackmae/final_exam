# final_exam Mae Benaroche (50231642)

## Explain what you do in your project <h4>  
In this project we need to find the best model to fit training data points about tumor by using scikit learn.

First we need to import the libraries, packages we need to use in our project 
- sklearn, numpy, matplotlib...

Then we load data points from our external file named 'Training' in the same file as this jupyternotebook file in a folder named 'tumor_dataset'

After that, we divide the datasets into two parts, the training datasets and the test datasets

Now we can use a model for tumor classification :

Instantiate Random Forest Classifier :
- 'rf_tumor = RandomForestClassifier(max_depth=40)' : creates an instance of the RandomForestClassifier with a hyperparameter max_depth = 40
- max_depth controls the maximum depth of each tree in the forest

Training the dataset :
- 'rf_tumor.fit(X_train, y_train)'

Making Predictions :
- 'y_pred=rf_tumor.predict(X_test)' 


## Explain the training dataset <h4>
The training dataset is ...

## Explain the algorithm you choose <h4>
I chose RandomForestClassifier 
- 'rf_tumor = RandomForestClassifier(max_depth=40)' : creates an instance of the RandomForestClassifier with a hyperparameter max_depth = 40


## Explain hyper-parameter of the function <h4>
I use the hyperparameter 'max_depth' and set it to 40
- max_depth controls the maximum depth of each tree in the forest



Motivation
Build Status
Code Style
Screenshots
Tech/Framework used
Features
Code Examples 
Installation
API Reference 
Tests
How to use ?
Contribute
Credits
License 

code added : 
rf_tumor = sklearn.ensemble.RandomForestClassifier(max_depth=40)
rf_tumor.fit(X_train, y_train)
y_pred=rf_tumor.predict(X_test)

accuracy : 0.90
