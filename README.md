# 💻 LME Remove Virus Tool

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg) ![PyQt6](https://img.shields.io/badge/PyQt6-GUI-green.svg) ![ADB](https://img.shields.io/badge/ADB-Android_Debug_Bridge-orange.svg)

**LME Remove Virus Tool** is a modern PyQt6-based desktop application designed to detect and remove potentially harmful applications (viruses) from Android devices using ADB (Android Debug Bridge). It provides real-time device information, malware detection, batch uninstalling, and automatic cleaning features with a clean UI and visual progress indicators.

---

## ✨ Features

- 🔌 **Auto-detect connected ADB devices**
- 📱 **Real-time Android device info**
- 🧹 **Scan and categorize installed apps** (User-installed vs Other sources)
- 🛡️ **Detect potentially malicious apps**
- ❌ **Uninstall apps directly from the interface**
- 🤖 **Auto Remove Virus** feature
- 🧠 **Smart App Info: Name, Type, Size, Installer**
- 📊 **Log Output Panel** with tabular formatting
- 🌈 **Modern UI** with gradient backgrounds and icon-enhanced app lists
- ☕ Support button & contact shortcuts built into the UI
- 🚀 **Update checker** via online version control

---

## 🖥 Screenshot

> *(Add a screenshot of the app UI here if available)*  
> ![App Screenshot](screenshot.png)

---

## 🛠 Requirements

- Python `3.10+`
- Android Debug Bridge (ADB)
- Internet connection (for update check)
- `pip install` dependencies:
  ```bash
  pip install PyQt6 psutil packaging
