# 📄 Automated Bottle Filling System Using Computer Vision and PLC Integration

## 📌 Overview
This repository contains the implementation of an automated bottle filling system capable of adapting to different bottle sizes without requiring dedicated production lines. The system integrates **computer vision**, **PLC control**, and **HMI monitoring** to improve production flexibility, reduce operational costs, and increase efficiency.

## 🎯 Objectives
- Develop a flexible filling system for multiple bottle sizes without manual reconfiguration.
- Integrate real-time **object detection** and **volume estimation** using **OpenCV**.
- Synchronize computer vision outputs with **PLC control** to automate the filling process.
- Provide real-time monitoring and manual override functionality through an **HMI**.

## 🛠️ Technologies & Tools
- 🐍 **Python** (for vision processing)
- 📷 **OpenCV** (computer vision library)
- 🔧 **PLC programming** (including VB Script integration)
- 🖥️ **HMI** (Human-Machine Interface)
- 📡 **Industrial sensors** (photoelectric sensors)
- 🎥 **Camera hardware** (for real-time input)

## 🚀 Key Features
- ✅ Detects different bottle sizes using **background subtraction**, and **Gaussian Mixture Models (GMM)** algorithms.
- ✅ Interfaces with a **PLC** to control filling valves in real-time.
- ✅ Logs production data (bottle count, fill time, volume) to a **CSV file** using **VB Script**.
- ✅ Displays system status and controls through an interactive **HMI**.

## 📝 Results & Contributions
- 🎯 Accurate detection of bottles under varying lighting conditions.
- 🎯 Automatic switching between bottle sizes without stopping production.
- 🎯 Reduced dependency on dedicated production lines, resulting in **cost savings** and **greater flexibility**.
- 🎯 Scalable design applicable to other liquid products like juices and soft drinks.

## 🔄 Future Enhancements
- ➕ Expand detection capabilities for complex shapes and transparent materials.
- ➕ Integrate machine learning models to improve detection accuracy.
- ➕ Extend automation to labeling and packaging stages.

## 📚 References
For a full list of references, see the bibliography in the thesis document.
