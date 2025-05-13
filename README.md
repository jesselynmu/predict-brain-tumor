![Preview](Brain Tumor.png)

# Brain Tumor Prediction Using MRI Scans

This project aims to classify brain tumor types using MRI images. The brain is one of the most vital organs in the human body, acting as the central nervous system. Like other organs, it is vulnerable to serious diseases — one of which is brain tumors. There are four types of brain tumors considered in this project: **glioma**, **meningioma**, **pituitary**, and **no tumor**.

## 🧠 Problem Background

MRI (Magnetic Resonance Imaging) is commonly used to capture brain scans, but it does not inherently classify tumor types. To assist medical diagnosis, this project develops a system that classifies MRI images using image processing and machine learning.

## 🔍 Methods

- **Feature Extraction**: 
  - Canny and Sobel edge detection are applied to extract meaningful features (number of white pixels).
- **Classification**: 
  - K-Nearest Neighbors (KNN) algorithm is used for tumor classification.

## 🛠 Tools & Libraries

- Python
- OpenCV (for image segmentation)
- scikit-learn (for KNN model)
- Jupyter Notebook / Google Colab

## ✅ Results

- **Accuracy**: 75.85%
- **Precision**: 75.13%
- **Recall**: 75.34%
- **F1 Score**: 0.75

These results show that the chosen methods can classify brain tumor types with decent performance and have the potential to assist early diagnosis efforts.
