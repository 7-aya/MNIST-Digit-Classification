# MNIST-Digit-Classification:

A convolution neural network to classify the MNIST dataset with ~98% accuracy
* Loaded the data from keras dataset API as numpy arrays (the data was already split in train and test)
* Casting the data into float32 to be scaled later into values between [0, 1]
* Built the Sequential using the high-level Keras API built TensorFlow
* Built the model architecture using Keras Neural Network Layers
* Compiled the model using Categorical Loss and Adam optimizer (for momentum optimization to speed up the training)
* Trained the model for five epochs, using the test-set as the cross validation-set ()
* Re-ajusted the model hyperparameters to reach ~98% accuracy

## Package
* Python: 3.9.6
* Tensorflow: 2.7

## Libraries
* keras
* matplotlip
* tensorflow
* numpy

## Training Curves

### 
![image](https://user-images.githubusercontent.com/82214163/142780032-6ad23af6-9347-43aa-a4a8-a6faa122cfc2.png)

![image](https://user-images.githubusercontent.com/82214163/142779277-275e724a-6e48-4d9e-b507-71181fa55caf.png)

<!--
## Model Archetictures Comparison

### CNN Model:
* Training_accuracy = 
### 
-->


