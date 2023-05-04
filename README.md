# Autoencoder-and-classifier-for-encoded-MNIST

In this program purpose is making an autoencoder with Fully Connected Neural Networks and making a classifier to class encoded MNIST images First
of all we import the dataset and after visualizing data we make a fully connected neural network as a autoencoder, dimension of input is 784 and
dimension of output is also 784 and in center of the network there is output of encoder that has 30 dimenision and after that there is decoder part
and input of this part has 30 dimension and output of this part that is also output of whole of the network has 784 dimension.

Desired Autoencoder has a slight loss becasue when loss is very slight it means that the output image is as good as the main image.

After making the autoencoder and defining first part of the network as encoder and last part of the network as decoder we want to
make a classifier that can classify encoded images.
