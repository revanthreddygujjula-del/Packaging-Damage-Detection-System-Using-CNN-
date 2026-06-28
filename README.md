# Packaging Damage Detection System Using CNN and MobileNetV2

## Project Overview

This project develops an automated packaging damage detection system using Deep Learning techniques. The system classifies package images into two categories:

* Damaged
* Undamaged

The project compares the performance of a Custom CNN model and MobileNetV2 Transfer Learning model.

## Dataset

* Total Images: 8457
* Damaged Images: 6462
* Undamaged Images: 1995

## Technologies Used

* Python
* TensorFlow
* Keras
* CNN
* MobileNetV2
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

## Models Implemented

### 1. Custom CNN

* Convolution Layers
* Max Pooling
* Dense Layers
* Dropout Regularization

### 2. MobileNetV2

* Transfer Learning
* Pretrained ImageNet Weights
* Global Average Pooling

## Results

| Model       | Accuracy |
| ----------- | -------- |
| CNN         | 85.15%   |
| MobileNetV2 | 88.18%   |

MobileNetV2 achieved the highest performance and outperformed the custom CNN model.

## Project Structure

project_outputs/

* Accuracy Graphs
* Loss Graphs
* Confusion Matrices
* Classification Reports
* Dataset Tables

models/

* custom_cnn_package_damage.h5
* mobilenetv2_package_damage.h5

## Conclusion

The system successfully detects packaging damage using image classification techniques. MobileNetV2 achieved superior performance and demonstrates the effectiveness of transfer learning for industrial inspection tasks.

