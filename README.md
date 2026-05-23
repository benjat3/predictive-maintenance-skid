# Predictive Maintenance Skid ⚙️

## Project Overview
This project consists of a low-cost, real-time vibration analysis skid designed for predictive maintenance. It simulates mechanical faults and captures vibration data to perform spectral analysis (FFT) and detect anomalies before catastrophic failure occurs.

<!-- 
TODO (Mechanical Team): 
1. Add a good quality picture of the assembled skid here.
Format: ![Skid Prototype](docs/images/skid_frontal.jpg)

2. Create a "Mechanical Hardware" section below and list the specific components:
- Main Pump: (Model)
- Motor: (Model / RPM / HP)
- Coupling: (Type)
- Base: (Material/Design)
-->

## System Architecture

*   **Hardware:** ESP32 Microcontroller, and sensors to be defined.
    <!-- TODO: Update the sensor models here once the BOM is approved (e.g., ADXL345, ST IIS3DWB,ADXL1002) -->
*   **Software:** Python (with Pandas, NumPy, SciPy).

## Repository Structure
*   `/docs`: Project management, Gantt charts, and milestones.
*   `/hardware`: Bill of Materials (BOM), CAD designs, and component datasheets.
*   `/software/mcu_firmware`: C++ code for the ESP32 data acquisition.
*   `/software/data_analysis`: Python scripts and Jupyter Notebooks for signal processing.
