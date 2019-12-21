# Identify-The-Apparel-using-ML
I have trained a Machine Learning Algorithm to Identify the apparel in the image. The training images were stored in Google Drive. Thus, I used Google Colab for my project.
Google has done the coolest thing ever by providing a free cloud service based on Jupyter Notebooks that supports free GPU. Not only is this a great tool for improving your coding skills, but it also allows absolutely anyone to develop deep learning applications using popular libraries such as PyTorch, TensorFlow, Keras, and OpenCV.

In case someone decides to use my source code in their local machine, make sure that your Pip (Pip install packages) is updates. If not, use the **python -m pip install --upgrade pip** command to do the same. 


## Problem Statement:

We have a total of 70,000 images (28 x 28 dimension), out of which 60,000 are from the training set and 10,000 from the test one. The training images are pre-labelled according to the apparel type with 10 total classes. The test images are, of course, not labelled. The challenge is to identify the type of apparel present in all the test images.

The following table gives a list of labels and their corresponding apparel:

|     Label     |  Description  |
| ------------- | ------------- |
|       0       |  T-shirt/top  |
|       1       |    Trouser    |
|       2       |    Pullover   |
|       3       |     Dress     |
|       4       |     Coat      |
|       5       |     Sandal    |
|       6       |     Skirt     |
|       7       |     Shoe      |
|       8       |      Bag      |
|       9       |   Ankle Boot  |
