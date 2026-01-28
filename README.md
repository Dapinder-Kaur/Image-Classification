
# Image Classification using CNN and Transfer Learning

## Project Overview
This project provides a deep learning solution designed to automate the detection and classification of wildlife species within remote sensing imagery. The primary objective is to support global conservation efforts by providing researchers with a tool for monitoring endangered animals in their natural habitats.

The model was built through iterative development, moving from a baseline Convolutional Neural Network (CNN) to a highly optimized architecture using MobileNetV2 for feature extraction and accuracy.

## Performance and Metrics
* **Final Test Accuracy:** 93.67%
* **Architecture:** MobileNetV2 (Transfer Learning)
* **Optimization Techniques:** Dropout layers and data augmentation (rotations, zooms, flips) were utilized to eliminate overfitting and ensure the model generalizes well to real-world backgrounds.

## Key Features
* **Iterative Model Development:** Transitioned from custom CNN layers to pre-trained weights to maximize precision.
* **Advanced Data Pipeline:** Engineered a custom loading pipeline capable of parsing YOLO format labels and converting them into categorical variables for supervised learning.
* **Real-Time Inference Web App:** Integrated a Streamlit based interface where users can upload field imagery and receive classification results with associated confidence scores.
* **Robust Pre-processing:** Utilized OpenCV and NumPy for image standardization and noise reduction.

## Tech Stack
* **Deep Learning:** TensorFlow, Keras
* **Base Model:** MobileNetV2
* **Deployment:** Streamlit
* **Computer Vision:** OpenCV
* **Data Manipulation:** NumPy, Scikit-learn, Pandas
* **Programming Language:** Python



