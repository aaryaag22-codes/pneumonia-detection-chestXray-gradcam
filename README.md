# Pneumonia Detection in Chest X-Rays using Deep Learning and Grad-CAM

## Overview

This project presents a deep learning-based approach for automated pneumonia detection from chest X-ray images. The system utilizes Convolutional Neural Networks (CNNs) and transfer learning architectures such as MobileNetV2, ResNet50, and DenseNet121 to classify chest X-rays as Normal or Pneumonia. To improve model transparency and interpretability, Grad-CAM (Gradient-weighted Class Activation Mapping) is used to highlight the image regions that contribute most to the model's predictions.

## Features

* Automated pneumonia classification from chest X-ray images
* Transfer learning using MobileNetV2, ResNet50, and DenseNet121
* Image preprocessing and normalization
* Data augmentation to improve generalization
* Grad-CAM visualizations for explainable AI
* Performance evaluation using Accuracy, Precision, Recall, and F1-Score
* Medical image classification with interpretable predictions

## Technologies Used

* Python
* TensorFlow
* Keras
* OpenCV (cv2)
* NumPy
* Matplotlib
* Seaborn
* Google Colab

## Dataset

The project uses the Chest X-Ray Images (Pneumonia) dataset obtained from Kaggle. The dataset contains labeled chest X-ray images categorized into two classes:

* Normal
* Pneumonia

The images were preprocessed, resized, normalized, and augmented before training.

## Methodology

1. Data preprocessing and normalization
2. Data augmentation (rotation, zooming, horizontal flipping)
3. Training a baseline CNN model
4. Applying transfer learning using MobileNetV2, ResNet50, and DenseNet121
5. Evaluating model performance using classification metrics
6. Generating Grad-CAM heatmaps to explain model predictions

## Results

* MobileNetV2 achieved a training accuracy of approximately 94.69%.
* Grad-CAM visualizations successfully highlighted clinically relevant lung regions influencing predictions.
* Transfer learning models improved classification performance and generalization compared to a baseline CNN model.

## Screenshots

### Grad-CAM Heatmap

<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/aa97c52e-9775-4d2a-921d-a883463df09b" />

<img width="462" height="469" alt="image" src="https://github.com/user-attachments/assets/023af3a2-ed89-4f2a-b79a-7b32e46cea98" />


📄 [Project Report](./Detection of Pneumonia in xray scans.pdf)

## Future Improvements

* Train on larger and more diverse datasets
* Explore advanced architectures such as EfficientNet
* Develop a web-based interface for real-time diagnosis
* Integrate with hospital information systems

## Team Members

* Aarya Agarwal
* Mahira Srivastava
* Pranshu Bhale
* Ishi Pandeya
* Nandini Taldar
* Varda Murarka

## Disclaimer

This project is intended for educational and research purposes only and should not be used as a substitute for professional medical diagnosis.
