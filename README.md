# MRITUMORDETECTION
MRI Tumor Detection Project On Computer Vision

# Brain Tumor Detection from MRI using Computer Vision

## Project Overview
This project implements a **simple computer vision–based deep learning system** to detect brain tumors from MRI scan images. A **Convolutional Neural Network (CNN)** is used to classify MRI images into two categories: **Tumor** and **No Tumor**.

The project is designed as a **beginner-friendly academic mini project** demonstrating the application of computer vision and deep learning in healthcare.

---

## Objectives
- Preprocess MRI brain images for model training  
- Train a CNN for binary image classification  
- Predict tumor presence from MRI scans  
- Understand medical image analysis using computer vision  

---

## Project Structure


---

## Dataset
- Public MRI brain image dataset
- Two classes:
  - **yes** → Tumor present
  - **no** → No tumor present

> Dataset is for academic and learning purposes only.

---

## Technologies Used
- Python  
- OpenCV  
- NumPy  
- TensorFlow / Keras  
- Scikit-learn  
- Matplotlib  

---

## Methodology
1. **Image Preprocessing**
   - Resize to 128×128 pixels
   - Normalize pixel values
   - Convert images to NumPy arrays

2. **Model Architecture**
   - Convolutional layers for feature extraction
   - Max pooling layers for dimensionality reduction
   - Fully connected layers for classification
   - Softmax output layer

3. **Training**
   - Optimizer: Adam  
   - Loss Function: Categorical Cross-Entropy  
   - Epochs: 10  
   - Train-test split: 80%–20%

4. **Prediction**
   - Load trained model
   - Predict tumor presence for new MRI images

---

## How to Run the Project

### Install Required Libraries
```bash
pip install tensorflow opencv-python numpy matplotlib scikit-learn

