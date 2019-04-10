# Regularisation

### Underfitting and Overfitting 
* Last session we talked about two sets,the training and test set
* Training set is used in the creation of the model
* We can run the model on the training set to determine the correct weights and biases 
* We then use a seperate test,to see how the model performs on new examples 
* The central challenge in machine learning is to make our model perform well on previously unseen inputs
* Typically,when training a machine learning model,we compute the "loss" on the training set and try to minmimise it using Gradient Descent
* This is simply Optimisation,but in Machine Learning,we are also interested in minimising the test error 
* When we use a ML model,we do not set the parameteres ahead of time ,we first train it on the training set,then se the parameters to test it on the test set
* Under this process,the expected test set error is greater than or equal to the expected value of the training error
* So,there are mainly two factors which determine how well a ML model will perform 
* The first one is, the training error should be small
* Secondly, the gap between the training and test error should be small
* These two factors are the reason for the two biggest challenges in ML, Overfitting and Underfitting  

<p>
  <img src="https://github.com/akshaydevml/Intro-to-Machine-Learning-Workshop/blob/master/uofitting_1.jpg" height="200" width="400" alt="Over and Under fitting"/>
</p>

* Undeffitting occurs,when the model is not able to obtain a sufficiently low error value
* Overfitting occurs, when the gap between the training and test error is too large


### Regularisation 

<p>
  <img src="https://github.com/akshaydevml/Intro-to-Machine-Learning-Workshop/blob/master/regularisation_1.jpg" height="200" width="400" alt="Regularisation"/>
</p>

* To alleviate the problem of underfitting and overfitting,we implement Regularisation
* Last lecture, we talked about features,and how each feature contributes differently to the loss function 
* Sometimes, we have to express preference for one feature over the other 
* For example, we might express a preference for linear features over non-linear features 
* There are many ways of expressing preferences, together they are called "Regularisation"
* There are many type of Regularisation,L2 regularisation,Dropout regularisation
* In dropout regularisation, we take out random nodes for every iteration.
* The intuition behind dropout regularisation is that, we can't rely on one feature,so we have to spread out the weights


### Validation Set

* Till now,we talked about the test set and the training set
* However,there is one more set,called the Validation set 
* Earlier,we talked about test set,which we use to test how well the model generalises to new examples
* But,it is also important that we don't use the test set to fine tune our Hyperparameters
* Therefore,we need a new set,this is the validation set.It is always constructed from the training set,by splitting it into     two
* We use the validation set to estimate the generalisation error and update our hyperparameters accordingly 
