# Food-Vision-Big
It is an end-to-end multi-class image classification model that is based on the concepts of deep learning and Food(image) recognition. For this project I am using EfficientNet B0 feature extraction model , which takes in data of mixed precision. This will be used to predict on the images from 'food101' which is imported from TensorFlow datasets.

## What we're going to cover (broadly):
- Using TensorFlow Datasets to download and explore data (all of Food101)
- Creating a preprocessing function for our data
- Batching & preparing datasets for modelling (making our datasets run fast)
- Creating modelling callbacks
- Setting up mixed precision training (for faster model training)
- Building and training a feature extraction model
- Fine-tuning the feature extraction model to beat the DeepFood paper
- Evaluating the model results by making and plotting predictions
