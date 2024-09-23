# Neural Net Architectures From Zero To Here

1. LeNet

    LeNet is a convolutional neural network architecture introduced by Yann LeCun in 1998. It was designed for handwritten digit recognition and laid the foundation for many modern CNN architectures.

    LeNet-5 consists of the following layers:

    - Input layer (32x32 grayscale image)
    - Convolutional layer (6 feature maps, 5x5 kernel)
    - Average pooling layer (2x2)
    - Convolutional layer (16 feature maps, 5x5 kernel)
    - Average pooling layer (2x2)
    - Fully connected layer (120 units)
    - Fully connected layer (84 units)
    - Output layer (10 units, one for each digit)