# Classification-Model

This is a Classification Model created using the pre trained Resnet 18 Model from Pytorch Library.

The dataset used in this is custom dataset stored in own computer.

The Train data constits of 3726 images which are classified into 8 classes (categories)

Validation data consists of 160 images.

Here, the Validation is done using the unlabelled data which has images and a corresponding CSV File.

The Training file (Training.py) is used to train the model and can also be used for validation to find the valid accuracy with some changes

To Find the validation accuracy and the predictions of the images (as a CSV File) in validation dataset, Run the Evaluation.py with the saved model using Trainingpy


## Required packages : 

*Pytorch

*torchvision

*PIL

*natsort

*path
