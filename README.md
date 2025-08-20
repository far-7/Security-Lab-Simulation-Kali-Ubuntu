# Security+ Lab Simulation – Kali & Ubuntu

This project simulates a small business network environment to demonstrate foundational cybersecurity practices aligned with CompTIA Security+ domains.  
It was conducted in a **virtual lab setup** using Kali Linux (attacker) and Ubuntu (target).

---

## 🔹 Project Overview
- **Environment:** UTM with Kali Linux (2025.1) and Ubuntu Server (22.04 LTS)  
- **Objective:** Perform reconnaissance, exploit weak credentials, analyze network traffic, and apply system hardening.  

---

## 🔹 Methodology
1. **Reconnaissance** – Nmap scanning to identify active services.  
2. **Vulnerability Assessment** – Enumeration of open ports and weak SSH configurations.  
3. **Exploitation Simulation** – Brute force SSH login using Hydra.  
4. **Traffic Analysis** – Captured packets with Wireshark during attack phase.  
5. **System Hardening** – Applied UFW firewall rules, disabled root login, enforced password policies.  
6. **Verification** – Re-scanned system to confirm mitigation effectiveness.  

---

## 🔹 Key Findings
- Weak/default passwords are easily exploitable.  
- Default SSH configurations allow risky root login.  
- Firewall rules significantly reduce the attack surface.  

---

## 🔹 Skills Demonstrated
- Penetration Testing Basics  
- Network Scanning (Nmap)  
- Password Attacks (Hydra)  
- Traffic Capture & Analysis (Wireshark)  
- Linux Firewall & SSH Hardening  
- CompTIA Security+ Domains  

---

## 📄 Report
The full detailed report (with screenshots and methodology) is included in this repository.  

**Author:** Faris Ali  
[SecurityPlus_Lab_Report.pdf](https://github.com/user-attachments/files/21907394/SecurityPlus_Lab_Report.pdf)
