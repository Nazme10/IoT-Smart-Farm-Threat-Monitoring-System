![Cisco Packet Tracer](https://img.shields.io/badge/Cisco-Packet%20Tracer-blue)
![Python](https://img.shields.io/badge/Python-3.x-yellow)
![IoT](https://img.shields.io/badge/IoT-Smart%20Agriculture-green)
![License](https://img.shields.io/badge/License-MIT-red)


# 🌱 IoT-Based Smart Farm Threat Monitoring System
IoT-based Smart Farm Threat Monitoring System using Cisco Packet Tracer with DHCP, IoT sensors, smart automation, and real-time monitoring.






---

##  Overview

Traditional farming often relies on manual monitoring, making it difficult to respond quickly to environmental changes and security threats. This project demonstrates how IoT technologies can be integrated into agriculture to create an automated smart farming environment.

The system incorporates multiple sensors and actuators connected through a centralized Home Gateway. Dynamic IP address assignment using DHCP simplifies network management while enabling seamless communication among devices.

---

##  Features

-  Soil moisture monitoring with automatic irrigation
-  Fire and smoke detection with automatic sprinkler activation
-  Wild animal intrusion detection using PIR sensors
-  Smart lighting based on ambient light conditions
-  RFID-based smart door access control
-  Air quality monitoring with automated exhaust fans
-  Solar-powered energy management
-  DHCP-enabled automatic IP address allocation
-  Wireless communication through a centralized Home Gateway





---

## ⚙️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Cisco Packet Tracer | IoT Network Simulation |
| Python | Device Logic Simulation |
| DHCP | Automatic IP Address Assignment |
| IoT Devices | Smart Farm Automation |
| Wireless Networking | Communication |
| RFID | Secure Door Access |

---

## 🌐 Network Configuration

| Parameter | Value |
|-----------|-------|
| Gateway IP | 192.168.1.1 |
| DHCP Range | 192.168.1.100 – 192.168.1.200 |
| Network Type | Wireless |
| Address Allocation | Dynamic (DHCP) |

---



---

## 📷 Screenshots



### Network Topology

<p align="center">
<img src="Images/Logical view of the design.png" width="700">
</p>

### Physical Layout

<p align="center">
<img src="Images/Physical view of the design.png" width="700">
</p>

### Ping Test

<p align="center">
<img src="Images/Ping results.png" width="700">
</p>

---

## 🚀 How to Run

1. Install **Cisco Packet Tracer**.
2. Open the `SmartFarm.pkt` simulation file.
3. Start the simulation mode.
4. Observe the interaction between sensors and actuators.
5. Verify network connectivity using the built-in ping utility.
6. Test individual modules by modifying sensor values.

---

## 📈 System Modules

###  Soil Moisture Monitoring
Automatically activates the sprinkler system when soil moisture falls below a predefined threshold.

###  Fire Detection
Detects smoke and immediately activates both the alarm and sprinkler system.

###  Wild Animal Detection
Uses PIR sensors to detect movement and trigger a siren to deter intrusions.

###  Smart Door Security
Allows access only to authorized RFID cards while rejecting unauthorized users.

###  Air Quality Monitoring
Monitors CO₂ concentration and automatically activates exhaust fans when required.

###  Solar Energy Management
Uses solar panels and battery management to provide sustainable power for IoT devices.

###  Smart Lighting
Adjusts lighting automatically based on surrounding light intensity.

---

## 📊 Results

- Successful DHCP-based network configuration
- Reliable wireless communication among IoT devices
- Automatic IP assignment without conflicts
- Successful connectivity verified through ping testing
- Fully functional automated monitoring and response system

---

## 🔮 Future Improvements

- Integration with real-world IoT hardware
- Weather API integration
- Mobile application for remote monitoring
- SMS and Email alert system
- Cloud database integration
- Machine Learning for predictive farming
- Real-time analytics dashboard

---




---

## 📄 License

This project is intended for educational and academic purposes.

---



If you find this repository helpful, consider giving it a ⭐ to support the project.
