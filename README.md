# Diabetic_Retinopathy_Project
Diabetic Retinopathy Detection using Deep Learning
Abstract
Diabetic Retinopathy (DR) is a serious eye condition caused by diabetes that can lead to vision loss if not detected early. This project presents a deep learning-based approach to automatically detect and classify diabetic retinopathy from retinal images, enabling faster and more reliable diagnosis.
Objectives
- Develop a deep learning model for detecting diabetic retinopathy
- Perform both binary and multi-class classification
- Improve diagnostic accuracy using image preprocessing techniques
System Architecture
1. Image Acquisition
2. Data Preprocessing (CLAHE)
3. Feature Extraction using Deep Learning
4. Classification (Binary & Multi-class)
5. Performance Evaluation
Dataset
APTOS Diabetic Retinopathy Dataset containing labeled retinal images across different severity levels:
No DR, Mild, Moderate, Severe, Proliferative DR
Methodology
Preprocessing:
Applied Contrast Limited Adaptive Histogram Equalization (CLAHE) to enhance image quality.

Model Implementation:
CNN for binary classification and DenseNet for multi-class classification.

Evaluation Metrics:
Accuracy, Precision, Recall, F1-Score
Results
Achieved approximately 80.11% accuracy, demonstrating effective performance in medical image classification.
Technologies Used
Python, TensorFlow, Keras, OpenCV, NumPy, Pandas, Matplotlib
Applications
Automated retinal screening, clinical decision support, early disease detection.
Future Scope
Improve accuracy with advanced models, integrate into web/mobile apps, enable real-time diagnosis.
Author
CHIMATA VARSHINI
