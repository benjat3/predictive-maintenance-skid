# Predictive Maintenance Skid ⚙️

## Project Overview
This project consists of a low-cost, real-time vibration analysis skid designed for predictive maintenance. It simulates mechanical faults and captures vibration data to perform spectral analysis (FFT) and detect anomalies before catastrophic failure occurs.

## System Architecture
*   **Hardware:** ESP32 Microcontroller, and sensors to be defined.
*   **Software:** Python (with Pandas, Numpy, SciPy.)

## Repository Structure
*   `/docs`: Project management, Gantt charts, and milestones.
*   `/hardware`: Bill of Materials (BOM), CAD designs, and component datasheets.
*   `/software/mcu_firmware`: C++ code for the ESP32 data acquisition.
*   `/software/data_analysis`: Python scripts and Jupyter Notebooks for signal processing.
