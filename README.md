# StockPrice-ML-Python

The saved CSV file in local directory

![saved csv file](https://user-images.githubusercontent.com/40432616/84531290-0265fe80-ad02-11ea-8ec8-a42e83f25711.PNG)


We Will plot the dataframe using the matplotlib module so in order to do that, Before we need to do the scaling



![scalling of dataframe before plotting](https://user-images.githubusercontent.com/40432616/84531802-c1221e80-ad02-11ea-9424-fcb068d9c034.PNG)


We will be using the sklear.prepocessing import minmax scaler, for scalling of the dataframe

Why is the use of scaling the data(s) in the dataframe?

![minmax scaler](https://user-images.githubusercontent.com/40432616/84535029-9a66e680-ad08-11ea-9759-9a7d02647e2c.PNG)


Trainning data scaling -> we have kept the percentage as 65

![trainning data 65 percentage](https://user-images.githubusercontent.com/40432616/84535741-0138cf80-ad0a-11ea-8834-c104881a924b.PNG)


  BEFORE CREATING OUR LSTM MODEL WE HAVE TO RESHAPE OUR TRAINING DATA & TEST DATA( X_TRAIN AND X_TEST)

![reshape LSTM](https://user-images.githubusercontent.com/40432616/84751763-8eb24300-afda-11ea-89f3-ac9b34a003d4.png)



Introduction of the sequential Model of Keras.Sequential of Tensorflow.

Keras Tuner is an easy-to-use, scalable hyperparameter optimization framework that solves the pain points of hyperparameter search. Easily configure your search space with a define-by-run syntax, then leverage one of the available search algorithms to find the best hyperparameter values for your models. Keras Tuner comes with Bayesian Optimization, Hyperband, and Random Search algorithms built-in, and is also designed to be easy for researchers to extend in order to experiment with new search algorithms.

![sequential model](https://user-images.githubusercontent.com/40432616/85585257-763acc00-b65d-11ea-91b2-8197ae77dd6f.PNG)

Importing the keras model 

![import model keras](https://user-images.githubusercontent.com/40432616/85585607-c31ea280-b65d-11ea-80b0-15bbc85733f0.PNG)

Below are the two main points.

Sequential groups a linear stack of layers into a tf.keras.Model.
Sequential provides training and inference features on this model.

for the LSTM Documentation please refer the below links.


