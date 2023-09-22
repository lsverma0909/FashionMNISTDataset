# FashionMNISTDataset

In this project, I constructed an image classifier using a ConvolutionalNeural Network (CNN).
\nI downloaded the Fashion-MNIST dataset and normalizeed the data such that pixel values are floats in [0, 1]. 
I then trained a convolutional neural network on the training data with the following layer specifications:
• 2D convolutional layer, 28 filters, 3x3 window size, ReLU activation
• 2x2 max pooling
• 2D convolutional layer, 56 filters, 3x3 window size, ReLU activation
• fully-connected layer, 56 nodes, ReLU activation
• fully-connected layer, 10 nodes, softmax activation
The accuracy for the model was approximately 90%
