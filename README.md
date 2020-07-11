# StockPrice-DeepLearning-Python

## Difference between Machine Learning and Deep Learning?

</br> Deep learning is just a subset of machine learning. In fact, deep learning technically is machine learning and functions in a similar way (hence why the terms are sometimes loosely interchanged). However, its capabilities are different.

</br> While basic machine learning models do become progressively better at whatever their function is, they still need some guidance. If an AI algorithm returns an inaccurate prediction, then an engineer has to step in and make adjustments. With a deep learning model, an algorithm can determine on its own if a prediction is accurate or not through its own neural network.

## Why to use Neural Networks in Machine Learning?

A deep neural network analyzes data with learned representations akin to the way a person would look at a problem. In traditional machine learning, the algorithm is given a set of relevant features to analyze, however, in deep learning, the algorithm is given raw data and derives the features itself.

### What's the difference between LSTM and GRU?

-LSTM (Long Short Term Memory): LSTM has three gates (input, output and forget gate)

-GRU (Gated Recurring Units): GRU has two gates (reset and update gate).

-GRU couples forget as well as input gates. GRU use less training parameters and therefore use less memory, execute faster and train faster than LSTM's whereas LSTM is more accurate on dataset using longer sequence. In short, if sequence is large or accuracy is very critical, please go for LSTM whereas for less memory consumption and faster operation go for GRU. If you donot have much floating point operations per second (FLOP's) to spare switch to GRU. LSTM has three values at output (output, hidden and cell) whereas GRU has two values at output (output and hidden).



### Q) Is there any difference between in LSTM and ML?

</br>Points to be remember while performing this project:
</br> 1) The individual shud have a grasp of good knowledge of numpy and pandas.
</br> 2) The individual shud have a grasp of knowledge of using jupyter notebook




### Creating and Saving a local .CSV file in local directory
The saved CSV file in local directory

![saved csv file](https://user-images.githubusercontent.com/40432616/84531290-0265fe80-ad02-11ea-8ec8-a42e83f25711.PNG)


We Will plot the dataframe using the matplotlib module so in order to do that, Before we need to do the scaling



![scalling of dataframe before plotting](https://user-images.githubusercontent.com/40432616/84531802-c1221e80-ad02-11ea-9424-fcb068d9c034.PNG)


We will be using the sklear.prepocessing import minmax scaler, for scalling of the dataframe

### Why is the use of scaling the data(s) in the dataframe?

![minmax scaler](https://user-images.githubusercontent.com/40432616/84535029-9a66e680-ad08-11ea-9759-9a7d02647e2c.PNG)


Trainning data scaling -> we have kept the percentage as 65

![trainning data 65 percentage](https://user-images.githubusercontent.com/40432616/84535741-0138cf80-ad0a-11ea-8834-c104881a924b.PNG)


### BEFORE CREATING OUR LSTM MODEL WE HAVE TO RESHAPE OUR TRAINING DATA & TEST DATA( X_TRAIN AND X_TEST)

![reshape LSTM](https://user-images.githubusercontent.com/40432616/84751763-8eb24300-afda-11ea-89f3-ac9b34a003d4.png)



## Introduction of the sequential Model of Keras.Sequential of Tensorflow.

</br> Keras Tuner is an easy-to-use, scalable hyperparameter optimization framework that solves the pain points of hyperparameter search. Easily configure your search space with a define-by-run syntax, then leverage one of the available search algorithms to find the best hyperparameter values for your models. Keras Tuner comes with Bayesian Optimization, Hyperband, and Random Search algorithms built-in, and is also designed to be easy for researchers to extend in order to experiment with new search algorithms.

![sequential model](https://user-images.githubusercontent.com/40432616/85585257-763acc00-b65d-11ea-91b2-8197ae77dd6f.PNG)

### Importing the keras model 

![import model keras](https://user-images.githubusercontent.com/40432616/85585607-c31ea280-b65d-11ea-80b0-15bbc85733f0.PNG)

### Below are the two main points.

</br> Sequential groups a linear stack of layers into a tf.keras.Model.
</br> Sequential provides training and inference features on this model.

for the keras Model Documentation please refer the below links.
1) -> https://keras.io/api/models/model/


After setting the epochs value and after executing it we need to set the test/train data
    do check the highlighted texts
![setting the test and train data](https://user-images.githubusercontent.com/40432616/85873347-9e0d6980-b7ee-11ea-9ad9-31e58107a0da.PNG)


****Why to use Keras Model Library API?*****

  The Keras Python library makes creating deep learning models fast and easy.

  The sequential API allows you to create models layer-by-layer for most problems. It is limited in that it does not allow you to create models that share layers or have multiple inputs    
  or outputs.

   The functional API in Keras is an alternate way of creating models that offers a lot more flexibility, including creating more complex models.
