# AI-Powered Stroke Detection System (CNN + Medical Imaging)

A deep learning-based medical image classification system that detects stroke from CT scan images using Convolutional Neural Networks (CNN) and OpenCV preprocessing techniques.

##  Overview

This project implements a CNN-based classifier trained on real-world CT scan images to detect stroke with 95% accuracy. The system includes:

- Image preprocessing using OpenCV
- CNN training and evaluation
- Model comparison with Random Forest and Decision Tree
- Web-based deployment using Django
- Real-time stroke prediction interface

##  Model Performance

- Accuracy: 95%
- Precision: 95%
- Recall: 94%
- F1-Score: 94%

The CNN outperformed traditional ML baselines.

##  Architecture

1. Image Preprocessing (OpenCV)
   - Noise reduction (Gaussian Blur)
   - Contrast enhancement (CLAHE)
   - Edge detection
   - Normalization & resizing (224x224)

2. CNN Model
   - Convolution + MaxPooling layers
   - Fully connected layers
   - Softmax output
   - Adam optimizer
   - Categorical Cross-entropy loss

3. Web Deployment
   - Django backend
   - Image upload interface
   - Real-time prediction output

##  Tech Stack

  - Python
  - TensorFlow / Keras
  - OpenCV
  - Django
  - NumPy / Pandas
  - Matplotlib

##  Project Structure
  AI-Stroke-Detection-CNN/
  │
  ├── model/
  ├── static/
  ├── templates/
  ├── app.py
  ├── requirements.txt
  └── README.md

##  Dataset

  Kaggle Brain CT Scan dataset (Normal vs Stroke classes)

##  How to Run

```bash
pip install -r requirements.txt
python app.py
```
Then open:
http://127.0.0.1:5000
