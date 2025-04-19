# 🛡️ Wireshark-Based Network Security Analysis Project

This project explores a wide range of **network security analysis tasks using Wireshark** on **Windows 11**, as part of the **Google Cybersecurity Certification** course:  
[Connect and Protect: Networks and Network Security](https://www.coursera.org/learn/networks-and-network-security)

---

## 📌 Objectives

- Learn to inspect and analyze packets at different layers of the OSI model
- Detect common protocols and visualize traffic flow
- Identify security flaws such as **FTP credential leaks**
- Understand encrypted vs unencrypted traffic (TLS vs HTTP)
- Document the entire process with examples

---

## 💻 Tools Used

- **Wireshark** (Version X.X)
- **Windows 11**
- Protocol Simulations using: web browser, ping, command prompt, FTP server/client

---

## 🗂️ Project Contents

| Task | Description | Screenshot |
|------|-------------|------------|
| 1. Deep Packet Inspection | Viewing detailed packet info at all layers (Ethernet, IP, TCP, etc.) | ![dpi](media/screenshots/deep-packet-inspection.png) |
| 2. Filtering by Protocols | Filters used: `http`, `ftp`, `dns`, `icmp`, `tcp.port==21` etc. | ![filter](media/screenshots/filtering.png) |
| 3. TCP Stream Analysis | Followed full conversations using `Follow TCP Stream` | ![tcp](media/screenshots/tcp-streams.png) |
| 4. Bandwidth Usage | Used **I/O Graphs** and **Statistics** > **Conversations** | ![bandwidth](media/screenshots/bandwidth.png) |
| 5. DNS Analysis | Captured DNS queries and responses | ![dns](media/screenshots/dns-analysis.png) |
| 6. ICMP Ping Packets | Sent and observed echo requests & replies | ![icmp](media/screenshots/icmp-ping.png) |
| 7. FTP Cleartext Login | Logged in using FTP and captured credentials in plaintext | ![ftp](media/screenshots/ftp-cleartext.png) |
| 8. TLS Handshake | Observed `Client Hello`, `Server Hello`, and certificate | ![tls](media/screenshots/tls-handshake.png) |
| 9. Protocol Hierarchy | Viewed all protocols used in a session via hierarchy view | ![protocol](media/screenshots/protocol-hierarchy.png) |
| 10. View Endpoints and Conversations | Identified top talkers, IPs, and sessions | ![endpoints](media/screenshots/endpoints.png) |

---

## 📸 Screenshots & Demo

📂 All screenshots are stored in `media/screenshots/`  
📼 A screen recording demo is provided in `media/demo-video.mp4`

---

## 🔍 Capture Files

All `.pcapng` files are stored in the `captures/` directory.  
Each file corresponds to a task like FTP, DNS, TLS, etc.

---

## ⚙️ Setup Guide

Refer to [`docs/setup-guide-windows.md`](docs/setup-guide-windows.md) for:
- Wireshark installation on Windows 11
- Npcap adapter setup
- Enabling necessary interfaces

---

## 📈 Observations & Findings

Detailed observations are documented in:
- [`docs/observations-and-findings.md`](docs/observations-and-findings.md)

---

## 📽️ Sample Use Case Video

A full workflow demo is available in `media/demo-video.mp4` (optional but helpful).

---

## 📝 Author

- **Riya Bugalia**  
B.Tech CSE, MIT Manipal  
Course: Google Cybersecurity – Networks & Network Security  
Certificate Link: _[Insert your certificate link here]_

---

## 📎 License

This project is open-source under the MIT License.
