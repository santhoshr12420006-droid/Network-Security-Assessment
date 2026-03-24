# 🔐 Network Security Assessment

## 📌 Project Overview
This project demonstrates a basic network security assessment using industry-standard tools. It involves scanning a system for open ports and analyzing network traffic to identify potential vulnerabilities.

---

## 🎯 Objective
To perform network scanning and traffic analysis using:
- Nmap
- Wireshark

---

## 🧰 Tools Used
- Nmap (for port scanning and service detection)
- Wireshark (for packet capture and network analysis)

---

## 🌐 Target Environment
- Localhost (127.0.0.1)
- Safe and controlled lab environment

---

## 🔍 Nmap Scan Results
- Identified open ports and services running on the system
- Example findings:
  - Port 135 → MSRPC service
  - Port 445 → SMB service

📁 File: `nmap_results.txt`

---

## 📡 Wireshark Analysis
- Captured real-time network traffic
- Applied filters:
  - DNS → Domain name queries
  - TCP → Network communication

📁 File: `wireshark_capture.pcap`

---

## ⚠️ Vulnerabilities Identified
- Open ports increase attack surface
- SMB (port 445) is commonly targeted
- DNS queries reveal browsing activity
- Network traffic can be analyzed if not secured

---

## 🛡️ Recommendations
- Close unused ports
- Disable unnecessary services (like SMB if not needed)
- Use firewall protection
- Use encrypted protocols (HTTPS)
- Monitor network traffic regularly

---

## 📊 Project Files
- `network_security_assessment.md` → Detailed report
- `nmap_results.txt` → Scan results
- `wireshark_capture.pcap` → Captured traffic
- `dns_filter.png` → DNS analysis screenshot
- `tcp_filter.png` → TCP analysis screenshot

---

## 🎯 Learning Outcome
- Understanding of port scanning and service detection
- Practical experience with packet analysis
- Ability to identify basic network vulnerabilities

---

## 🚀 Conclusion
This project highlights how network scanning and packet analysis can help identify potential security risks and improve system protection.

---

## ⚠️ Disclaimer
This project was conducted for educational purposes only on a local/test environment (127.0.0.1).
