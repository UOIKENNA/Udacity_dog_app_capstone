# Udacity_dog_app_capstone
The mission of this project is to classify dog based on their breeds, by analysing images of dogs. This will be carried out using Convolutional Neural Networks CNN and datasets provided by Udacity for the purpose of the project.

# Instructions
The project instructions can be found [here](https://github.com/udacity/dog-project.git)

# Table of Contents
1. [Installation](https://github.com/UOIKENNA/Udacity_dog_app_capstone#Installation)
2. [Project Motivation](https://github.com/UOIKENNA/Udacity_dog_app_capstone#Project)
3. [File Descriptions](https://github.com/UOIKENNA/Udacity_dog_app_capstone#File)
4. [Results](https://github.com/UOIKENNA/Udacity_dog_app_capstone#Results)
5. [Licensing, Authors and Acknowledgements](https://github.com/UOIKENNA/Udacity_dog_app_capstone#licensing)


# Installation
The code should run without issues using Python 3.*. Some of the libraries used include;Tensorflow, Keras, Numpy, Matplotlib, CV2, tqdm. The source code was written in Jupyter Notebook. All the necessary libraries were imported using the Anaconda distribution.

# Project Motivation
Image classification has become one of the most influential innovations in Computer Vision since the first digital image scanner. Developing models that can classify images has made tremendous advances in the way people interact (social media, search engines & image processing), retail (both in person and online), marketing, theatre & the performing arts, government, surveillance, law enforcement, etc. Thanks to image classification algorithms we are able to receive notifications on social media when someone has posted a picture that may look like us, or object recognition in self driving cars! The idea of a program being able to identify meaningful objects in an image and make a judgement as to what it is, what it’s connected with and where it belongs based on only the information found in an image has endless applications. I have implemented this classification using Convolutional Neural Networks. This project is part of my Udacity nanodegree and I give credit to them for the data sources used and also some of the code in this write up. The project description is available [here](https://github.com/udacity/dog-project). The datasets provided by Udacity for this project include;

Dog Images — This is a dataset of images of different types of dogs we used

Human Faces — This consists of different human faces used for the classification.

# File Descriptions
This repository consists of one 
1. dog_app.ipynb file - A jupyter notebook with the main code
2. dog_app.html file - the html version of the jupyter notebook

# Results and Conlusion
As shown in this project, CNN implementation is a relatively straight forward way of performing image classification . Keras provides a simple way to implement multiple types of CNN architectures and facilitates easy fine tuning of hyperparameters so that models can be easily optimized. Our initial model had a very low accuracy of 3.5%, but with the application of transfer learning I was able to increase the performance to 80.9%. The aspect of the algorithm being able to liken a human face to a dog image was something I found intriguing. Despite it’s relatively fair accuracy score, the algorithm was able to accurately predict the sample images it was supplied with.

However, we still see several options to further improve our algorithm in the future:
1. We could gather more training data.
2. We could employ data augmentation to prevent overfitting.
3. In this project, I have tried training the model on VGG-16 and InceptionV3. One next step could be to try training the models using different architectures as well as changing the architect of our fully connected layers.

A detailed report can be found [here](https://uikenna97.medium.com/dog-breed-classification-7706e7a946af)

# Licensing, Authors and Acknowledgements
I credit Udacity for the support and lessons given to me. This project is free to use and contributions are welcome.
