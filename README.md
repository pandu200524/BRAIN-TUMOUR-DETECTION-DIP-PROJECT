Brain Tumor Detection Using YOLOv4
Overview
This project focuses on automating the detection of brain tumors in MRI scans using deep learning techniques. The YOLO (You Only Look Once) v4 model, implemented through Ultralytics and Roboflow, is used for accurate and efficient tumor detection in medical imaging.

Features
-Automatic brain tumor detection in MRI images
-YOLOv4-based deep learning model
-Visualization of detected tumor areas with annotations
-Pseudo-color enhancement for better analysis

Project Workflow
Data Collection & Preprocessing

MRI images are collected and processed using Roboflow.
The dataset is prepared for training YOLOv4.
Model Training

The YOLOv4 model is trained on labeled MRI images.
Training parameters such as batch size, epochs, and image size are optimized.
Tumor Detection & Visualization

The trained model predicts tumor locations on unseen MRI images.
The detected regions are annotated and enhanced with pseudo-color mapping.
Results & Evaluation

The model's predictions are visualized with bounding boxes and color mapping.
Output images display detected tumor areas clearly for analysis.
