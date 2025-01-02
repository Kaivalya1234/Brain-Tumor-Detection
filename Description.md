# Abstract
Early detection of brain tumors significantly enhances treatment efficacy and patient outcomes. In this study, we propose an efficient Trilayer architecture integrating InceptionV3, DeepLabV3+, and Convolutional Neural Networks (CNNs) for enhanced brain tumor segmentation and classification using magnetic resonance imaging (MRI) data. The proposed architecture first employs InceptionV3 to extract multi-scale features, followed by DeepLabV3+ for precise tumor segmentation, and finally, a CNN for classification. Through transfer learning and iterative training, the model achieved impressive classification accuracy of 99.25% on the Brain Tumor MRI dataset, outperforming existing methods. This study demonstrates that our Trilayer approach not only improves diagnostic accuracy but also supports clinical decision-making by providing detailed tumor segmentation. We emphasize the importance of open-sourcing our algorithm and dataset to facilitate reproducibility and future research advancements in this critical area.

# Keywords
Brain tumor segmentation, MRI images, DeepLabV3+, InceptionV3, CNN, Brain Tumor dataset, evaluation parameters, performance metrics, tumors.

# About Dataset
This dataset is a combination of the following three datasets :
figshare
SARTAJ dataset
Br35H

This dataset contains 7023 images of human brain MRI images which are classified into 4 classes: glioma - meningioma - no tumor and pituitary.

# Proposed Algorithm
The Trilayer model employs a three-step approach to brain tumor segmentation and classification:

1. Feature Extraction with InceptionV3:
   InceptionV3, a deep convolutional neural network with 269 layers, extracts multi-scale features from MRI images. This stage enhances the ability to detect small and complex patterns in the data.

2. Tumor Segmentation with DeepLabV3+:
   DeepLabV3+ performs semantic segmentation, isolating the tumor from healthy brain tissue. The segmentation process leverages atrous convolution and spatial pyramid pooling to achieve high-resolution feature 
   maps.

3. Classification with CNN:
   The segmented tumor is classified into glioma, meningioma, pituitary, or no tumor using a lightweight CNN. This final layer ensures efficient classification based on the segmented 
   regions.


# Results and Performance
The proposed Trilayer model achieved 99.25% classification accuracy, surpassing state-of-the-art methods. Performance metrics, including precision, recall, F1-score, and IoU (Intersection over Union), highlight significant improvements in segmentation and classification accuracy.


# Reproducibility
To ensure reproducibility, the code and dataset are made publicly available. A comprehensive usage guide and detailed documentation, including step-by-step instructions for data preprocessing, model training, and evaluation, are provided.


# Dependencies and Requirements
Python 3.8 or higher

TensorFlow 2.6+

Keras 2.8+

NumPy

OpenCV

Matplotlib

Scikit-learn

CUDA Toolkit (for GPU acceleration)



# To install dependencies, run
pip install tensorflow keras numpy opencv-python matplotlib scikit-learn nibabel 



# Server and Hardware Requirements

GPU: NVIDIA RTX 3080 or higher (for optimal performance)

CPU: Intel i7 or AMD Ryzen 7 (or equivalent)

RAM: 32 GB or more

Storage: Minimum 500 GB SSD (for faster data processing)

Operating System: Linux (Ubuntu 20.04+ recommended) or Windows 10/11

Server Environment: NVIDIA CUDA drivers and cuDNN installed for GPU acceleration



# Dataset
[Brain Tumor Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)
