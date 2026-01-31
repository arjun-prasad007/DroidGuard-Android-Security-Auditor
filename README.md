🛡️ DroidGuard: Android Security Auditor
DroidGuard is a Python-based automation tool designed to audit the security and health of Android devices using ADB (Android Debug Bridge). It generates a detailed security report in real-time, helping users identify potential privacy risks and monitor hardware status.
✨ Features
Device Identification: Automatically detects device model and serial number.
Third-Party App Audit: Lists all manually installed applications to identify suspicious software.
Permission Scanner: Scans for apps with sensitive permissions like READ_SMS to prevent data leaks.
Hardware Health Monitor: Provides real-time data on battery health, voltage, and charging cycles.
Storage Analysis: Reports disk usage and available space on the device.
Automated Reporting: Generates a timestamped .txt report for documentation.
📸 Screenshots
1. Script Execution (Terminal)
![](/assets/REPORT-1.png)
![](/assets/REPORT-2.png)
3. Generated Security Report

![](/assets/CODE-1.png)
![](/assets/CODE-2.png)
🚀 How to Run


Prerequisites: Install Python and ADB Platform Tools.

Enable USB Debugging on your Android device.

Connect the device and run:

python security_scan.py

![](/assets/SAVED_FILE.png)

Check the generated .txt file in the same directory for the full report.
