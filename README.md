# Fastai Face Mask Detection
![image](https://github.com/AmiraQadry/Real-time-Face-Mask-Detection/assets/106974489/b0f6e671-5ecc-414a-bd7e-4ea259187b00)

## Overview

This project uses the [Fastai library](https://github.com/fastai/fastai) for real-time face mask detection. 
It leverages the Fastai vision module, which simplifies the process of training deep learning models for image classification. The pre-trained ResNet50 model is used for the task of face mask detection.

## Requirements

- Python 
- Fastai
- pathlib

## Face Mask Detection Data set

[Face Mask Detection Data set](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset/data) consists of 7553 RGB images in 2 folders as with_mask and without_mask. 
Images are named as label with_mask and without_mask. Images of faces with mask are 3725 and images of faces without mask are 3828.

## Training

The model is trained in two stages:

- Stage 1: Training the Frozen Layers
- Stage 2: Fine-tuning Unfrozen Layers
