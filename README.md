# CIFAR10 Classification Model
A classification model implemented using Deep Neural Networks

# Algorithms Used
## Convolutional neural network
Popularly used for Image Processing, CNN's are a series of convolutional, nonlinear, pooling (downsampling), and fully connected layers that produces an output. This output can be a single class or a probability of classes that best describes the image.
Convolutions use a kernel matrix to scan a given image and apply a filter to obtain a certain effect and still maintains the spatial relationship between pixels.
 
## Confusion Matrix
* A confusion matrix is used to describe the performance of a classiﬁcation model: 
* True positives (TP): Classiﬁer predicted TRUE and correct class was TRUE. 
* True negatives (TN): Classifier predicted FALSE and correct class was FALSE . 
* False positives (FP): Classiﬁer predicted TRUE but correct class was FALSE. 
* False negatives (FN): classiﬁer predicted FALSE but correct class was TRUE.


# Implementation
##Dataset
CIFAR-10 is a dataset that consists of several images divided into the following 10 classes: 
* Airplanes
* Cars
* Bird
* Cats
* Deer
* Dogs
* Frogs
* Horses 
* Ships
* Trucks
It consists of 60,000 images with low resolution (32x32).
After the model is trained, it classifies the testing dataset to one of the category as shown above.
