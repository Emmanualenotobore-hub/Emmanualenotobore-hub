# Brain Tumor Segmentation using Hybrid CNN-Transformer Models

## Overview
This project focuses on developing an optimized deep learning model for **brain tumor segmentation** from MRI scans. The study aims to improve tumor detection accuracy by integrating **Transformer-based attention mechanisms** with **Convolutional Neural Networks (CNNs)** in a hybrid architecture. The hybrid model captures both local and global image features, leading to more accurate and smoother segmentations.

---

## Features
- Hybrid **CNN-Transformer** architecture for enhanced segmentation performance.
- Preprocessing pipeline including **intensity normalization**, **binary mask correction**, and **data augmentation**.
- **Composite loss function** combining Dice loss and Binary Cross-Entropy loss.
- Training optimizations: **early stopping** and **learning rate scheduling**.
- Evaluation using metrics: **Dice coefficient**, **sensitivity**, **specificity**, and **AUC**.
- Visual outputs of segmented tumors for qualitative assessment.

---

## Results
The hybrid model significantly outperformed the baseline CNN model:

| Metric       | Baseline CNN | Hybrid CNN-Transformer |
|------------- |------------- |-----------------------|
| Dice Score   | 0.559        | 0.724                 |
| Sensitivity  | 0.518        | 0.729                 |
| Specificity  | 0.947        | 0.955                 |

**Example Segmentation Output:**  
![Sample Segmentation](results/plots/sample.png)

The results demonstrate that adding Transformer elements improves the model’s ability to capture global context, producing smoother and more comprehensive tumor segmentations.

---

## Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/Emmanualenotobore-hub/Brain-Tumor-Segmentation.git
cd Brain-Tumor-Segmentation
pip install -r requirements.txt
