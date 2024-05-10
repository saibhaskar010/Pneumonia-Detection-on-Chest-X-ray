# 🌟 Pneumonia Detection from Chest X-Rays with CNNs and Transfer Learning

Welcome to the Pneumonia Detection project repository! This project demonstrates the application of Convolutional Neural Networks (CNNs) and Transfer Learning to identify pneumonia from chest X-ray images.

## 🚀 Overview

This repository hosts a detailed Jupyter notebook that utilizes deep learning models to classify chest X-ray images into two categories: Normal and Pneumonia. Using TensorFlow and Keras, the project explores both custom-built CNN models and pre-trained models via Transfer Learning.

## 📖 Introduction

Pneumonia is a significant health problem, and rapid diagnosis can substantially affect treatment outcomes. The motivation behind this project is to leverage deep learning to assist and accelerate the decision-making process in medical diagnostics.

## 🗂 Dataset Preprocessing and Visualization

The dataset comprises chest X-ray images categorized into Normal and Pneumonia, sourced from publicly available medical image repositories. This project involves:
- Loading and resizing images
- Visualizing the distribution of classes
- Augmenting the data to improve model robustness

## 🤖 Model Training

### CNN from Scratch
- Constructed a CNN to learn features directly from the X-ray images.
- Implemented data augmentation to enhance model generalization.

### Transfer Learning
- Employed a pre-trained ResNet50 model, adapting it to our specific task.
- Fine-tuned and evaluated the model performance on separate training and validation sets.

## 🔍 Conclusion

The models were able to classify X-ray images with a high degree of accuracy, demonstrating the potential of deep learning in medical imaging tasks. Further improvements could involve more complex architectures or exploring other pre-trained models.

## 🛠 Installation

Clone the repository and install the required packages:

```bash
git clone https://github.com/yourusername/pneumonia-detection.git
cd pneumonia-detection
pip install -r requirements.txt
```
## 📋 How to Use
To run the notebook:
jupyter notebook pneumonia_detection.ipynb

## 📬 Contact
Sai Bhaskar Kumpatla - saibhaskar93@gmail.com

## 📄 License
This project is licensed under the MIT License - see the LICENSE.md file for details.
