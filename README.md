# ELEC5690_Assignment1
The solutions are in Python notebook format since google colab was used, you can also create a virtual environment and install the libraries at the start of each python notebook to run it outside of google colab.

## Problem 1: Skin Lesion Image Classification
The dataset is the ISIC2018 task 3 (https://challenge.isic-archive.com/data/#2018):, including 10,015 training images, 193 validation images, and 1,512 test images with seven diseases.

For my solution, I used the ResNet50 model in 2 training configurations:

1. Using cross-entropy loss
2. Using cross-entropy + focal loss to address the class imbalance 

## Problem 2: 3D medical image segmentation
The dataset is the The Atrial Segmentation Challenge datasext, including 14 training and 20 test 3D images.

For my solution, I use the 3D Unet model in 3 different training configurations:

1. Using binary cross entropy loss
2. Using dice loss
3. Using dice loss + data augmentations

## Additional Information
Further details and the exact code can be found here: 
- Problem 1: ELEC5690_Assignment1_Problem_1.ipynb
- Problem 2: ELEC5690_Assignment1_Problem_2.ipynb

The modules in each notebook are labelled according to what they are doing so it is straightforward to follow along.

The report which includes metrics and example plots can be found here: 
- report.pdf