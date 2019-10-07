# Cat-Classifier
Image Classifier trained on cat images.

In the logistic regression folder the ipython notebook contains the code to create a logistic regression model. The model is built by mathematically calculating the loss function for the images of entire data set create a model that can identify cat images. But here we observe that the confidence value is not that high even if it recognizes a picture of cat.

In the shallow neural network folder the ipython notebook contains the code which compares logistic regression model to other shallow and deep neural network on does it perform on classification of data.

In the deep neural network folder the ipython notebook contains two folders, first is the helper method folder which contains the ipython notebook contains where all the utility function like loss calculation, forward propagation and backward propagation done mathematically. These utility functions are used while building the models whose code is in second folder deep neural network model is used for training and then classifying novel images.

The test utils are used to do some sanity test after completing each of utility functions.

# Screenshots

Logistic Regression Model Result
![image](https://user-images.githubusercontent.com/16362957/53358289-e9dba480-3955-11e9-9060-ded566ca7d25.png)

Compare Multiple Models

Logistic Regression Model
![image](https://user-images.githubusercontent.com/16362957/53358398-36bf7b00-3956-11e9-8561-a61431e213cf.png)

Neural Network Model
![image](https://user-images.githubusercontent.com/16362957/53358467-75553580-3956-11e9-8e92-c3ee2b2f45ac.png)

Deep Neural Network Result
![image](https://user-images.githubusercontent.com/16362957/53358587-c402cf80-3956-11e9-88be-5f12a1d1818e.png)
![image](https://user-images.githubusercontent.com/16362957/53358612-d11fbe80-3956-11e9-8e7a-401e72fed58a.png)

# Dependencies
Python 3,
Numpy,
Scipy,
Matplotlib,
h5py,
SciKit Learn.

# References
https://www.coursera.org/learn/neural-networks-deep-learning
