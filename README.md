# Drone Detection with Faster R-CNN

## Features

- Faster R-CNN model with MobileNetV3-Large backbone for efficient drone detection
- Data augmentation pipeline using Albumentations
- Custom dataset class for COCO format annotations
- Training and evaluation scripts
- Inference on new images
- Model saving and loading functionality

## Model

The implementation uses a Faster R-CNN model with a MobileNetV3-Large backbone and Feature Pyramid Network (FPN). This architecture provides a good balance between accuracy and inference speed.

Key components:
- MobileNetV3-Large backbone pre-trained on ImageNet
- Feature Pyramid Network for multi-scale feature detection
- Region Proposal Network (RPN)
- ROI pooling and classification heads

## Results

The model achieves:
- High IoU scores for accurate localization
- Good detection performance across various lighting conditions and backgrounds
- Real-time inference capability
