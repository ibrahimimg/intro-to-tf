# Introduction To Tensorflow for AI

My Solutions for Programming Assignments from coursera course: Introduction to Tensorflow for Artificial Intelligence, Machine Learning and Deep Learning by deeplearning.ai

course link: [https://www.coursera.org/learn/introduction-tensorflow](https://www.coursera.org/learn/introduction-tensorflow)

tensorflow version: 1.14.0

## Exercise 1: Your first Neural Network (Housing Prices)
[week1](week1)

In this exercise you'll try to build a neural network that predicts the price of a house according to a simple formula.
So, imagine if house pricing was as easy as a house costs 50k + 50k per bedroom, so that a 1 bedroom house costs 100k, a 2 bedroom house costs 150k etc.
How would you create a neural network that learns this relationship so that it would predict a 7 bedroom house as costing close to 400k etc.

Hint: Your network might work better if you scale the house price down. You don't have to give the answer 400...it might be better to create something that predicts the number 4, and then your answer is in the 'hundreds of thousands' etc.

## Exercise 2: Implement a DNN to recognize handwritten digits
[week2](week2)

In the course you learned how to do classificaiton using Fashion MNIST, a data set containing items of clothing. There's another, similar dataset called MNIST which has items of handwriting -- the digits 0 through 9.

Write an MNIST classifier that trains to 99% accuracy or above, and does it without a fixed number of epochs -- i.e. you should stop training once you reach that level of accuracy.

Some notes:

    It should succeed in less than 10 epochs, so it is okay to change epochs= to 10, but nothing larger
    When it reaches 99% or greater it should print out the string "Reached 99% accuracy so cancelling training!"
    If you add any additional variables, make sure you use the same names as the ones used in the class

## Exercise 3: Improving DNN Performance using Convolutions
[week3](week3)

In the videos you looked at how you would improve Fashion MNIST using Convolutions. For your exercise see if you can improve MNIST to 99.8% accuracy or more using only a single convolutional layer and a single MaxPooling 2D. You should stop training once the accuracy goes above this amount. It should happen in less than 20 epochs, so it's ok to hard code the number of epochs for training, but your training must end once it hits the above metric. If it doesn't, then you'll need to redesign your layers.

When 99.8% accuracy has been hit, you should print out the string "Reached 99.8% accuracy so cancelling training!"

## Exercise 4: Handling Complex Images
[week4](week4)

use the provided code with a link to a happy or sad dataset which contains 80 images, 40 happy and 40 sad. Create a convolutional neural network that trains to 100% accuracy on these images, which cancels training upon hitting training accuracy of >.999