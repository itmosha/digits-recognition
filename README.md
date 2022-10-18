## About this project

This project is an example of a basic sequence neural network which is trained for recognising handwritten digits. I used TensorFlow for creating and training the network, and also some additional libraries are included (OpenCV for working with images, Numpy for arrays handling and matplotlib for visualisation the results).

### Neural network structure

There are four layers in the network:
1. Input layer, used for getting a 28 by 28 image as an input data
2. Inner dense layer with 128 neurons and ReLU activation function
3. Another dense layer (same as the second)
4. Output layer with 10 possible results (0 - 9 digits) and softmax activation function (checks if all neurons values sum up to 1)

It is trained using the [MNIST](http://yann.lecun.com/exdb/mnist/) handwritten digits dataset.

### Predicting your handwritten digits

You can use any 28x28 black on white image with a digit on it and put it in the digits directory. The neural network will try to make a prediction according to the image you gave it.

You should put your images into the digits directory and specify every image name as 'digit1.png', 'digit2.png', etc.

```
digits:
    digit1.png
    digit2.png
    digit3.png
    ...
```

