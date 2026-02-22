## 📌 Objective
The objective of this task was to perform a basic network scan using Nmap to identify open ports and running services on a local machine.

## 🛠 Tool Used
- Nmap (Zenmap GUI)
- Operating System: Windows
- Target: 127.0.0.1 (Localhost)

## 🚀 Scan Profile Used
Intense Scan

Command executed:
nmap -T4 -A -v 127.0.0.1

## 🔎 Scan Results

The scan identified the following open ports:

| Port | State | Service | Description |
|------|--------|----------|--------------|
| 135/tcp | Open | MSRPC | Microsoft Remote Procedure Call |
| 445/tcp | Open | Microsoft-DS | SMB file and printer sharing |

## 📖 Explanation of Open Ports

### 🔹 Port 135 (MSRPC)
This port is used by Windows systems for Remote Procedure Call (RPC) services. It allows communication between different Windows services and applications.

### 🔹 Port 445 (Microsoft-DS / SMB)
This port is used for Server Message Block (SMB) protocol, which enables file and printer sharing over a network in Windows environments.

## 🖥 OS Detection
Nmap attempted OS detection and identified the system as Microsoft Windows.

## 📂 Files Included
- nmap_scan_results.txt
- Screenshots of scan execution
- README.md

## ✅ Conclusion
The Nmap scan successfully identified active services and open ports on the local system. This demonstrates basic network reconnaissance and port scanning techniques using Nmap.

## ⚠️ Ethical Note
The scan was performed only on my local system (127.0.0.1) for educational purposes.
