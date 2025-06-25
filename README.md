# Semantic Segmentation of Urban Scenes

This project applies semantic segmentation techniques to urban scene images using two deep learning models: **U-Net** and **DeepLabV3+**. Each pixel in an image is classified into semantic categories like road, building, vegetation, sky, etc.

## Models

- **U-Net**: Encoder-decoder architecture with skip connections for precise localization.
- **DeepLabV3+**: Uses atrous convolutions and ASPP to capture multi-scale context.

## Dataset

The dataset includes paired images and masks representing different semantic classes. Images are resized to 128×128 for training efficiency.

## Workflow

1. Data preprocessing and augmentation
2. Training and validation of U-Net and DeepLabV3+
3. Evaluation using pixel accuracy and mIoU
4. Visualization of segmentation results

## Requirements

- Python 3.x
- TensorFlow / Keras
- NumPy, Matplotlib, scikit-learn

## Usage

Open the notebook `Semantic_segmentation_of_urban_scenes.ipynb` and run it step by step.
