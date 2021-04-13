# Facial Expression Recognition using CNN Algorithm
This is a Tensorflow implementation of the  paper:<br/>


**Real Time Facial Expression Recognition using Convolution Neural Network Algorithm**<br/>
Ayan Bag <br/>


Paper Link : [pdf](https://www.ijraset.com/fileserve.php?FID=31485)

## Objective

The most expressive way human beings display emotions is through facial expressions. The task of detecting facial
expression of a human being via a computer is a very complex process due to its variability present across human faces
including color, expression, position, and orientation. The aim of this paper is to presents a Convolution Neural Network (CNN)
architecture for real-time facial expression recognition

## Model Overview
My model can detect the facial expressions of a human being and can predict the emotional state of the person in realtime. Our model is compromised of four convolutional layers, 
four max-pooling layers, and two connected layers. The convolutional layers with the kernel size of 3x3 are stacked together which are followed by maxpooling layer with kernel
size of 2x2. Like the convolutional layer, the RELU activation function is applied in the hidden layers of our network. Softmax has been used as an activation function of the 
output layer. Adam is used as our model optimizer with a learning rate of 0.0005.And as loss function, Categorical Crossentropy is used. I have trained this model with 28,708 
training images and tested on 7178 test images. After 500 epochs, it reached a training accuracy of 84%.


## Cite as
**Bibtex :**
```
@article{bagreal,
  title={Real Time Facial Expression Recognition using Convolution Neural Network Algorithm},
  author={Bag, Ayan}
}
```
