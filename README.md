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

This python notebook contains code to build a Neural Network with two hidden layers.
We will use TensorFlow's Keras Sequential API.
Input is Keras California_Housing dataset.
We create two hidden layers with relu activation functions.
We create output layer with 10 neurons with linear activation function



4. Regression_Functional.ipynb

This python notebook contains code to build a Neural Network with two hidden layers.
We will use TensorFlow's Keras Functional API.
Input is Keras California_Housing dataset.
We create two hidden layers with relu activation functions.
We create output layer with 10 neurons with linear activation function



5. Saving a model

Saving a keras model to .h5 file so that unseen data can be tested without having to run code until model building.
Using callbacks is very handy when you have large dataset that takes hours to train the model and you have to save each model after an epoch.



6. Saving a best model based on val_loss and early stopping

Saving best model in the no of epochs we have set.
1. with creterion: val_loss muinimum in the no of epochs
2. with criterion: early stopping by setting patience to 10


7. DigitClassification.ipynb

This python notebook contains code to build a Neural Network with two hidden layers.
Input is Keras mnist dataset for image classification
