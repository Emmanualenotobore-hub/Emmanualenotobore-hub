# Brain Tumor Segmentation using Deep Learning

🎓 Master's Dissertation Project | Data Science

## Overview
This project is based on my Master's dissertation titled
**"Brain Tumor Diagnosis using Optimized Segmentation Techniques"**
completed under the supervision of Dr. Shaheen Khatoon.

The objective is to automatically segment brain tumors from MRI scans
using deep learning models, including CNN and Transformer-based architectures.

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
