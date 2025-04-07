# Plant-Disease-Detection

A deep learning-based image classification model to detect plant leaf diseases using transfer learning (ResNet18) on the PlantVillage dataset.

## Project Overview

Plant diseases can significantly impact crop production. This project uses a ResNet18 model (pretrained on ImageNet) fine-tuned on the **PlantVillage** dataset to identify **38 different plant diseases and healthy leaves**.

## Dataset

- 📥 Source: [PlantVillage Dataset on Kaggle](https://www.kaggle.com/datasets/emmarex/plantdisease)
- 📊 Contains over **50,000 labeled images** of plant leaves (both healthy and diseased)


## Model Architecture

- 🔸 **ResNet18** pretrained on ImageNet
- 🔸 Final layer replaced with `nn.Linear` to match 38 output classes
- 🔸 Loss Function: CrossEntropyLoss
- 🔸 Optimizer: Adam
- 🔸 Accuracy Achieved: **96% on validation set**
