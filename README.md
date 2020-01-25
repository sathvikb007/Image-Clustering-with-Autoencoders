# Image-Clustering-with-Autoencoders

An autoencoder is a neural network that is trained to attempt to copy its input to its output. Internally, it has a hidden layer that describes a code used torepresent the input. The network may be viewed as consisting of two parts: an encoder function h=f(x) and a decoder that produces a reconstruction r=g(h). If an autoencoder succeeds in simply learning to set g(f(x)) =x everywhere, then it is not especially useful. Instead, it is designed to learn useful properties of the dataset.

Application : Image clustering


  Image clustering involves the process of mapping an archive image into a cluster such that
the set of clusters has the same information. It is an important field of machine learning and computer
vision. While traditional clustering methods, such as k-means or the agglomerative clustering method,
have been widely used for the task of clustering, it is difficult for them to handle image data due
to having no predefined distance metrics and high dimensionality. To solve this problem, deep unsupervised
feature learning methods, such as the autoencoder (AE), have been employed for image clustering. These
autoencoders are used to reduce the dimensionality of images and learn useful features to improve clustering
results. In this project, 
3 such types of autoencoders have been implemented: 

    1) A simple autoencoder (SAE) with one hidden layer
    
    2) A deep autoencoder (DAE) with more than one hidden layer
    
    3) A convolutional autoencoder(CAE)
    
The project utilizes the fashion MNIST dataset - consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. The link to the dataset:

https://github.com/zalandoresearch/fashion-mnist

The code is written in Python with the help of Keras.
