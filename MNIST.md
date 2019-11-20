# Homework 2
Build and train a `MLP` Model to classify the ***MNIST*** dataset:
1. `MLP` networks accepts one-dimensional data.
	So, we should flatten our 2D image, and then print the dimension of the result arrays.
1. Normalize data by rescaling them to (0,1).
1. Convert label arrays to one-hot representation (`keras.utils.to_categorical`).
1. Define the Model.
	- Hidden Layer 1: Fully Conncted + Relu Activition (e.g. 512 Nuerons)
	- Hidden Layer 2: Fully Connected + Relu Activition (e.g. 512 Neurons)
	- Outout Layer: Fully Connected + Softmax Activition

Build and train a `CNN` + `MLP` deep learning model with Keras with followings specs for the ***MNIST*** dataset:
- `Conv2D(32, kernel_size=(3, 3), activation='relu')`
- `Conv2D(64, kernel_size=(3, 3), activation='relu')`
- `MaxPooling2D(pool_size=(2, 2))`
- `Dense(128, activation='relu')`
- `Dense(num_classes, activation='softmax')`

Also build another model with BatchNormalization and Dropout.
Compare these two `CNN` + `MLP` models performance for test data.
