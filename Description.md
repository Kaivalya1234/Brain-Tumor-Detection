# Abstract
Early detection of brain tumors significantly enhances treatment efficacy and patient outcomes. In this study, we propose an efficient Trilayer architecture integrating InceptionV3, DeepLabV3+, and Convolutional Neural Networks (CNNs) for enhanced brain tumor segmentation and classification using magnetic resonance imaging (MRI) data. The proposed architecture first employs InceptionV3 to extract multi-scale features, followed by DeepLabV3+ for precise tumor segmentation, and finally, a CNN for classification. Through transfer learning and iterative training, the model achieved impressive classification accuracy of 99.25% on the Brain Tumor MRI dataset, outperforming existing methods. This study demonstrates that our Trilayer approach not only improves diagnostic accuracy but also supports clinical decision-making by providing detailed tumor segmentation. We emphasize the importance of open-sourcing our algorithm and dataset to facilitate reproducibility and future research advancements in this critical area.

# Keywords
Brain tumor segmentation, MRI images, DeepLabV3+, InceptionV3, CNN, BraTS-2015 dataset, evaluation parameters, performance metrics, tumors.

# About Dataset
This dataset is a combination of the following three datasets :
figshare
SARTAJ dataset
Br35H

This dataset contains 7023 images of human brain MRI images which are classified into 4 classes: glioma - meningioma - no tumor and pituitary.

# Proposed Algorithm
	The following exploration introduces a Trilayer model approach which utilizes an early level abstraction better to identify and categorize mind malignancy by recognizing tumors in output images from the Brain Tumor dataset. The proposed method has the potential of outperforming novel methods by integrating the best part of each DeepLabV3+ and InceptionV3, which drastically improves tumours detection and classification.
	Demonstrating the accuracy of brain tumour segmentation over existing models using stacking model with DeepLabV3+ for image segmentation of input scanned images from BraTS-2015 dataset,InceptionV3 for feature extraction and CNN for classification. We show that the proposed method outperforms existing models based on evaluation measures from the chosen dataset.
	The Probability Density Function eliminates the memory issues that occur with the hybrid DeepLabV3+, InceptionV3 and CNN architecture
	DeepLabV3+ arch tecure for image segmentation of input images to detect tumour either it is benevolented or malignant, using InceptionV3 (269 layers sinks deep CNN) architecture for feature extraction and classifying either positive Class based on contour points under Gantry totally methodologically classified with comparison against various methods related to diseased -- cancer detection field.
