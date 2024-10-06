Style Transfer
In this notebook, we are going to replicate a technique for style transfer as described in the research paper titled "Image Style Transfer Using Convolutional Neural Networks" by Gatys, using the PyTorch framework.

The paper presents a method where style transfer leverages the features identified in the VGG19 Network, a deep neural network with 19 layers. This network consists of a sequence of layers, including convolutional layers, pooling layers, and a few fully-connected layers.

The convolutional layers within this network are identified in a specific manner: they are named based on the 'stack' they belong to and their position within that stack. For example, 'Conv_1_1' refers to the very first convolutional layer the image encounters in the first stack. Similarly, 'Conv_2_1' denotes the initial convolutional layer in the second stack. The last and deepest convolutional layer in this network is referred to as 'conv_5_4'.
