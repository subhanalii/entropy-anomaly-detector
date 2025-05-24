# entropy-anomaly-detector
A forensic detection tool to identify covert data exfiltration using entropy analysis. Detects encrypted or hidden content in files and network traffic, and features live packet sniffing with anomaly alerts.


# 🔍 Entropy-Based Anomaly Detector

A forensic detection tool designed to trace sophisticated data exfiltration attacks using entropy analysis. Capable of analyzing files, PCAP traffic, and live packets to detect encrypted, obfuscated, or steganographic behavior often missed by traditional tools.

---

## 🎯 Project Objective

To build a real-world detection tool tailored to a defined cybercrime scenario:  
**Insider exfiltration of sensitive data using encrypted or steganographic channels.**

---

## 🧠 Key Features

- 📁 Upload-based entropy detection (files, PCAPs)
- 📡 Live packet sniffer with entropy alerts
- 📊 Entropy graph generation & visualization
- 🧾 CSV export of flagged packets/files
- 🛡️ Detects base64, XOR, and high-entropy content
- 🚦 Verdict engine: Normal vs Suspicious
- 🔒 Simulated covert exfiltration demo (`attack.py`)

---

## 🖼️ Web Interface Preview

![image](https://github.com/user-attachments/assets/f8db734a-1788-4448-b324-45837b234302)


---

## 🚀 Getting Started

### 🔧 Requirements

Install dependencies:

```bash
pip install -r requirements.txt
