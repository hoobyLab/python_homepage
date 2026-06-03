# Dumb Phone User Guide

Welcome to Dumb Phone! This guide helps you navigate the features of this network security application, designed to give you total control over your device's connectivity.

## Table of Contents
1. [Introduction](#introduction)
2. [Dashboard](#dashboard)
3. [Firewall Modes](#firewall-modes)
4. [Custom Firewall Rules](#firewall-rules)
5. [Logs and Activity](#logs-and-activity)
6. [Country Blocklists](#blocklists)
7. [Settings](#settings)

---

## 1. Introduction <a id="introduction"></a>

Dumb Phone uses Android's VPN Service API to intercept and filter network traffic locally on your device. 

**Important:** You must grant **VPN Permission** when prompted for the firewall to function. No data is sent to external servers; all processing is local.

## 2. Dashboard <a id="dashboard"></a>

The Dashboard is your control center:
- **Status Cards**: Quickly toggle between Dumb Phone and Soft Firewall modes.
- **Quick Stats**: See real-time counts of **Blocked** and **Allowed** connections.
- **Recent Activity**: A live preview of the latest network events.

## 3. Firewall Modes <a id="firewall-modes"></a>

### Dumb Phone Mode
The most restrictive state. It follows a "Block All" policy.
- **Behavior**: Disables most network-reliant sensors and blocks all traffic.
- **Exceptions**: System-critical services, phone calls, and SMS are permitted.
- **Best for**: Maximum privacy and focus.

### Soft Firewall
A balanced protection mode.
- **Behavior**: Allows traffic by default but filters it against your **Custom Rules** and **Country Blocklists**.
- **Best for**: Everyday use with enhanced security.

## 4. Custom Firewall Rules <a id="firewall-rules"></a>

Define specific behavior for apps or servers:
- **Rule Types**: 
    - **IP Address**: Target specific servers (e.g., `192.168.1.1`).
    - **App Package**: Target specific apps (e.g., `com.social.app`).
- **Actions**: Set to **Allow** or **Block**.
- **Granularity**: You can specify Ports and Protocols (TCP/UDP) for IP rules.

## 5. Logs and Activity <a id="logs-and-activity"></a>

The **Logs** screen provides a transparent history of your device's networking:
- **Filtering**: Search for specific IP addresses or app names. 
- **Date Range**: View logs from specific days using the calendar filter.
- **Details**: Tap any log entry to see the source IP, destination port, and the process/package responsible.

## 6. Country Blocklists <a id="blocklists"></a>

Prevent data exfiltration to specific regions:
- Toggle entire countries on or off.
- The app categorizes countries by **Threat Level** (High, Medium, Low) based on known security profiles.
- Blocking a country instantly applies to all outgoing traffic in Soft Firewall mode.

## 7. Settings <a id="settings"></a>

- **Permissions**: Check and grant VPN and Storage permissions.
- **Log Retention**: Use the slider to choose how many days (1–30) to keep log history.
- **Load Defaults**: Refresh the threat intelligence database to get the latest IP ranges and country risk profiles.
- **Quick Actions**: Instantly **Clear Logs** or reset your firewall configuration.
