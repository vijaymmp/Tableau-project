
# 📘 Network Performance Analysis 

## 📌 Project Overview

This project analyzes **mobile network performance** using datasets collected from multiple locations and scenarios. The goal is to evaluate **signal quality, download/upload speeds, latency, jitter, congestion, and user experience metrics** to identify factors affecting network performance.

---

## 🎯 Objectives

* Measure and compare **network speed and signal strength** across different locations.
* Analyze **latency and jitter** to understand real-time communication quality.
* Study the effect of **device, environment, and congestion** on network performance.
* Evaluate **user experience metrics** like video quality, dropped calls, and handovers.
* Provide **recommendations** for improving mobile network performance.

---

## 📂 Dataset Description

Three datasets were used in this project:

1. **network\_data\_part1.csv**

   * Initial set of signal strength, network type, and speed readings.
   * Focus: Core parameters (Signal, Download, Upload, Latency).

2. **network\_data\_part2.csv**

   * Extended with **device and environment-related columns** (Temperature, Battery, Device Model).
   * Focus: Device/Environment influence on network.

3. **network\_data\_part3.csv**

   * Includes **user experience and advanced network metrics** (VoNR, Video Quality, Dropped Connections, Handover Count).
   * Focus: End-user experience and 5G behavior.

---

## 📊 Key Metrics Explained

* **Signal Strength (dBm):** Power level of received signal (closer to 0 = stronger).
* **Download/Upload Speed (Mbps):** Bandwidth performance for user applications.
* **Latency (ms):** Time delay in data transfer; lower = better.
* **Jitter (ms):** Variation in packet delay; impacts video calls/gaming.
* **Congestion Level:** Indicator of how crowded the network is at the time.
* **Dropped Connections:** Number of failed/disconnected sessions.
* **Video Streaming Quality:** User-perceived video experience (Poor, Average, Good).
* **Handover Count:** How often the device switches between towers.
* **VoNR Availability:** Indicates whether advanced 5G voice features are supported.

---

## 🛠️ Tools & Technologies

* **Python (Pandas, Matplotlib, Seaborn)** – Data cleaning & visualization
* **Tableau** – Interactive dashboards
* **Jupyter Notebook / Google Colab** – Analysis environment
* **GitHub** – Version control & project hosting

---

## 📈 Results & Insights

1. **Network Strength & Speed**

   * Stronger signals → higher speeds.
   * 5G consistently outperformed 4G.

2. **Latency & Jitter**

   * Acceptable latency (<100 ms) in most cases.
   * High jitter observed during congestion.

3. **Device & Environment**

   * Older/overheated devices reported lower speeds.
   * Battery level had minimal but noticeable impact.

4. **Congestion Impact**

   * Higher congestion → lower download speeds and higher latency.
   * More handovers in mobile scenarios.

5. **User Experience**

   * Video streaming quality mostly "Good" in strong signal areas.
   * Dropped connections frequent in weak-signal zones.

---

## 📌 Conclusion & Recommendations

* **For Network Providers**: Improve tower density in weak and congested areas.
* **For Users**: Prefer 5G-capable devices in strong-signal zones for better performance.
* **For Researchers**: Extend analysis with **time-based trends** (peak vs off-peak) and **device-specific insights**.

---



