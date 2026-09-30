# ECG Signal Analysis Using Python

## Project Overview

This project analyzes electrocardiogram (ECG) signals using Python.

The ECG data is obtained from the MIT-BIH Arrhythmia Database on PhysioNet.

The main goals of this project are:

- Load real ECG data
- Visualize ECG signals
- Detect R peaks
- Calculate RR intervals
- Estimate heart rate
- Compare detected R peaks with expert annotations
- Evaluate detection performance using sensitivity, precision and F1 score

---

## Background

Electrocardiography (ECG) records the electrical activity of the heart.

A typical ECG waveform contains:

- P wave: atrial depolarization
- QRS complex: ventricular depolarization
- T wave: ventricular repolarization

The R peak is one of the most prominent features in an ECG signal and is commonly used to calculate RR intervals and heart rate.

---

## Dataset

This project uses the MIT-BIH Arrhythmia Database.

Dataset information:

- Database: MIT-BIH Arrhythmia Database
- Record: 100
- Sampling frequency: 360 Hz
- Data source: PhysioNet
- Analysis duration: 60 seconds

---

## Tools and Libraries

The project is implemented in Python.

Main libraries:

- NumPy
- Matplotlib
- SciPy
- WFDB
- Jupyter Notebook

---

## Analysis Workflow

The project follows this workflow:

```text
MIT-BIH ECG Data
        ↓
Load ECG Signal
        ↓
Visualize ECG
        ↓
Detect R Peaks
        ↓
Calculate RR Intervals
        ↓
Estimate Heart Rate
        ↓
Compare with Expert Annotations
        ↓
Evaluate Detection Performance