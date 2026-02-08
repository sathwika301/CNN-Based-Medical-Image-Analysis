#  Medical Image Classification using Deep Learning

# Project Overview
This project focuses on classifying medical chest X-ray images into two categories:
- **NORMAL**
- **PNEUMONIA**

A Convolutional Neural Network (CNN) with transfer learning is used to automatically detect pneumonia from X-ray images. The model is trained, evaluated, and tested using deep learning techniques.

---

# Objectives
- To apply deep learning in medical image classification  
- To build a CNN-based model for pneumonia detection  
- To visualize training performance using accuracy and loss graphs  
- To evaluate the model using test data and prediction samples  

---

# Technologies Used
- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  
- Scikit-learn  
- OpenCV  

---

# Dataset
The dataset used is a **Chest X-ray Pneumonia dataset** containing medical images categorized into:
- Normal lungs
- Pneumonia-infected lungs

Images were preprocessed, resized, and augmented before training.

---

# Model Details
- Image Size: **150 × 150**
- Model Type: **Convolutional Neural Network (CNN)**
- Transfer Learning: **MobileNetV2**
- Optimizer: **Adam**
- Loss Function: **Binary Crossentropy**
- Activation Function: **ReLU / Sigmoid**
- Evaluation Metrics: **Accuracy**

---

# Results
The model was successfully trained and evaluated.  
Performance was analyzed using:
- Training vs Validation Accuracy graph
- Training vs Validation Loss graph
- Confusion Matrix
- Sample Predictions on test images

The model demonstrates good performance in distinguishing pneumonia cases from normal X-rays.

---

