# Keylogger-Detector-Python
A simple yet powerful Python-based Keylogger Detection tool that scans running processes for suspicious keylogger-related activity. Ideal for cybersecurity students and hobbyists to understand process monitoring and threat detection using the psutil library.
# 🛡 Keylogger Detector (Python)

This is a simple tool to detect potential keyloggers running on your system by scanning process names for suspicious keywords.

##  How it works
- Scans all running processes using `psutil`
- Looks for keywords like: `keylogger`, `hook`, `spy`, `keyboard`, etc.
- Alerts if any suspicious process is found

##  Requirements
- Python 3.x
- psutil library (`pip install psutil`)

##  How to Run
```bash
python keylogger_detector.py
