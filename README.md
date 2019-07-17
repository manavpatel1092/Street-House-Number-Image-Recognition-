# Street-House-Number-Image-Recognition

We built a Convolutional Neural Network (CNN) on the SVHN dataset which consists of real-world street view house number images. 
- 'Relu' was used as the activation function for the hidden layers. 
- Two neural network models were built, with and without Batch Normalization, to observe the differences. 
- The model with Batch Normalization performed a bit well than the other, giving us the accuracy of about 89%.

The dataset used in this task is acquired from stanford repository. Dataset with Format 2 is used in this task. You can access it from the following URL:
http://ufldl.stanford.edu/housenumbers

Overview of the dataset:
- 10 classes, 1 for each digit. Digit '1' has label 1, '9' has label 9 and '0' has label 10.
- 73257 digits for training, 26032 digits for testing, and 531131 additional, somewhat less difficult samples, to use as extra training data.
- Comes in two formats:
1. Original images with character level bounding boxes.
2. MNIST-like 32-by-32 images centered around a single character (many of the images do contain some distractors at the sides).


