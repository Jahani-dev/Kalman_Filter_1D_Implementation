# Kalman Filter 1D Implementation #

This repository demonstrates the application of a 1D Kalman Filter to denoise a simulated time-series signal (a noisy sine wave).
It compares a manual implementation of the Kalman filter with a built-in version from the "filterpy" library.

## Biomedical Signal Processing Applications
Kalman Filters are widely used in biomedical engineering to extract meaningful information from noisy physiological signals in real time. Common applications include:

- EEG & fNIRS: Noise reduction, mental state estimation, hybrid BCI systems
- ECG / EKG: Denoising, heartbeat tracking, real-time R-peak detection
- EMG: Muscle activation smoothing, prosthetic control, motor intent decoding
- EOG: Eye movement tracking, blink artifact rejection in human-computer interfaces
- SpO₂ (Pulse Oximetry): Smoothing oxygen saturation trends, removing motion-induced artifacts
- Respiratory Signals: Breath rate tracking, filtering impedance pneumography data
- Sensor Fusion: Combining multiple biosignals for robust state estimation (e.g., EEG + fNIRS)

Kalman Filters provide real-time, adaptive estimation capabilities that are especially useful in wearable health devices, neurotechnology, and remote monitoring systems.

## What This Project Does

- Simulates a noisy sine wave
- Applies the Kalman filter (manual and built-in)
- Visualizes and compares the results


## Libraries Used

- `numpy`
- `matplotlib`
- `filterpy`



## Applications

This basic Kalman filtering concept can be extended to:
- fNIRS preprocessing
- EEG/ECG denoising
- Time-series prediction
- Robotics and control systems


## Files

- `Kalman_Filter_Implementation.py`: Python code for simulation and filtering
- `Figure_*.png`: Visualization of the results


## Author

Sahar Jahani  
[GitHub Profile](https://github.com/Jahani-dev)


Feel free to fork, modify, and use this as a starter for more advanced filters like:
- 2D Kalman filters
- Extended Kalman Filters (EKF)
- Unscented Kalman Filters (UKF)
