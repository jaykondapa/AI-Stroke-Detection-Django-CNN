\# AI-Powered Stroke Detection System using CNN



A deep learning-based medical image classification system that detects stroke from CT scan images using Convolutional Neural Networks (CNN) and OpenCV preprocessing techniques.



\##  Overview



This project implements a CNN-based classifier trained on real-world CT scan images to detect stroke with 95% accuracy. The system includes:



\- Image preprocessing using OpenCV

\- CNN training and evaluation

\- Model comparison with Random Forest and Decision Tree

\- Web-based deployment using Django

\- Real-time stroke prediction interface



\##  Model Performance



\- Accuracy: 95%

\- Precision: 95%

\- Recall: 94%

\- F1-Score: 94%



The CNN outperformed traditional ML baselines.



\##  Architecture



1\. Image Preprocessing (OpenCV)

&nbsp;  - Noise reduction (Gaussian Blur)

&nbsp;  - Contrast enhancement (CLAHE)

&nbsp;  - Edge detection

&nbsp;  - Normalization \& resizing (224x224)



2\. CNN Model

&nbsp;  - Convolution + MaxPooling layers

&nbsp;  - Fully connected layers

&nbsp;  - Softmax output

&nbsp;  - Adam optimizer

&nbsp;  - Categorical Cross-entropy loss

&nbsp;  - Training epochs: 30

&nbsp;  - Batch size: 32

&nbsp;  - Train/Test split: 80/20



3\. Web Deployment

&nbsp;  - Django backend

&nbsp;  - Image upload interface

&nbsp;  - Real-time prediction output



\##  Tech Stack



&nbsp; - Python

&nbsp; - TensorFlow / Keras

&nbsp; - OpenCV

&nbsp; - Django

&nbsp; - NumPy / Pandas

&nbsp; - Matplotlib



\##  Project Structure

&nbsp; AI-Stroke-Detection-Django-CNN/

&nbsp;  │

&nbsp;  ├── AdminApp/

&nbsp;  ├── UserApp/

&nbsp;  ├── BrainStrokeCNN/ # Django settings

&nbsp;  ├── model/ # Trained CNN model (.h5)

&nbsp;  ├── static/ # Static assets

&nbsp;  ├── templates/ # HTML templates

&nbsp;  ├── manage.py

&nbsp;  ├── requirements.txt

&nbsp;  └── README.md



\##  Dataset



&nbsp; Kaggle Brain CT Scan dataset (Normal vs Stroke classes)



\##  How to Run



```bash

pip install -r requirements.txt

python app.py

```

Then open:

http://127.0.0.1:5000

## Sample Inputs

Example CT scan images are included in the `sample_images/` folder for quick testing.



