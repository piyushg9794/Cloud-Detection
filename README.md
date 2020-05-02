# Cloud-Detection
Applying concept of (Res-net) + (U-net++) for cloud detection

#Outline of project

1) reading images names from csv file
2) Reading images and then mask of corresponding images
3) Image augmentation & processing
4) Batch generation for training, validation & testing
5) Neural Network building
6) Selecting optimizers and losses
7) Training & validation of neural network
8) Testing on test image dataset

#Dataset description

- Using dataset of LANDSAT-8 satellite known as 38-cloud dataset.
- This dataset consist of 18 images with 8400 patches for training.
- 20 images with 9201 patches are used for testing.
- Each patch of image has 4 channels – red, green, blue & nearly infrared.

#Model Features

- 36M parameters
- Model image is available as model img file
- furthur expanded image of model is also available as model img expanded file
- keras generated graph is also available as model file

![](https://github.com/piyushg9794/Cloud-Detection/blob/master/Model%20img.jpg)
![](https://github.com/piyushg9794/Cloud-Detection/blob/master/model%20img%20expanded.jpg)
