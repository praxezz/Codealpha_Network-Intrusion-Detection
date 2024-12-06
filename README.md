Intrusion Detection System (IDS) Simulation
Overview
This project simulates an Intrusion Detection System (IDS) that monitors network traffic, detects malicious activities, and provides alerts based on specific network behavior. The system is designed to capture, analyze, and classify network traffic into normal or suspicious categories using both rule-based and machine learning approaches.

The simulation uses tools like Scapy for network packet capturing, Matplotlib for data visualization, and Scikit-learn for implementing machine learning-based anomaly detection.

Key Features
Network Traffic Capture: Captures and analyzes packets from the network.
Malicious Traffic Detection: Detects suspicious activities like HTTP GET requests and simulates network attacks like DDoS (Ping flood).
Traffic Visualization: Visualizes packet sizes and traffic patterns over time.
Anomaly Detection: Uses machine learning to classify traffic as normal or suspicious based on packet features.
DDoS Simulation: Simulates a DDoS (Ping flood) attack to test IDS response.
Technologies Used
Scapy: For network packet sniffing and manipulation.
Scikit-learn: For implementing machine learning algorithms to detect anomalies in network traffic.
Matplotlib: For plotting and visualizing packet sizes and network traffic patterns.
Python: Programming language used for the implementation.
