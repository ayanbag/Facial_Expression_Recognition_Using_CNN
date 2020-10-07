# Facial Expression Recognition using CNN Algorithm

This model can detect facial expressions of a human being and can predtict the emotional state of the person in realtime. Our model is compromised of four convolutional layers, 
four max-pooling layers, and two connected layers. The convolutional layers with the kernel size of 3x3 are stacked together which are followed by maxpooling layer with kernel
size of 2x2. Like the convolutional layer, the RELU activation function is applied in the hidden layers of our network. Softmax has been used as an activation function of the 
output layer. Adam is used as our model optimizer with a learning rate of 0.0005.And as loss function, Categorical Crossentropy is used. I have trained this model with 28,708 
training images and tested on 7178 test images. After 500 epochs, it reached a training accuracy of 84%.
