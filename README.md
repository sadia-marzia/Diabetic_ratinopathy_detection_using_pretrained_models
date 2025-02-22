# Diabetic_ratinopathy_detection_using_pretrained_models
## Project Overview
This project focuses on the automated detection of Diabetic Retinopathy (DR) using deep learning techniques and pre-trained models. By leveraging transfer learning and efficient image preprocessing, this system accurately classifies retinal fundus images into five stages of DR severity.
## Dataset
Name: Diabetic Retinopathy 224x224 (2019 Data)  
Source: https://www.kaggle.com/datasets/sovitrath/diabetic-retinopathy-224x224-2019-data
Total Images: 3662 fundus images
Class Distribution:
No DR: 1805 images
Mild DR: 370 images
Moderate DR: 999 images
Severe DR: 193 images
Proliferative DR: 295 images

## Results
### Model	Accuracy (%)
MobileNetV2	81.60
EfficientNet-B0	84.17 ✅
DenseNet121	82.95
EfficientNet-B0 achieved the best classification accuracy (84.17%) with balanced efficiency and high accuracy.
