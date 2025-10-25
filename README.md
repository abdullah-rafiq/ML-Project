#  Human Activity Recognition – Data Preprocessing & Feature Scaling

This repository contains preprocessing and feature-scaling code for the **HAR-Sense Dataset**, a Human Activity Recognition dataset available on Kaggle.  
The notebook demonstrates feature normalization, variance-based feature selection, and visualization to prepare sensor data for machine learning.

---

## Dataset

**HAR-Sense Dataset**  
 Download: [Kaggle – HAR-Sense Dataset](https://www.kaggle.com/datasets/nurulaminchoudhury/harsense-datatset/data)

The dataset contains motion sensor readings (accelerometer, gyroscope, and magnetometer) from multiple subjects performing various daily activities.  
It is designed for Human Activity Recognition (HAR) tasks.

---

## Features Implemented

- **Libraries Used**
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `scipy.signal` (for peak detection)
  - `sklearn` (for scaling, encoding, and feature selection)

- **Data Preprocessing Steps**
  1. Dataset loading and inspection  
  2. Missing value handling (if required)  
  3. Statistical feature visualization  
  4. Feature scaling using:
     - MinMaxScaler  
     - StandardScaler  
     - RobustScaler  
     - MaxAbsScaler  
  5. Feature selection using:
     - Variance Threshold  
     - Mutual Information  
  6. Label encoding for classification

---

## Visualizations

The notebook includes visual comparisons of scaled features and activity distributions:
- Histograms and KDE plots
- Correlation heatmaps
- Sensor signal peak detection
- Scaler-wise comparison plots

---

