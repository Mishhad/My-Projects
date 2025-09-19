# Public WiFi Sniffer Detector

This project detects whether a public WiFi network is being sniffed or monitored by identifying suspicious network activity. It uses packet capturing and analysis techniques to alert the user when unusual behavior is detected.

---

## 🧰 Tools Used
- Kali Linux (or Ubuntu)
- Python 3
- Scapy (Packet analysis library)
- Wireshark (for validation)
- VirtualBox (optional for testing in lab setup)

---

## 🛠️ What I Did
- Developed a Python script using **Scapy** to capture packets.
- Implemented filters to detect suspicious activities (e.g., ARP spoofing, duplicate IPs).
- Designed alerts to notify users of possible sniffing attempts.
- Validated results using **Wireshark**.
- Captured screenshots as proof of working implementation.

---

## 📜 Commands Used
- Start packet capture:
  ```bash
  sudo python3 wifi_sniffer_detector.py

