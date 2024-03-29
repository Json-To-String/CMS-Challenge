# CMS-Challenge
My attempts at the CMS challenge tasks for the GSoC2024

Descriptions taken from here: https://docs.google.com/document/d/1QuG0Ho3pWsJGMx0fG969aBNfgPg-cDxU9w33ZuDEBng/edit

## Common Task 1. Electron/photon classification

Datasets:
https://cernbox.cern.ch/index.php/s/AtBT8y4MiQYFcgc (photons)
https://cernbox.cern.ch/index.php/s/FbXw3V4XNyYB3oA (electrons)

Description: 32x32 matrices with two channels: hit energy and time for two types of
particles, electrons and photons, hitting the detector.

Please use a Resnet-15 (you are free to play around with the architecture) like model, to achieve the highest possible
classification score on this image dataset. Please provide a Jupyter notebook that shows your solution along with the model weights. Preferably only use PyTorch or Keras in your solutions.

Please train your model on 80% of the data and evaluate on the remaining 20%. Please make sure not to overfit on the test dataset - it will be checked with an independent sample.

## Common Task 2.  Deep Learning based Quark-Gluon Classification


Datasets: https://cernbox.cern.ch/s/oolDBdQegsITFcv


Description 125x125 matrices in three-channel images for two classes of particles, quarks and gluons, impinging on a calorimeter.

Please build 2 models: a VGG with 12 layers (you can reduce the weights in the FC layers to speed up the training and play around with the general architecture) and another deep learning architecture of your choice to achieve the highest possible classification on this dataset. Please provide a Jupyter notebook that shows your solution along with the model weights. 

Please train your model on 80% of the data and evaluate on the remaining 20%. Please make sure not to overfit on the test dataset - it will be checked with an independent sample.



