# Gemstone Classification using MobileNetV2 🧠💎

This project is part of a group assignment for the SE4050 Deep Learning module at SLIIT. The objective is to classify Sri Lankan gemstones into 87 distinct classes using deep learning techniques.

## 📌 My Contribution

I implemented the **MobileNetV2** model for the gemstone image classification task. MobileNetV2 is a lightweight and efficient CNN architecture suitable for resource-constrained environments, making it ideal for mobile deployment.

## 🧠 Model Overview

- **Model Used**: MobileNetV2 (pre-trained on ImageNet, fine-tuned on our dataset)
- **Input Image Size**: 224x224 pixels
- **Optimizer**: Adam
- **Loss Function**: Categorical Crossentropy
- **Data Augmentation**: Rotation, zoom, horizontal/vertical flip
- **Test Accuracy Achieved**: **57.39%**

## 📁 Dataset

- **Total Images**: ~3200
- **Classes**: 87 gemstone types
- **Source**: Publicly available (Kaggle)
- **Split**: 2800 training images / 400 testing images

> Note: Dataset not included in this repo due to size limitations.

## 📊 Why MobileNetV2?

MobileNetV2 is designed for performance and speed:
- Low computational cost
- Depthwise separable convolutions
- Ideal for mobile and embedded applications

## 🚀 How to Run

1. Clone the repo:
```bash
git clone https://github.com/Viraj494/Gem-Stone-Classification.git
cd Gem-Stone-Classification
