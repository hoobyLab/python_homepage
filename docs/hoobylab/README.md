# Hooby Lab 🛡️

A comprehensive, intelligent security monitoring application built with Flutter, designed for Android and Linux. This project merges and enhances the functionality of various security monitoring tools into a modern, beautiful GUI application.

## 🚀 Overview

Hooby Lab provides real-time oversight of your digital and physical environment. It uses machine learning patterns to detect anomalies in network traffic, Bluetooth signals, and hardware sensor data. **All data processing and storage occurs exclusively on your device; no data is ever transmitted or saved outside of your phone.**

## ✨ Features

### 🔍 Network & WiFi Monitoring
- **Automatic Discovery**: Scans local networks for new and disappeared devices.
- **Threat Detection**: Identifies suspicious open ports (RDP, Telnet, FTP, SMB).
- **WiFi Security**: Detects Rogue Access Points, Evil Twin attacks, and unencrypted networks.
- **Deauthentication Alerts**: Monitors for WiFi deauth attacks (Linux/Rooted Android).

### 📡 Bluetooth Attack Detection
- **Permission Requests**: Requests location and Bluetooth permissions on initial install.
- **Nearby Detection**: Detects nearby Bluetooth devices after first search.
- **Attack Recognition**: Detects KNOB (Proximity), BIAS (Impersonation), and BlueBorne vulnerabilities.
- **AirTag Detection**: Monitors BLE for Apple AirTags and Find My network-enabled devices.
- **Signal Analysis**: Tracks RSSI history to identify potential relay attacks.
- **Selective Blocking**: Capability to block external Bluetooth devices while preserving trusted connections.

### 🤖 AI Anomaly Detection
- **RSSI Anomaly**: Uses standard deviation analysis to flag sudden signal strength changes.
- **Connection Patterns**: Detects unusually frequent connection attempts (potential brute-force/flooding).
- **Mass Device Discovery**: Alerts when a suspicious number of unknown devices appear simultaneously.

### 📊 Hardware Sensor Monitor
- **Real-time Streams**: Live monitoring of Accelerometer, Gyroscope, and Magnetometer.
- **Environment Sensing**: Ambient light detection and precise GPS tracking.
- **Battery Health**: Continuous status monitoring of power levels and charging states.

### 🎨 Beautiful Modern UI
- **Unified Dashboard**: Real-time security status and quick statistics.
- **Dark/Light Mode**: Full support for system-wide themes.
- **Detailed Logs**: Categorized threat logs with severity-based color coding.

### 📁 File System Scanner
- **Deep File Analysis**: Comprehensive scanning of local file systems
- **Threat Detection**: Identifies suspicious files and potential security risks
- **Pattern Recognition**: AI-powered detection of malicious file patterns
- **Real-time Monitoring**: Continuous surveillance of file system changes

### 📊 System Monitor
- **Resource Tracking**: Real-time monitoring of CPU, memory, and disk usage
- **Performance Analytics**: Detailed performance metrics and historical data
- **Alert System**: Notifications for system anomalies and performance issues
- **Optimization Suggestions**: AI-driven recommendations for system improvements

## ⚖️ License

**Copyright (c) 2025-2026 Hooby Solutions & timotheuzi@hotmail.com**

This software is proprietary and owned by Hooby Solutions and timotheuzi@hotmail.com.

### Disclaimer of Warranty
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

### Limitation of Liability
In no event shall Hooby Solutions or timotheuzi@hotmail.com be liable for any direct, indirect, incidental, special, exemplary, or consequential damages (including, but not limited to, procurement of substitute goods or services; loss of use, data, or profits; or business interruption) however caused and on any theory of liability, whether in contract, strict liability, or tort (including negligence or otherwise) arising in any way out of the use of this software, even if advised of the possibility of such damage.

### No Guarantees
This product is provided "as-is" with no guarantees of:
- Security effectiveness or protection capabilities
- Accuracy of threat detection
- Compatibility with all devices or systems
- Performance under all conditions
- Complete protection against all security threats

### User Responsibility
Users assume full responsibility for:
- The security of their systems and data
- Proper configuration and use of this software
- Any consequences resulting from the use or misuse of this application
- Ensuring compliance with local laws and regulations regarding security software

### Third-Party Components
This software may include third-party components that are subject to their own licenses and terms.
