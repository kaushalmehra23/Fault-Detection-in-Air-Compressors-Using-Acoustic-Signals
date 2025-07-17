# Fault-Detection-in-Air-Compressors-Using-Acoustic-Signals
This repository contains the code, report, and presentation for our course project under EE656: Artificial Intelligence, Machine Learning, Deep Learning & Its Applications, guided by Prof. Nischal K. Verma at IIT Kanpur.
---
# Objective
To develop a machine learning model that can classify the health state of an air compressor from raw acoustic signals, enabling predictive maintenance and fault diagnosis in real-time or embedded systems.
--
# Dataset
The dataset used for this project—raw acoustic recordings of 8 air compressor health/fault states—is provided by Prof. Nischal K. Verma and can be downloaded from his [official website](https://www.iitk.ac.in/idea/datasets/index.html).
---
# Approach
Extracted features using FFT, DCT, Wavelet Packet Transform (WPT), STFT, and key time-domain statistics.
Normalized features with StandardScaler and selected the top 25 using mutual information.
Trained a multi-class SVM (RBF kernel) with 5-fold cross-validation for robustness.
---
# Result & Impact
Achieved 98.89% classification accuracy across 8 distinct fault/health states.
Model is lightweight and computationally efficient, making it suitable for real-time deployment in embedded or edge devices
--
