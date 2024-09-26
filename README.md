# Jute Pest Identification: A Deep Learning Approach
## Overview
This repository contains the source code and resources for a deep learning project focused on classifying jute pests into 17 distinct categories. The project aims to enhance pest management in jute cultivation by automating the identification of pest species using deep learning models.

## Project Description
The study utilizes several deep learning architectures, including Convolutional Neural Networks (CNNs), pre-trained models like DenseNet and VGG16, and hybrid models combining ResNet50 with Random Forest and Vision Transformer (ViT). The models were evaluated for their accuracy, computational efficiency, and overall effectiveness in classifying jute pests from image data.

## Key Models:
- **CNN:** A custom-built model designed specifically for pest classification.
- **DenseNet121:** Fine-tuned for 17 classes to leverage its dense connectivity and efficient feature propagation.
- **VGG16:** Achieved the highest test accuracy of 97.89% through transfer learning.
- **ResNet50-Random Forest Hybrid:** Combines deep feature extraction with traditional machine learning, optimizing computational efficiency.
- **ResNet-ViT Hybrid:** Integrates convolutional and self-attention mechanisms for robust performance.
## Dataset
The dataset is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/920/jute+pest+dataset) and consists of images categorized into 17 different jute pest species. The dataset is divided into training, validation, and test sets to ensure robust model evaluation.

## Methodology
- **Data Preprocessing:** Includes resizing, normalization, and augmentation techniques to enhance model robustness.
- **Training Setup:** Models were trained using the Adam optimizer and cross-entropy loss, with careful consideration of learning rates and batch sizes.
- **Evaluation Metrics:** Accuracy, precision, recall, F1-score, and computational efficiency were used to evaluate model performance.
## Results
- **VGG16:** Highest test accuracy of 97.89%.
- **ResNet-ViT Hybrid:** Strong performance with 97.36% accuracy, leveraging self-attention for better feature extraction.
- **ResNet50-Random Forest Hybrid:** Achieved 96.00% accuracy with the least computational time, making it ideal for deployment in resource-constrained environments.

## Acknowledgments
The dataset used in this project is provided by the UCI Machine Learning Repository.
Special thanks to Texas State University for support and resources.
