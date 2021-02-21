<p align="center"><a href="https://www.tensorflow.org"><img width=100 src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2d/Tensorflow_logo.svg/1200px-Tensorflow_logo.svg.png"/></a></p>

# CNN Networks

I have decided to implement some popular CNN networks which are used in several deep-learning networks as the backbone networks i.e. VGG16/19, Resnet, GoogleNet, etc.

Each network will be placed in a folder on the main project root and contains of a **Jupyter notebook** and some python classes. They also may consist of their c++ implementation as well.

> **Note**: My implementations are under TensorFlow (tf) and Keras. Any other platforms (i.e. pytorch) may be included for some networks but, the main considered framework is tf.

## Jupyter Notebook

The jupyter notebook consists of an introduction to the network architecture, step by step implementation, and some testing results. This could be used as a review/reminder and/or teaching assistant.

## Python Classes

Each network is a python class that could be used separately in some projects and implementations. I try my best that the codes have the most flexibility on eloquent for being used in various projects.

## C++

For real-time implementation and real-world projects, some times it is suggested to have the c++ code as well. I also try to write the c++ implementation for each network. The codes could also be used in embedded devices such as Raspberry Pi, Android phones, IOS devices, and those support TensorFlow-Lite.
If a network consists of such an code, it also may had application called _demo_ to represent the resualts on some of these devices. (my favorite is Raspberry Pi 3 model B)

## List of available/future networks

1. Lenet5
2. VGG16
3. VGG19
4. AlexNet
5. GoogleNet
6. RetinaNet
7. Inseption
8. SSD
9. Resnet
10. YOLOv4
11. RefineDet
