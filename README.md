# Number-Recognition

This code demonstrates how to build and train a neural network to classify handwritten digits using the popular MNIST dataset. 

* The MNIST dataset consists of 70,000 grayscale images of size 28x28, representing the digits 0-9.

* The code first loads the dataset using TensorFlow's built-in function, and then normalizes the pixel values of the images. It then flattens the 2D arrays of the images into 1D arrays for use in the neural network.

* Next, the code defines a neural network with three layers: an input layer, two hidden layers, and an output layer. The input layer is simply a flattened version of the image data. The two hidden layers have 128 neurons each, with the ReLU activation function. The output layer has 10 neurons (one for each digit), with the softmax activation function.

* The code then compiles the model with the Adam optimizer, sparse categorical cross-entropy loss function, and accuracy metric. It trains the model using the training data for one epoch, and then evaluates its performance on the test data.

* The code also saves the trained model and loads it back for prediction. It predicts the labels of the test data and generates a confusion matrix to evaluate the model's performance. Finally, it visualizes the confusion matrix using a heatmap.

* Overall, this code provides a basic example of building, training, and evaluating a neural network for image classification using TensorFlow and Keras. It can serve as a useful starting point for beginners looking to learn about deep learning.
