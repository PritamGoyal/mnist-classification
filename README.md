# mnist-classification
Machine Learning | Deep Learning
A MNIST classifier is a type of machine learning model designed to recognize and classify handwritten digits from the MNIST dataset. MNIST, which stands for Modified National Institute of Standards and Technology database, is a widely used dataset in the field of computer vision and machine learning. It consists of a collection of 28x28 pixel grayscale images of handwritten digits (0 through 9), with each image labeled with the corresponding digit it represents.
Input Data: The MNIST classifier takes as input a 28x28 pixel grayscale image of a handwritten digit. Each pixel's intensity value ranges from 0 (white) to 255 (black).
Preprocessing: Before feeding the data into the classifier, preprocessing steps may be applied, including normalization (scaling pixel values to a range between 0 and 1) and reshaping the 28x28 image into a flat vector of 784 (28*28) features.
Model Architecture: The classifier uses a neural network architecture, commonly a deep convolutional neural network (CNN). A typical CNN for MNIST classification consists of multiple layers, including convolutional layers, pooling layers, and fully connected layers.
It contains a input layer having 784 input units. 
It has two hidden layers with relu activation function.
It has a output layer with softmax function and 10 output units.
Sparse categorical crossentropy serves as our loss function.
We have achieved a accuray of 97.87%
