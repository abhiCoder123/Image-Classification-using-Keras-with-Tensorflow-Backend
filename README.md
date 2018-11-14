# Image-Classification-using-Keras-with-Tensorflow-Backend

## Overview
A simple image recognition tool that classifies whether the image is of a dog or a cat.The same concept can applied to a diverse range of objects with a lot of training data and appropriate network.

## Tools And Technologies

**1)Anaconda** — Anaconda is a free and open source distribution of the Python and R programming languages for data science and machine learning related applications, that aims to simplify package management and deployment. You can download it from the link below according to your system https://www.anaconda.com/download/

**2)Spyder** — Spyder is an open source cross-platform IDE for scientific programming in the Python language. It comes installed with anaconda. If not, install it using anaconda navigator.

**3)Tensorflow** — TensorFlow is an open-source software library for dataflow programming across a range of tasks. Download link — https://www.tensorflow.org/install/install_windows

**4)Keras** — Keras is an open source neural network library written in Python. Activate Tensorflow env and install keras using:
```
pip install keras
```

**5)CNN** — Convolution Neural network , a class of deep, feed-forward artificial neural networks, most commonly applied to analyzing visual imagery.

#### Setup
This repository contains a directory called **dataset** containing folders **training_set** and **test_set**. Each of these folders will contain folders for the two classes: **dogs** and **cats**. It should look like this:
```
dataset/
    training_set/
        dogs/
            dog.1.jpg
            dog.2.jpg
            ...
        cats/
            cat.1.jpg
            cat.2.jpg
            ...
    validation/
        dogs/
            dog.4001.jpg
            dog.4002.jpg
            ...
        cats/
            cat.4001.jpg
            ca.4002.jpg
            ...
 ```
We will be using 4000 images for each of the classes to train the Convolutional Neural Network. Additionally we will use 1000 images each for validation and to evaluate our model.

#### Execute
Navigate to the directory where you have your **data** folder and run *classify.py*
```
python cnn.py
```
