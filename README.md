# Anomaly Detection in Manufacturing Data 🏭

## Overview
This repository contains a Deep Learning solution for detecting anomalies in manufacturing time-series data. 

## The Solution
I utilized an **LSTM Autoencoder** architecture to identify data points that deviate significantly from normal operating patterns. This approach is unsupervised, making it ideal for scenarios where "anomaly" labels are scarce or unknown.

### Key Methodology:
1.  **Data Preprocessing:** Cleaning, scaling (MinMax), and reshaping data for temporal sequence processing.
2.  **Model Architecture:** An LSTM Autoencoder that learns to reconstruct "normal" time-series data.
3.  **Anomaly Detection:** By calculating the **Reconstruction Error (MAE)**, the model flags data points where the error exceeds a calculated threshold.

## How to Run
This project is designed to run in Google Colab for easy reproduction of results.

1.  Click the **"Open in Colab"** badge at the top of the notebook file.
2.  Run all cells sequentially.
3.  The notebook will download the necessary dataset automatically (or requires upload if specified in the notebook steps).

## Tech Stack
*   **Python**
*   **TensorFlow/Keras** (for LSTM implementation)
*   **Pandas & NumPy** (for data manipulation)
*   **Matplotlib/Seaborn** (for visualization of anomalies)

---
*Submitted by GOWTAM.J*
