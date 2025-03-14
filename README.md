# CIFAR-10 ResNet Image Classification

Team Members: Raj Trikha, Saavy Singh, Nikita Gupta

In this project, we have implemented a modified ResNet architecture designed specifically for image classification on the CIFAR-10 dataset. The primary objective was to achieve high accuracy while keeping the model complexity within a constraint of **5 million parameters**.

## 📝 Project Description

This project was developed as part of the **Deep Learning (CS 6953)** course at **New York University (NYU)**. The goal was to train and fine-tune a Residual Neural Network (ResNet) to classify CIFAR-10 images efficiently while keeping the model size under 5 million parameters.

## 📊 Project Achievements
- Achieved **96.54% accuracy** on the validation dataset.
- Achieved **88.091% accuracy** on the Kaggle competition test dataset.
- Secured **9th place** out of **over 150 participating teams**.

## 🗃️ Data

The dataset used is CIFAR-10, which includes 60,000 color images (32x32 pixels) divided into 10 distinct classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

- **Training set**: 50,000 images
- **Test set**: 10,000 images

## 📁 Project Structure
```
cifar10-resnet/
├── model/
│   └── cifar10-resnet.ipynb
└── README.md

```

## 🚀 Running the Project

### Clone Repository
```bash
git clone https://github.com/saavysingh/cifar10-resnet.git
```

### Install Dependencies
```bash
pip install torch torchvision matplotlib numpy
```

### Run Notebook
```bash
jupyter notebook cifar10-resnet.ipynb
```

## 📌 Project Constraints
- **Model Constraint:** Maximum of 5 million parameters

---

Feel free to explore the notebook to gain deeper insights into the model architecture, training strategies, visualizations, and evaluation metrics.


