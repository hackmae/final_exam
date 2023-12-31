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

Then we print the accuracy of our model :
- 'print('Accuracy: %.2f' % sklearn.metrics.accuracy_score(y_test, y_pred))'

## Explain the training dataset <h4>
The training dataset is composed of images taken in a lab to see if someone has a tumor or not and if he has one which one it is.
Each data has one of the 4 differents states of tumor : glioma tumor, meningioma tumor, pituitary tumor and no tumor  

## Explain the algorithm you choose <h4>
I chose RandomForestClassifier because I have the greatest accuracy with this algorithm, the parameters are pretty straightforward and it avoids overfitting problem.
- 'rf_tumor = RandomForestClassifier(max_depth=40)' : creates an instance of the RandomForestClassifier with a hyperparameter max_depth = 40


## Explain hyper-parameter of the function <h4>
I use the hyperparameter 'max_depth' and set it to 40
- max_depth controls the maximum depth of each tree in the forest

