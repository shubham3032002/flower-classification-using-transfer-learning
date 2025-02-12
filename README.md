# flower-classification-using-transfer-learning

## Flower Classification with Transfer Learning 
🌼🌻🌹🌷🌺
This project uses transfer learning with TensorFlow and EfficientNetB0 to classify flowers into five categories: daisy, dandelion, rose, sunflower, and tulip. The model leverages pre-trained ImageNet weights and fine-tunes the model for flower classification.

## Table of Contents
Project Overview
Dataset
Installation
Usage
Model Training and Fine-Tuning
Prediction
Results
Future Work
License

## Project Overview
The goal of this project is to classify flower images into one of five categories using a deep learning model. Transfer learning is employed for faster training and improved accuracy by building upon the pre-trained EfficientNetB0 architecture.

## Dataset
The dataset consists of images organized into two folders: train and test. The train folder is further split to create a validation set during training. Images should be sorted into the following subfolders for each category:

daisy
dandelion
rose
sunflower
tulip

## Model Training and Fine-Tuning
Transfer Learning: The base EfficientNetB0 model is frozen and used to extract features.
Custom Layers: Fully connected layers are added to adapt the model to flower classification.
Fine-Tuning: Some layers of the base model are unfrozen, and the model is trained further with a lower learning rate for better accuracy.

## Results
The model achieved the following accuracy:

Validation Accuracy: 67.09%% (update after training)
![image](https://github.com/user-attachments/assets/79cd83ba-8722-4dbf-8043-d75119887631)

![image](https://github.com/user-attachments/assets/21bfcdaf-ec33-4e25-80c6-e1a7b6da6c3e)
## License
This project is licensed under the MIT License. See the LICENSE file for details.


