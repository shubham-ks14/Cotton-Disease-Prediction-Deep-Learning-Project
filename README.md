# Cotton-Disease-Prediction-Deep-Learning-Project
Deep Learning technique for image-based cotton plant disease prediction

## Overview
* Demonstrating a method to use deep learning technique to classify  images of cotton plant and associated disease by training the model with around 2000 images.
* The classification was done on 4 different class of images available as follows:
1. Diseased cotton leaf
2. Diseased cotton plant
3. Fresh cotton leaf
4. Fresh cotton plant

## Methods
### Dataset 
* 2000 images for train data and 40 images for test data were used to reduce the computational cost
* A sample of train and test data is provided in sample folder.
* Each of train and test contains images for above mentioned 4 classes.
* The default resizing of images of 224 x 224 pixels is used.
### Approach
* For the classification Deep CNN method with Transfer learning training mechanism is applied
* ResNet50 deep learning architecture is used.

### Platform
* Google Colaboratory IDE with TPU hosted runtime server to allow fast computaion.
* The dataset needs to be saved in google drive first and then load to Colab notebooks
* Training time is close to 2 hours.

### Results
* Highest accuracy of 0.7668 for training set and 0.85 for test set is obtained
* Final predicion of one image from class-3 .ie.Fresh Cotton leaf was conducted using the model and the prediction is accurate
