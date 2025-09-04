# EV Battery Anomaly Detection

This repository contains a pipeline for detecting anomalies in **real EV driving cycle data (TripA series)** using physics-informed features and machine learning.

---

##  Features
- Extracts key battery/thermal features:
  - Voltage & current variability
  - Temperature range & gradient
  - SoC drop rate
  - Energy consumption efficiency
- Uses **Isolation Forest** for unsupervised anomaly detection.
- Saves results to CSV:
  - `tripA_features.csv`
  - `tripA_anomalies.csv`
- Provides plots comparing normal vs anomalous trips (voltage, current, temperature).

## Acknowledgments
- EV trip dataset: Battery and heating data in real driving cycles [kaggle.com]([https://link-url-here.org](https://www.kaggle.com/datasets/atechnohazard/battery-and-heating-data-in-real-driving-cycles).


