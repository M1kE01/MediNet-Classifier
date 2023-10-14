# MediNet-Classifier

MediNet-Classifier is a deep learning project focused on medical image classification using neural networks.

## Introduction

This project primarily employs the ResNet50 architecture and evaluates its effectiveness on a specific medical dataset. Fine-tuning and other modifications have been implemented to adapt the model to the specific dataset characteristics.

## Results

### Basic Model:
- **Validation Accuracy:** peaks 64.15% at epoch 2, then decreasing.

### ResNet50 Pretrained Model:
- **Validation Accuracy:** Starts at 35.85% in epoch 1 and achieves a maximum of 73.58% by epoch 3.

Despite various tweaks, both models yielded similar performances. The consistent F1 score across epochs and models indicates potential data-related challenges, such as quality or imbalance.

## Key Features

- Uses **ResNet50** as the base model with options to fine-tune.
- Implements **Learning Rate Scheduling** and **Weight Decay** for optimization.
- Employs **Early Stopping** to halt training when validation accuracy plateaus.
- Incorporates **Class Weights** to tackle class imbalance in the dataset.

## Recommendations

Future improvements could include:
- Exploring different data augmentation methods.
- Testing alternative model architectures.
- Seeking insights from medical professionals to ensure clinical relevance.

## Feedback

Feel free to open an issue for any bugs, enhancements, or discussions. Contributions are welcome!

