1. Perceptron.ipynb

This python notebook contains code to build a basic perceptron (single neuron).
We will use scikit-learn's linear_model and import Perceptron module.
We will build a very basic neural network model for CLASSIFICATION with one layer and one perceptron
We will then use scikit_learn's iris dataset to fit and test out model.



2. Classification_Sequential.ipynb

This python notebook contains code to build a Neural Network with two hidden layers.
We will use TensorFlow's Keras Sequential API.
Input is Keras fashion_mnist dataset. Images are of 28 x 28 pixels.
We create two hidden layers with relu activation functions.
We create output layer with 10 neurons with softmax activation function

3. Regression_Sequential.ipynb

This python notebook contains code to build a simple sequential and Multi Layer Perceptrion(MLP) sequential NN model.
We will use TensorFlow's Keras Sequential API.
Input is sklearn's california_housing dataset.


4. Functional.ipynb

This python notebook contains code to build a complex Functional NN model for regression.
We will use TensorFlow's Keras Functional API.
Input is sklearn's california_housing dataset.


5. Callbacks_During_Training.ipynb
In this notebook, we will use Callbacks during training to save a model in .h5 extension so we can load and use at a later time. Using callbacks is very handy when you have large dataset that takes hours to train the model and you have to save each model after an epoch.
This is also helpful in cases of unexpected interruption, so we wont lose th eentire progress of training.
