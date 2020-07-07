# MNIST_Keras
I have implemented a simple step by step tutorial to create a simple neural network to train MNIST digits.

MNIST is a very common dataset of hand written digits from 0-10. The goal is to create a simple neural network model using popular library Keras/Tensorflow(Keras has been integrated as a part of TF from TF V2.0)
Prepare the dataset by preprocessing.
1) divide into Train and Test sets- Training Set 60000x28x28 and Test set 10000x28x28. Each image is of size 28x28 pixels
2) flatten the images matrix into 60000x784 to feed into the network
3) Normalize the pixel values from [0, 255] to [-0.5 , 0.5]. This makes network easier to train.
4) Build the Network, Train, Test and predict
5) Tune Hyperparameters to improve performance of network.
