# Brain Tumor Segmentation using Deep Learning

🎓 Master's Dissertation Project | Data Science

## Overview

This project focuses **"Brain tumor classification using deep learning techniques"** in MATLAB. Two approaches are developed and compared: a custom Convolutional Neural Network (CNN) and a transfer learning model based on AlexNet. The goal is to classify brain MRI images into four categories—Glioma, Meningioma, Pituitary Tumor, and No Tumor—with high accuracy.

The Kaggle Brain Tumor MRI dataset is used, with data split into 70% training, 15% validation, and 15% testing. Preprocessing steps include image resizing, RGB conversion, data augmentation, and class distribution analysis to enhance model performance and reduce overfitting.

The custom CNN consists of 10 convolutional layers with batch normalization and ReLU activation, followed by pooling layers and a softmax classifier. Trained for 20 epochs using the Adam optimizer, the model achieved an accuracy of 96.02%, showing strong generalization across all tumor classes.

The transfer learning approach modifies AlexNet for four-class classification and uses augmented images resized to 227×227. Trained under similar conditions, this model achieved 94.20% accuracy, performing particularly well on the No Tumor and Glioma classes.

Comparative analysis using accuracy, precision, recall, and F1-score shows that the custom CNN outperforms AlexNet, demonstrating that well-designed task-specific models can be more effective than pretrained networks for medical imaging tasks.

## Problem Statement
Manual tumor segmentation is time-consuming and subjective.
This project explores optimized deep learning approaches to improve
accuracy and robustness in medical image segmentation.

## Models Used
- U-Net (Baseline)
- nnU-Net
- UNETR
- Hybrid CNN–Transformer model (Proposed)

## Dataset
BraTS (Brain Tumor Segmentation) dataset.  
Due to data usage restrictions, the dataset is not included.

## Methodology (High-Level)
- MRI preprocessing and normalization
- Data augmentation
- Model training and optimization
- Evaluation using Dice Score, IoU, and Hausdorff Distance

## Results
The proposed hybrid model achieved improved Dice scores compared
to baseline models, particularly for tumor core and enhancing regions.

Sample outputs and metrics are available in the `results/` folder.

## Tech Stack
- Python
- PyTorch
- MONAI
- NumPy, OpenCV
- Matplotlib

## Disclaimer
This project is shared for academic and portfolio purposes only.
