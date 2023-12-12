# final_exam Mae Benaroche (50231642)

##### Explain what you do in your project <h6>  

Explain the training dataset

Explain the algorithm you choose 
I chose RandomForestClassifier 
- 'rf_tumor = RandomForestClassifier(max_depth=40)' : creates an instance of the RandomForestClassifier with a hyperparameter max_depth = 40


Explain hyper-parameter of the function
I use the hyperparameter 'max_depth' and set it to 40
- max_depth controls the maximum depth of each tree in the forest



Import Libraries :
- 'import sklearn' : to use sklearn library
- 'from sklearn.ensemble import RandomForestClassifier' : to import RandomForestClassifier class

Instantiate Random Forest Classifier :
- 'rf_tumor = RandomForestClassifier(max_depth=40)' : creates an instance of the RandomForestClassifier with a hyperparameter max_depth = 40
- max_depth controls the maximum depth of each tree in the forest

Training the dataset :
- 'rf_tumor.fit(X_train, y_train)'

Making Predictions :
- 'y_pred=rf_tumor.predict(X_test)' 


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
