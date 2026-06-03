# Hooby Lab - User Guide 📘

Welcome to the **Hooby Lab** user guide. This document provides a comprehensive overview of the application's features, how to interpret the data, and how to maximize your security posture using our tools.

---

## 📋 Table of Contents
1. [Introduction](#1-introduction)
2. [Getting Started](#2-getting-started)
3. [The Dashboard](#3-the-dashboard)
4. [Device Discovery & Management](#4-device-discovery--management)
5. [Understanding Threats](#5-understanding-threats)
6. [Hardware Sensor Monitor](#6-hardware-sensor-monitor)
7. [AI Anomaly Detection](#7-ai-anomaly-detection)
8. [File System Scanner](#8-file-system-scanner)
9. [Network Security](#9-network-security)
10. [System Monitor](#10-system-monitor)
11. [Radio Frequency Monitor](#11-radio-frequency-monitor)
12. [Logs](#12-logs)
13. [Advanced Features](#13-advanced-features)
14. [Troubleshooting](#14-troubleshooting)

---

## 1. Introduction
Hooby Lab is a multi-platform security suite providing real-time monitoring of your network, Bluetooth environment, physical hardware sensors, file system, system resources, and radio frequencies to protect you from digital and physical intrusions. It includes AI-driven learning for threat patterns.

## 2. Getting Started
When you first launch the application, it will:
- Request location and Bluetooth permissions.
- Perform an initial scan for devices and threats.
- Initialize sensors and services.

**Initial Setup Tip**: Navigate to the Devices tab to review discovered devices. Use the "Trust" button for known devices to reduce false positives.
After the first search, nearby Bluetooth objects should be detected in the Bluetooth section of the dashboard.

## 3. The Dashboard
The Dashboard is your command center:
- **Status Header**: Shows "SYSTEM SECURE" in green if no high-severity threats, or "THREATS DETECTED" in red with count.
- **System Statistics**: Cards for total Devices, Attacks, Network devices, Bluetooth devices. Tap to view details.
- **Recent Threats**: List of the 5 most recent threats.
- **Bottom Navigation**: Access Sensors, Security, System, and More (Filesystem Scanner, Radio Monitor, Logs).
- **Actions**: Toggle theme, refresh scan.

Pull down to refresh the dashboard.

## 4. Device Discovery & Management
Accessed via stats cards or navigation, this screen lists discovered devices filtered by type (All, Network, Bluetooth & AirTags):
- Devices show name, IP/MAC, RSSI, last seen.
- For AirTags, flagged specially.
- Controls: Trust (mark as known), Block.
- Refresh to rescan.

## 5. Understanding Threats
Threats are logged and categorized by severity (High, Medium, Low).
- Access full log via Attacks stat card or More > Logs (threat-specific).
- Filter by date using calendar icon.
- Each threat card shows description, severity, timestamp.
- Clear logs if needed.

## 6. Hardware Sensor Monitor
Accessed via bottom nav "Sensors". Displays real-time data from device sensors:
- Accelerometer (X,Y,Z m/s²)
- Gyroscope (X,Y,Z rad/s)
- Magnetometer (X,Y,Z μT)
- Battery Level (%)
- Battery State
- Location (Lat, Lon GPS)
- Each sensor shows value, unit, timestamp.

Monitors for physical intrusions via movement or environmental changes.

## 7. AI Anomaly Detection
The AI service learns threat patterns over time:
- Analyzes network and application data for anomalies.
- Learns from detections, improving confidence scores.
- Matches against learned patterns for analysis.
- Provides confidence level and recommendations.
- Patterns can be verified as malicious or benign to improve accuracy.
- No dedicated screen; integrated into scans and analyses.

## 8. File System Scanner
Accessed via More > Filesystem Scanner. Scans for suspicious files:
- Header shows count by risk (Low, Medium, High), total files/size, current path if scanning.
- Progress bar during scan.
- Results list with path, reason, size, modified date, risk level.
- Select files with checkboxes, delete selected or all.
- Tap for details (full path, etc.).
- Refresh to rescan.

Configure scan frequency in settings if available.

**⚠️ Important**: Verify results before deleting; may impact performance.

## 9. Network Security
Accessed via bottom nav "Security". Tabs for Port Scan, App Test, Results:
- **Port Scan**: Enter target IP/hostname, ports (range or comma-separated). Start/Stop scan, progress bar. Shows open ports with service, vulnerabilities.
- **App Test**: Enter URL, select test type (XSS, SQL Injection, Headers, SSL/TLS, All). Start/Stop test.
- **Results**: List scan results (port, service, vulnerabilities) and test results (name, details, severity).

Protects against malicious traffic and vulnerabilities.

## 10. System Monitor
Accessed via bottom nav "System". Monitors performance and health:
- System Information: OS, Architecture, Hostname, CPU Cores, Last Updated.
- Memory Usage: Used/Total GB, percentage bar.
- Battery Status: Level %, State, bar.
- Network Information: IP, MAC, Active Connections.
- Network Connections: List with local/remote addr, protocol, status.
- Statistics: History Entries, Avg Memory/Battery %.

Refresh for latest data.

**⚠️ Important**: Monitoring may consume resources; adjust frequency if needed.

## 11. Radio Frequency Monitor
Accessed via More > Radio Monitor. Monitors radio frequencies for threats:
- Status Header: SDR active or not, last updated, signal alert if detected.
- SDR Hardware: List detected USB SDR devices (RTL-SDR, HackRF).
- Monitored Bands: List frequencies being scanned.
- Surveillance Alert: If Sub-GHz signals detected, warns of possible hidden devices.

Refresh to rescan.

## 12. Logs
Accessed via More > Logs. View system logs:
- Filter by date using calendar.
- Clear all logs.
- Each log shows message, timestamp, source, level (DEBUG, INFO, WARN, ERROR) with color-coded chips.

Separate from threat logs.

## 13. Advanced Features
- AI learning from detections to improve anomaly detection.
- Dart-based port scanning and app testing (no external tools like Nmap required).
- Sensor integration for physical security.

On rooted devices, additional capabilities may be available.

## 14. Troubleshooting
- **No Devices Detected**: Ensure Bluetooth/WiFi enabled, permissions granted, refresh scan.
- **Sensor Data Missing**: Check location/sensor permissions, GPS enabled.
- **Scan Failed**: Ensure network connectivity, correct target/ports.
- **High Resource Usage**: Reduce scan frequencies, close background processes.
- **File Scanner Errors**: Check storage permissions, available space.
- **Radio Monitor No SDR**: Connect compatible USB SDR device.
- **Logs Empty**: Run scans to generate logs.

For persistent issues, clear app data or reinstall.

---
## 📋 Legal & Privacy Notice

### Ownership & Liability
This application is wholly owned and operated by **Hooby Solutions** and **timotheuzi@hotmail.com**. By using this software, you acknowledge and agree to the following:

**No Guarantees**: This product is provided "as-is" with no guarantees of:
- Security effectiveness or protection capabilities
- Accuracy of threat detection
- Compatibility with all devices or systems
- Performance under all conditions
- Complete protection against all security threats
- File system scanner accuracy or completeness
- System monitor precision or reliability
- Radio frequency detection accuracy

**Zero Liability**: Hooby Solutions and timotheuzi@hotmail.com shall not be held responsible for:
- Any security breaches or data loss
- False positives or false negatives in threat detection
- System damage or performance issues
- Any consequences resulting from the use or misuse of this application
- Any legal issues arising from the use of this software
- File system scanner results or recommendations
- System monitor accuracy or optimization suggestions
- Radio monitor detections

**User Responsibility**: You assume full responsibility for:
- The security of your systems and data
- Proper configuration and use of this software
- Ensuring compliance with local laws and regulations
- Any decisions made based on the application's output
- Verifying file system scanner results before taking action
- Interpreting and acting on system monitor recommendations
- Handling radio frequency detections

### Privacy Policy
This application collects and processes the following data:

**Collected Data**:
- Network information (IP addresses, MAC addresses, device names)
- Bluetooth device information (MAC addresses, signal strength, device types)
- Hardware sensor data (accelerometer, gyroscope, GPS coordinates, battery)
- System information (CPU usage, memory usage, battery status, OS details)
- File system scanner data (file metadata, content analysis, scan results)
- Network scan data (ports, vulnerabilities, test results)
- System monitor data (performance metrics, resource usage, connections)
- Radio frequency data (SDR devices, signals, bands)
- Application usage logs for debugging purposes

**Data Usage**:
- All data is processed locally on your device
- **No data is transmitted to external servers or saved outside of your phone.**
- Collected data is used solely for security monitoring and threat detection
- Sensor data is used to detect physical movement and environmental changes
- File system scanner data is used for threat identification
- Network data is used for security testing
- System monitor data is used for performance optimization
- Radio data is used for frequency monitoring

**Data Storage**:
- Threat logs and device information are stored locally
- File system scanner results are stored until the next scan
- Network results are maintained for review
- System monitor historical data is retained for trend analysis
- Radio detections are logged
- Users can export logs for analysis or delete them at any time
- No persistent data is stored beyond the application's runtime unless explicitly saved by the user

**Third-Party Access**:
- This application does not share data with third parties
- System permissions are required for security monitoring functionality
- All data access is transparent and documented in this guide

**User Rights**:
- Users can view, export, or delete all collected data
- Users can disable any monitoring feature at any time
- Users can configure file system scanner depth and frequency
- Users can adjust system monitor settings and frequency
- Users can uninstall the application to completely remove all data

### Security Considerations
- This application requires elevated permissions for security monitoring
- Users should verify the application's integrity before installation
- Regular updates are recommended for security improvements
- Users should follow security best practices when configuring the application
- File system scanning may impact system performance
- System monitoring consumes additional system resources
- Radio monitoring requires 
- compatible hardware

### File System Scanner Safety
- Deep file analysis may take significant time on large file systems
- Users should verify scanner results before taking action
- File system scanner may produce false positives
- Users can configure scan depth and frequency

### Network Security Safety
- Users should regularly review scan results
- Testing may affect live applications

### System Monitor Safety
- Continuous monitoring may impact system performance
- Users should adjust monitoring frequency based on needs
- Recommendations should be reviewed before implementation
- Historical data may consume storage space over time

### Radio Monitor Safety
- Requires SDR hardware for full functionality
- Signal detections may include false positives
- Users should verify alerts physically

---
*Hooby Lab - Your Security, Your Responsibility.*
