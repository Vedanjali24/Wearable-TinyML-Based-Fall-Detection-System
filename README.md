# Wearable-TinyML-Based-Fall-Detection-System
This project focuses on the design and development of a wearable health monitoring system capable of performing real-time motion analysis and fall detection directly on the device. The system is built around the ESP32 microcontroller, which serves as the main processing unit for sensor data acquisition, TinyML inference, and data logging.

The device integrates an MPU6050 inertial measurement unit (IMU) to capture motion and orientation data and a MAX30102 optical sensor for physiological monitoring such as heart rate and blood oxygen levels. Motion data from the IMU is processed locally using a TinyML model trained for fall detection, allowing the system to identify abnormal movement patterns without requiring external computation resources.

To enable reliable data storage and post-analysis, the system includes SD card logging, where raw sensor readings and detected events are stored during operation. This allows offline analysis of movement patterns, model performance evaluation, and long-term monitoring.

A key objective of the system is privacy-preserving edge intelligence. All inference and decision-making are performed directly on the embedded device, eliminating the need for continuous cloud connectivity. This reduces latency, lowers power consumption, and ensures that sensitive health data remains local to the device.

The combination of embedded machine learning, sensor fusion, and edge processing enables the device to operate as a compact and efficient health monitoring platform capable of detecting potential falls and anomalies in real time.


<img width="780" height="913" alt="image" src="https://github.com/user-attachments/assets/e51a8355-5e8d-40ee-aa21-9d8032b74b6a" />
