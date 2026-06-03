# Dumb Phone

A comprehensive network security application for Android that provides real-time protection against threats, monitoring network traffic, and blocking malicious connections through two distinct firewall modes. All processing and logging happen locally on your device; your network traffic data is never sent to external servers.

## Overview

Dumb Phone leverages the Android VPN Service API to intercept, analyze, and filter all outgoing and incoming packets, giving you complete control over your device's network footprint.

## Core Features

### 🛡️ Dual-Mode Firewall

*   **Dumb Phone Mode**: Our most restrictive security profile. It operates on a "Block All by Default" policy, automatically permitting only essential traffic for Voice over IP (VoIP) and text messaging (SIP, SMTP/IMAP).
*   **Soft Firewall Mode**: An intelligent monitoring layer that allows traffic by default while filtering it against customizable rules and threat intelligence.

### 🌍 Global Traffic Control

*   **Country Blacklisting**: Instantly block all communication to and from specific countries. The application utilizes a pre-loaded database of global IP ranges to provide geographical fencing.
*   **Custom Rules Engine**: Define your own granular security policies based on IP addresses, ports, or protocols.

### 📊 Real-time Analysis

*   **Connection Logging**: A detailed, searchable history of every network event. Blocked and allowed connections are clearly categorized with destination metadata and timestamps.
*   **Process Monitoring**: Direct visibility into which running processes are attempting to access the network.

## Privacy & Security

Dumb Phone is built with a "Privacy First" architecture:
*   **Local Processing**: All packet inspection and filtering logic occurs on-device.
*   **Zero Data Export**: Your network logs and activity data remain strictly within your device's secure storage.
*   **No External Dependencies**: The application does not rely on cloud-based analysis, ensuring protection even in isolated environments.

## License

Please see the [LICENSE](LICENSE) file for details.

---
*Classification: Confidential*
