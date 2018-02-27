[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"

## Project Overview

In this project I utilized Convolutional Neural Networks (CNNs), and transfer learning pipelines to process real-world, user-supplied images.  In this case, I built an image classify that, given an image of a dog, the model will identify an estimate of the breed.  If supplied an image of a human, the code will identify the resembling dog breed.  

![Sample Output][image1]

During this project we started by building our own CNNs from scratch - realizing how hard that is on small data sets.

I then utilized transfer learning from ImageNet pretrained models (VGG16 and InceptionV3). This used a pipeline to utilize its convolutional layers from those models, and added fully connected layers at the end to get a classification of which breed. Please see dog_app.ipynb for the complete project and process.
