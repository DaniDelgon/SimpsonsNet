# SimpsonsNet
A Convolutional Neural Network which classifies characters of the famous TV show 'The Simpsons' with images of the TV show as input.

# Convolutional Neural Network to classify The Simpsons characters from images

In this project, we are going to work with Convolutional Neural Networks to solve an image classification problem. In particular, we are going to classify images of characters from the well-known Simpsons series.

As deep CNNs are a rather advanced and computationally expensive type of model, it is recommended to do the practice in Google Collaboratory with GPU support. This link](https://medium.com/deep-learning-turkey/google-colab-free-gpu-tutorial-e113627b9f5d) explains how to activate an environment with GPUs. *Note: to read images and standardise them to the same size, the opencv library is used. This ĺlibrary is already installed in the Colab environment, but if you are working locally you will have to install it.

<center><img src="https://i.imgur.com/RGanwK4.gif" style="text-align: centre" height="300px"></center>

The dataset to be used consists of images of Simpsons characters taken directly from episodes of the series. This dataset has been compiled by [Alexandre Attia](http://www.alexattia.fr/) and is more complex than the Fashion MNIST dataset we have used so far. Apart from having more classes (we are going to use the 18 characters with more images), the characters can appear in different poses, in different positions of the image or with other characters on the screen (although the character to be classified always appears in the predominant position).

The training dataset can be downloaded from here:

[Training data](https://onedrive.live.com/download?cid=C506CF0A4F373B0F&resid=C506CF0A4F373B0F%219337&authkey=AMzI92bJPx8Sd60) (~500MB)

On the other hand, the test dataset can be downloaded from here:

[Test data](https://onedrive.live.com/download?cid=C506CF0A4F373B0F&resid=C506CF0A4F373B0F%219341&authkey=ANnjK3Uq1FhuAe8) (~10MB)

Before starting the practice, it is recommended to download the images and have a look at them.
