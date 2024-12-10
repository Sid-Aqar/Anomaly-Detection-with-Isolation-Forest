# Anomaly-Detection-with-Isolation-Forest

## Overview
This project demonstrates anomaly detection using the Isolation Forest algorithm on a synthetic dataset. The dataset contains cluters of normal data and injected outliers representing anomalies.

## Features
- Synthetic dataset generation with clusters and anomalies.
- Preprocessing with StandardScaler.
- Anomaly detection using Isolation Forest.
- Visualization of detected anomalies.

## Tools and Libraries
- Python
- Scikit-learn
- matplotlib
- numpy

## Results
The model successfully identified anomalies in the dataset. The visualization highlights normal points and anomalies.
- Normal Points:
    - Precision: 0.99
    - Recall: 0.95
    - F1-Score: 0.97

- Anomalies:
    - Precision: 0.50
    - Recall: 0.80
    - F1-Score: 0.62

  The Isolation Forest algorithms achieved high accuracy in detecting normal points and moderate performance in identifying anomalies.

## How to Run
1. Clone this respository
2. Open it in Google Colab or Jupyter Notebook.
3. Run the cells to see results

## Key insights
- Isolation Forest is effective for detecting anomalies in high-dimentional data.
- Synthetic datasets provide a simple way to experiment with anomaly detection.
