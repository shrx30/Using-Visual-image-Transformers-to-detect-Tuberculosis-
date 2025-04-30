Vision Transformer (ViT) for Tuberculosis Classification
Overview
This project involves training a Vision Transformer (ViT) model to classify tuberculosis (TB) from chest X-ray images. The dataset consists of segmented lung images categorized into TB-positive and TB-negative classes. A pre-trained segmentation model is used to segment the lung regions from the chest X-ray images, and the segmented images are then passed into a ViT model for classification.

Key Features
ViT Model: Utilizes a Vision Transformer model for image classification.

Image Segmentation: Segments the lung regions in chest X-rays using a pre-trained segmentation model.

Binary Classification: Classifies chest X-ray images into TB-positive or TB-negative classes.

Metrics: The model is evaluated using Sensitivity and Specificity metrics for better performance analysis in medical classification tasks.

  This project presents a two-stage deep learning pipeline for detecting tuberculosis (TB) from chest X-ray images:

Stage 1 – Lung Segmentation
A custom segmentation model  isolates lung regions from the chest X-rays.

Stage 2 – Classification with ViT (Vision Transformer)
The segmented lung images are passed to a Vision Transformer model built using PyTorch + TIMM to classify images into:

TB Positive

TB Negative
