# Image Recognition with PyTorch




**Project intuition and reasoning:**

This is my first run-in with PyTorch. I built a Convolutional Neural Network to predict what digit is being displayed in an image. The dataset used for this is PyTorch's built in MNIST dataset that has 70k images. 

This is what an image looks like, here is the number 9:

![alt text](https://github.com/georgybusov/Image-Recognition-with-PyTorch/blob/main/nine.jpg?raw=true)

**Project Overview**
- Find a way to load the data
- Create loaders
- Define layers
- Create a tensor to be passed into the model
- Perform first convolution/activation
- Run the first pooling layer
- Perform second convolution/activation
- Run the second pooling layer
- Flatten the data
- Create model
- Define loss function and optimizer
- Train the model
- Evaluate accuracy
- Check what images weren't correctly predicted

Here are some of the images that could not be predicted... probably the work of a doctor.

![alt text](https://github.com/georgybusov/Image-Recognition-with-PyTorch/blob/main/badnumbers.jpg?raw=true)

