# Number-Recognition

* This code is a Python script that demonstrates how to build and train a neural network model using TensorFlow and Keras to recognize handwritten digits from the MNIST dataset. 
* The script loads the dataset, normalizes the input data, flattens the images to one-dimensional arrays, creates a neural network with three layers (one input, two hidden, and one output), compiles the model, trains the model, evaluates the model's accuracy, saves the trained model, and makes predictions using the saved model.

* The script also creates a confusion matrix to evaluate the performance of the trained model. 
* A confusion matrix is a table that summarizes the actual class labels of a set of samples against the predicted class labels of the same samples.
* The rows of the matrix represent the actual (ground truth) class labels, while the columns represent the predicted class labels. 
* The diagonal elements of the matrix represent the number of correctly predicted samples for each class, while the off-diagonal elements represent the number of incorrectly predicted samples. 
* The confusion matrix is visualized as a heatmap using the seaborn library
