# ML-fingerspelling-classification
Detect and translate fingerspelling hand signs to text using CNNs VGG-16, VGG-19, and ResNet50V2 models.

This project addresses the intersection of technology and communication through Hand Gesture Recognition (HGR), with a focus on Fingerspelling—an essential aspect of sign language. Motivated by the increasing prevalence of hearing impairments globally, our objective is to develop a system capable of accurately detecting and translating hand signs into text, thereby facilitating seamless communication for individuals with hearing impairments.

We leverage Convolutional Neural Networks (CNNs), exploring the VGG-16, VGG-19, and ResNet architectures known for their efficacy in image recognition tasks. The project methodology involves data preprocessing using the ASL Fingerspelling Dataset from Kaggle, data augmentation to enhance model robustness, and hyperparameter tuning for optimization.

Results from model training and evaluation indicate that VGG-16 initially faced challenges with augmented data, prompting the addition of layers to improve performance significantly. Hyperparameter tuning further refines the models, with ResNet consistently outperforming VGG-16 and VGG-19.

Looking ahead, future work involves real-time American Sign Language (ASL) gesture prediction using the trained models in conjunction with the Open Source Computer Vision Library (OpenCV). This advancement aims to bridge communication gaps by providing a smooth interface for ASL to English translation in real-time, fostering accessibility and inclusion. 

