# MNIST Digit Classification using a Convolutional Neural Network

This project implements a convolutional neural network (CNN) to classify handwritten digits from the MNIST dataset, achieving approximately 98% accuracy.

* Data Preparation: The MNIST dataset was loaded using Keras' dataset API. The data, already split into training and testing sets, was converted to NumPy arrays and cast to float32 for subsequent scaling to the range [0, 1].

* Model Building: The model was constructed using the Keras Sequential API, built on top of TensorFlow. The architecture consists of convolutional layers, pooling layers, and fully connected layers. 

* Model Compilation and Training: The model was compiled using categorical cross-entropy loss and the Adam optimizer. Adam was chosen for its momentum-based optimization, which helps accelerate the training process. Training was performed for five epochs, utilizing the test set for validation.

* Hyperparameter Tuning: Model hyperparameters, such as the learning rate, number of filters, kernel sizes, or number of layers, were iteratively adjusted to achieve the target accuracy of ~98%.

* Results: The final model achieved an accuracy of ~98% on the MNIST test set.

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


