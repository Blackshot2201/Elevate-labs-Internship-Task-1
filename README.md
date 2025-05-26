# Elevate-labs-Internship-Task-1
# 🚀 Task 1: Scan Your Local Network for Open Ports

## 🔒 Cyber Security Internship Task

### 🎯 Objective:
To perform a basic port scanning operation on the local network using **Nmap**, identify open ports, and understand network exposure risks.

---

## 🛠 Tools Used
- [Nmap](https://nmap.org/download.html)
- (Optional) Wireshark

---

## 📍 Local IP Range Used
- **192.168.146.0/24** (Derived from my local IP address)

---

## 🔍 Command Executed
```bash
nmap -sS 192.168.146.0/24 -oN task1_result.txt
