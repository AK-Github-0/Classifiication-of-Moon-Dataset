# Classifiication-of-Moon-Dataset
## Introduction
This repository contains code that creates a neural network model using TensorFlow and Keras to classify the moons dataset. The moons dataset is a non-convex two-dimensional dataset consisting of two interleaved half circles.

The repository contains various examples of how to modify the model by increasing the number of hidden layers and neurons, normalizing the data, and using different optimizers with different parameters.

## Installation
Clone this repository to your local machine using git clone https://github.com/yourusername/yourproject.git
Ensure you have TensorFlow and Keras installed on your machine. If not, you can install them via pip by running pip install tensorflow keras.
Run the Python code in the main.py file.

## Usage
Classificiation by NN & SVM.ipynb file contains the code to train and test the model. When you run the file, it will first generate the moons dataset, split it into training and test sets, and then train the model using the training set.

After training, the script will output the test accuracy percentage and a confusion matrix showing the classification performance of the model on the test set. The script will also output a classification report, which shows other classification metrics such as precision, recall, and F1 score.

In the Classificiation by NN & SVM.ipynb file, you can modify the number of epochs, batch size, and other parameters for training the model. Additionally, you can modify the number of hidden layers and neurons to test different configurations of the model.

## Results
The repository includes various examples of how to modify the model architecture and parameters to achieve better performance on the moons dataset. The following is a summary of the results obtained from the different models:

Basic model with one hidden layer and 50 neurons achieved a test accuracy of 84.85%.
Model with two hidden layers and 50 and 30 neurons respectively achieved a test accuracy of 87.88%.
Model with two hidden layers and 50 and 45 neurons respectively achieved a test accuracy of 87.88%.
Model with two hidden layers, 50 and 30 neurons respectively, and normalized data achieved a test accuracy of 87.88%.
Model with one hidden layer and 50 neurons and Stochastic Gradient Descent optimizer with learning rate 0.09 and momentum 0.1 achieved a test accuracy of 87.88%.

## Contributing
If you would like to contribute to this repository, please open an issue or submit a pull request. All contributions are welcome!
