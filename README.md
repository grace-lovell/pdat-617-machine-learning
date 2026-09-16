# Plant Disease Detection

A computer vision project developed for PDAT 615 using PyTorch to classify plant images into nine different plant categories.

## Dataset

Plant Disease Detection Dataset from Kaggle:
https://www.kaggle.com/datasets/mgmitesh/plant-disease-detection-dataset

The dataset contains images of Apple, Cherry, Corn, Grape, Peach, Pepper, Potato, Strawberry, and Tomato plants.

## Model

This project uses a modified **LeNet-5** architecture. Batch Normalization was added after each convolutional layer, and the first convolutional layer was modified to accept RGB images instead of grayscale images.

Images were resized to 28×28 pixels and normalized before training.

## Results

The model was trained for 10 epochs using the Adam optimizer and Cross Entropy Loss.

**Test Accuracy: 91.40%**

## Tools

* Python
* PyTorch
* Torchvision
* NumPy
* Matplotlib
