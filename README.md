# UAV-Attitude-Estimation

## Overview

This project focuses on the implementation of advanced filtering techniques for precise attitude estimation of a quadrotor using quaternion representation. Utilizing Complementary, Madgwick, and Unscented Kalman Filter (UKF) algorithms, the project aims to accurately estimate the 3D orientation of a quadrotor navigating through space. The estimations are benchmarked against ground-truth data obtained from a Vicon Motion Capture System to ensure accuracy and reliability.

## Features

- Implementation of Complementary, Madgwick, and UKF algorithms for attitude estimation.
- Benchmarking of filter outputs against Vicon Motion Capture System ground truth.
- Quaternion representation for efficient and accurate orientation tracking.

## Prerequisites

- Python 3.x
- Required Python libraries: `numpy`, `matplotlib`, `scipy`

## Usage

To run the project and perform attitude estimation, follow these steps:

1. **Data Preparation**: Make sure the IMU and Vicon data are placed in the appropriate directories as outlined in the project structure. The expected structure is `Data/Train/IMU` for IMU data and `Data/Train/Vicon` for Vicon data.

2. **Sensor Calibration**: Align the IMU data with the Vicon system by following the sensor calibration steps provided. This step is crucial for accurate attitude estimation.

3. **Filter Application**: Select the filter you wish to apply—Complementary, Madgwick, or UKF—and execute the corresponding script. Ensure Python and necessary libraries are installed and configured correctly.

4. **Visualization**: Use `rotplot.py` for a basic visualization of the estimated orientation. This script provides a visual representation of the quadrotor's attitude over time, making it easier to analyze the performance of the chosen filter.

## Final Result

For a visual demonstration of the attitude estimation process and its accuracy, see the GIF below:

![Quaternion-based Attitude Estimation Demo](https://github.com/mayankbansal82/UAV-Attitude-Estimation/blob/main/Result/Result.gif)


