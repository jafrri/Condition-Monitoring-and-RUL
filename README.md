🔧 Bearing Fault Detection & Remaining Useful Life (RUL) Prediction

This project presents an end-to-end machine learning pipeline for fault detection and Remaining Useful Life (RUL) prediction of rotating machinery bearings using vibration signal data. It combines signal processing, feature engineering, and both classical and deep learning models to deliver accurate and scalable condition monitoring.

🚀 Overview

The system is designed to analyze real-world vibration data from industrial bearings and provide:

Fault classification (healthy vs defective conditions)
Degradation stage prediction (multi-stage health modeling)
Remaining Useful Life (RUL) estimation
Interactive web-based interface for real-time inference

The pipeline closely reflects real industrial scenarios, including non-stationary operating conditions and time-varying rotational speeds.

🧠 Key Features
Signal Processing & Feature Engineering
Time-domain and frequency-domain analysis (FFT)
Advanced features: RRMS (Relative RMS) and IRRMS (trend-smoothed RMS)
Outlier handling and trend extraction using regression-based filtering
Machine Learning Models
Support Vector Machine (SVM) for degradation stage classification
Random Forest for comparative analysis
CNN-LSTM for deep learning-based sequence modeling
RUL Prediction Framework
Stage-based degradation modeling (5 health stages)
Dynamic life progression mapping
Hybrid slope-based degradation estimation
Mathematical formulation for time-based RUL prediction
High Performance
Up to 99.93% classification accuracy
Low RUL prediction error (~1.35% MAE using SVM)
Full-Stack Deployment
Web-based interface for:
Uploading vibration data (.csv / .mat)
Automated preprocessing & feature extraction
Real-time fault classification & RUL prediction
Visualization of signals and diagnostic plots
📊 Dataset

The project uses real-world vibration datasets with:

High sampling rates (up to 200 kHz)
Multiple fault conditions:
Healthy
Inner race defect
Outer race defect
Ball defect
Combined faults
Variable speed profiles to simulate real industrial conditions
⚙️ Workflow
Data Collection & Preprocessing
Explatory Data Analysis (EDA)
Feature Extraction (RRMS, IRRMS)
Degradation Stage Labeling
Model Training (SVM / RF / CNN-LSTM)
RUL Estimation
Deployment via Web Interface
🖥️ Input Format

The system accepts vibration data with the following structure:

Timestamp (Hour, Minute, Second, Microsecond)
Acceleration (X-axis, Y-axis)

Each sample represents high-frequency vibration data collected over a short duration.

📈 Applications
Predictive Maintenance
Industrial Condition Monitoring
Fault Diagnosis in Rotating Machinery
Smart Manufacturing Systems
📌 Conclusion

This project demonstrates how data-driven techniques combined with signal processing can enable reliable and accurate prediction of machine health. It provides a scalable solution for reducing downtime, optimizing maintenance schedules, and improving operational efficiency in industrial environments.
