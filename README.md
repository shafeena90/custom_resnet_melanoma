

# Custom ResNet for Melanoma Detection

This repository contains a custom implementation of a ResNet-50 v2 model tailored for melanoma detection. The project involves modifying the standard ResNet architecture to incorporate an additional custom layer to improve performance for melanoma image classification.

## Overview

Melanoma is a serious form of skin cancer that can be life-threatening if not detected early. Deep learning models, particularly Convolutional Neural Networks (CNNs), have shown promise in automating the detection process. This project leverages a custom ResNet-50 v2 architecture, fine-tuned to handle melanoma images.

## Key Features

* **Custom ResNet-50 v2**: The standard ResNet-50 v2 model is adapted with an additional custom layer to better capture melanoma features.
* **Flexible Training**: Configurable training parameters including learning rate, batch size, and more.
* **Data Preprocessing**: Pipelines for image augmentation and normalization to improve model generalization.
* **Evaluation**: Evaluation metrics such as accuracy, precision, recall, and F1-score.

## Dataset

The project uses the **HAM10000** dataset, which consists of 10,000 dermatoscopic images of common pigmented skin lesions. You can download it from the [ISIC Challenge 2018 Data Archive](https://challenge.isic-archive.com/data/#2018).

## Cloning the Repository

To get started, simply clone the repository:

```bash
git clone https://github.com/shafeena90/custom_resnet_melanoma.git
cd custom_resnet_melanoma
```

