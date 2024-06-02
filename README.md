# Traffic Sign Detection

Data : https://www.kaggle.com/datasets/ahemateja19bec1025/traffic-sign-dataset-classification


Pre-trained Models used: 
- VGG16 
- Xception
- ResNet50

## Data Preparation: 

1. Loaded the traffic sign images from the directory structure.
2. Used ImageDataGenerator to rescale the images and split the data into training and validation sets.

## VGG16 Model: 

1. Loaded the pre-trained VGG16 model without the top layer.
2. Added a custom dense layer for classification.
3. Compiled and trained the model.
4. Saved the model and evaluated its performance, achieving high accuracy.

## Xception Model: 

1. Loaded the pre-trained Xception model.
2. Added custom layers for classification.
3. Compiled and trained the model with early stopping.
4. Evaluated the model, achieving reasonable accuracy but lower than VGG16.

- ## ResNet50 Model: 

1. Loaded the pre-trained ResNet50 model.
2. Added custom layers for classification.
3. Compiled the model and trained the model.
4. Evaluated the model, achieving reasonable accuracy but lower than VGG16.
