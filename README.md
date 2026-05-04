# Kalman Filter Implementation in Python

This repository provides a clean, modular implementation of the Kalman Filter, a powerful recursive filter that estimates the state of a dynamic system from a series of noisy measurements.

## Features
- **Linear Kalman Filter**: Core implementation for state estimation.
- **Modular Design**: Easy to integrate into other projects (robotics, finance, sensor fusion).
- **Visualization**: Built-in scripts to compare noisy measurements vs. filtered estimates.

## How it Works
The Kalman Filter operates in a two-step process:
1. **Prediction**: The filter predicts the next state based on the current estimate.
2. **Update**: The filter updates the estimate using a noisy measurement.



## Installation
```bash
git clone [https://github.com/nadiahmdi/KalmanFilter.git](https://github.com/nadiahmdi/KalmanFilter.git)
cd KalmanFilter
pip install numpy matplotlib
