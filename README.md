# Breats-cancer-classification

## Abstract
A multilevel ensemble convolutional neural network model has been developed for the detection and classification of breast cancer, by analyzing a set of 400 histopathology images from the BACH ICIAR grand challenge dataset, which are segregated into 100 images of normal, in-situ, benign and invasive histopathology images each. Conventional models fail to perform well on histopathology images due to lack in contrast in the images and also the lack of availability of a lot of data. The multi-level stacking of VGG16 and ResNet50 trained on the famed “ImageNet” dataset is deep and yet computationally light due to the employment of transfer-learning. The usage of such robust models for training allows for consistent accuracies. The individual validation accuracies of the VGG16 and ResNet50 are 73.43% and 82.81%. However, the validation accuracy of the stacked ensemble model accounts to 89.06% which is much higher than the results provided by conventional Convolutional Neural Network (CNN) models with similar computation times. This allows for the automation and accurate detection of breast cancer from histopathology images which is an industry requirement.

### The provided code which uses an ensemble of VGG16 and ResNet50 has currently been able to provide the highest accuracy of 89.6% in Cancer histology image classification on the BACH dataset. This places the research amongst the top 5 accuracies in the world

## Requirements
1. Download the Dataset after applying to the BACH Grand challenge, after whgich, the dataset would be made available to you. Apply here--> https://iciar2018-challenge.grand-challenge.org/
2. Upload the dataset to your drive, and mount your drive to Colab.
3. Edit the path of the dataset now available on your drive.
4. Enable the TPU in Colab so as to make use of the tensor processing unit provided by Colab to reduce the training time of the ensemble model.  

