# NetShield - Real-Time Network Monitoring
<img width="1024" height="1024" alt="screenshot" src="https://github.com/user-attachments/assets/eecdae64-b6c4-4067-b4df-fc9bda4ae8c8" />
A comprehensive network monitoring system designed to detect and alert on various network-related events, including DDoS attacks, bandwidth overutilization, unauthorized access attempts, suspicious port scanning activity, and unauthorized protocol usage.

## Key Features

### Real-Time Packet Capture
- Utilizes **jNetPcap** to capture and analyze live network packets.

### Database Integration
- Stores captured packet logs and alert data in a **MySQL** database for long-term analysis.

### Alert System
- Triggers real-time pop-up notifications for critical events using **JavaFX**.

### GUI Interface
- Provides a clean and interactive dashboard to view traffic logs, alerts, and monitoring statistics.

### Multithreading Support
- Employs multithreading to efficiently manage concurrent monitoring and processing tasks without performance bottlenecks.

## Technologies Used

- **Java** with **JavaFX** for the graphical user interface
- **jNetPcap** library for packet capturing
- **MySQL** for database storage
- **JDBC** for database connectivity and operations

## Use Cases

### Network Security Monitoring
- Detects potential threats such as DDoS attacks, suspicious port scanning, and unauthorized access attempts.

### Performance Monitoring
- Monitors and tracks bandwidth usage to prevent overutilization.

### Compliance Monitoring
- Identifies unauthorized or restricted protocol usage to maintain network compliance.

## Getting Started

1. Clone the repository.
2. Install the required libraries:
   - jNetPcap
   - MySQL Connector/J
3. Configure the database credentials in the project files.
4. Run `PacketCapture.java` to begin network packet capturing.
5. Run `NetworkMonitorGUI.java` to launch the graphical interface.
