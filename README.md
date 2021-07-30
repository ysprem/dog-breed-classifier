# Classify dog breeds from a user uploaded image
This repository contains code related to a CNN that can classify various dog breeds from an image. I created this as a part of the capstone project for Udacity Datascience Nanodegree. I had a lot of fun implementing this project. I created a detailed report here : https://premys.medium.com/building-a-dog-breed-classifier-using-a-cnn-1599ac0ece29 

# Installation
The code contained in this repository was written in Python and largely used the OpenCV and Keras libraries. Specifically the following Python packages were used: sklearn, keras, numpy, glob, random, cv2, matplotlib, tqdm, PIL and IPython.

# Running instructions
Run the dog_app.ipynb file to train and test the CNN. For certain modules, you need to use the lbpcascade_frontalface_improved.xml model framework from OpenCV which I have uploaded in the repository. You also need to download the VGG-19 model bottleneck features which can be found here : lbpcascade_frontalface_improved.xml

# Results summary
![Screen Shot 2021-07-29 at 11 01 53 PM](https://user-images.githubusercontent.com/10462415/127607976-a7fa8399-09a8-4c56-bc39-8033179d22bf.png)

The model performs fairly well in identifying broadly different dog breeds but struggles a little with very similar dog breeds. It has an accuracy of ~70% on the test data set.



