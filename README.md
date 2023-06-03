# EthanCSE455Final
Ethan Barber's CSE 455 final project repo.

# Introduction
Hello, for clarity, I have never work with neural networks so this is my first exposure to them so this may not be quite as rigourous as other groups. Nevertheless, from what I have learned over the last few weeks of the quarter, I have become facinated by the power of nerual networks and their capabilities at being able to accuratly/ semi-accurate idenify complex images. The focus of my project thus will mostly focus on using, and tuning nueral networks to how accurately they can perform to try and gain a greater insight as to how to utilize the neural networks, as well as gain a better foundation so that in the future if I interact and use them again, I have a better understanding and better tools at my displosal to use and utilize these networks.
 
# The Objectives
The main motivator of this project is to develope and train a neural network that accurately can identify birds for the kaggle competetion that was given as a final project for CSE 455. In this dataset, there are 555 different classification of birds which we would like to be able to identify with high accuracy. Thus, apart from my expierimentation, my main objective is to develop a model that performs well, at least in comparasion to my peers models.
My secondary goal for this project, and what most of this website will focus on, is how tuning parameters, adding layers, and number epochs, effect a networks performance, and what seems to be good/advantagous practices when it comes to using, and tuning, a neural network model. Performance will mostly be measuered with respect to it testing accuracy as calcuated on the Kaggle competition website.

# The Project
This project saught to test different ways of testing neural networks to see how they performed against one another. The testing and training data stayed consistent between trials, and every every training set was randomly horizontally agumented to reduce overfitting when training the model. We used the pretrained resnet base model as a foundation for the neural network and then adjusted the final layer to output to the correct number of bird outputs as well as in one of the test cases, we add additional convolutional layers to try and greater improve upon the model. All trials had a resnet base, but then we tested with different parameters.
Each test that was conducted was built off of the previous findings in an attept to create a model that performed well. If I ever attempted a model that performed worse, and sometimes substaintially worse, I back tracked and looked for why that was the case and decided against further pursuing that path.
NOTE: due to code colab usage restrictions, not all tests are entirely equal, but the main goal of finding what worked and what did not when creating our model was still able to be tested and informed by the tests that we performed in making the model.

# The Results

# Conclusions
