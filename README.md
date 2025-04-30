Vision Transformer (ViT) for Tuberculosis Classification
Overview
This project involves training a Vision Transformer (ViT) model to classify tuberculosis (TB) from chest X-ray images. The dataset consists of segmented lung images categorized into TB-positive and TB-negative classes. A pre-trained segmentation model is used to segment the lung regions from the chest X-ray images, and the segmented images are then passed into a ViT model for classification.

Key Features
ViT Model: Utilizes a Vision Transformer model for image classification.

Image Segmentation: Segments the lung regions in chest X-rays using a pre-trained segmentation model.

Binary Classification: Classifies chest X-ray images into TB-positive or TB-negative classes.

Metrics: The model is evaluated using Sensitivity and Specificity metrics for better performance analysis in medical classification tasks.

Dataset
The dataset used for this project is named segmented-lung-dataset-for-tb-classification, which consists of two primary categories:

tb_positive

tb_negative

Each category contains images of lung X-rays that have already been segmented to isolate the lung areas. The images are used for training and evaluating the ViT model.
