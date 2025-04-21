# 🛡️ Wireshark-Based Network Security Analysis Project

This project showcases several key network security analysis tasks using **Wireshark** on **Windows 11**. It was completed as part of the **Google Cybersecurity Certification** course:  
**Connect and Protect: Networks and Network Security**

---

## 📌 Objectives

- Analyze packets at various layers of the OSI model
- Apply protocol-based filtering and packet inspection
- Monitor DNS queries and ICMP traffic
- Identify insecure communications (e.g., FTP cleartext login)
- Observe TLS handshake for secure connections
- Document all findings with screenshots and video demos

---

## 💻 Tools Used

- Wireshark (Version X.X)
- Windows 11
- Command Prompt, web browser, and FTP client for traffic generation

---

## 🗂️ Project Contents

| Task                             | Description                                                    | Folder                        |
|----------------------------------|----------------------------------------------------------------|-------------------------------|
| 01-packet-inspection-filtering   | View raw packet data and apply protocol filters                | `01-packet-inspection-filtering` |
| 02-tcp-stream-analysis           | Follow TCP streams and inspect session details                 | `04-tcp-stream-analysis`     |
| 03-dns-analysis                  | Observe DNS queries for `www.bing.com`                         | `03-dns-analysis`            |
| 04-icmp-analysis                 | Capture and analyze ICMP Echo Request and Reply                | `02-icmp-analysis`           |
| 05-ftp-cleartext-credentials     | Capture FTP username/password sent in plaintext                | `05-ftp-cleartext-credentials` |
| 06-tls-handshake-analysis        | Examine TLS handshake: Client Hello, Server Hello, etc.        | `06-tls-handshake-analysis`  |
| 07-protocol-hierarchy-graphs     | Analyze overall protocol usage and view I/O graphs             | `07-protocol-hierarchy-graphs` |
| 08-endpoints-conversations       | Identify top IPs, TCP/UDP sessions, and endpoints              | `08-endpoints-conversations` |

---

## 📸 Screenshots & Demos

- Screenshots for each task are in their respective folders under `Screenshots/`
- Each major folder includes a demo `.mp4` video showing the live capture and analysis process

---

## 📂 Folder Structure

Wireshark-Network-Security-Project/
│
├── 01-deep-packet-inspection-filtering/
│   ├── 🕵️ Deep Packet Inspection.md
│   ├── Screenshots/
│   │   ├── arp_filter_view.png
│   │   ├── dns_filter_packets.png
│   │   ├── filter_pane_view.png
│   │   ├── ftp_filter_view.png
│   │   ├── packet_bytes_view.png
│   │   ├── tcp_filter_applied.png
│   │   └── tls_handshake_filter
│   │
│   └── dpi_demo.mp4
│
├── 02-tcp-stream-analysis/
│   ├── 🌐 TCP Stream Analysis.md
│   ├── Screenshots/
│   │   ├── tcp_filter_pane.png
│   │   ├── tcp_flags_syn_ack.png
│   │   ├── tcp_follow.png
│   │   ├── tcp_packet_detail.png
│   │   └── tcp_stream.png
│   └── tcp_stream_analysis.mp4   
│         
├── 03-dns-analysis/
│   ├── 🌐 DNS Analysis.md
│   ├── Screenshots/
│   │   ├── dns_dst_ip.png
│   │   ├── dns_filter_pane.png
│   │   ├── dns_packet_details.png
│   │   ├── dns_query_bing_1.png
│   │   ├── dns_query_bing_2.png
│   │   └── dns_src_ip.png
│   └── dns_analysis_demo.mp4
│
├── 04-icmp-ping-analysis/
│   ├── 📘 ICMP Ping Analysis.md
│   ├── Screenshots/
│   │   ├── icmp_filter_pane.png
│   │   ├── icmp_reply.png
│   │   ├── icmp_request.png
│   │   ├── icmp_request_packet_details.png
│   │   └── request_source_address.png
│   └── icmp_ping_demo.mp4.mp4
│
├── 05-ftp-cleartext-credentials/
│   ├── FTP Cleartext Credentials Capture.md
│   ├── Screenshots/
│   │   ├── ftp_cmd_session.png
│   │   ├── ftp_filter_applied.png
│   │   ├── ftp_pass_request.png
│   │   └── ftp_user_request.png
│   └── ftp_cleartext_demo.mp4
│
├── 06-tls-handshake-analysis/
│   ├── 🔐 TLS Handshake Analysis.md
│   ├── Screenshots/
│   │   ├── client_hello.png
│   │   ├── server_hello.png
│   │   ├── client_change_cipher_spec.png
│   │   ├── server_change_cipher_spec.png
│   │   └── filter_tls_handshake.png
│   └── tls_handshake_demo.mp4
│
├── 07-protocol-hierarchy-graphs/
│   ├── 📊 Protocol Hierarchy & Graphs.md
│   ├── Screenshots/
│   │   ├── io_graph_default.png
│   │   ├── protocol_hierarchy_full.png
│   │   └── statistics
│   └── protocol_hierarchy_graphs_demo.mp4
│
├── 08-endpoints-conversations/
│   ├── 🌐 Endpoints & Conversations Analysis.md
│   ├── Screenshots/
│   │   ├── conversations_tcp.png
│   │   ├── conversations_udp.png
│   │   ├── endpoints_ipv4.png
│   │   └── endpoints_tcp.png
│   └── endpoints_conversations_demo.mp4
│
└── setup/
    ├── 📦 Installation Guide for Wireshark.md
    ├── 🛠️ Wireshark Configuration Guide
    ├── Screenshots/
    │   ├── packet_capturing_window.png
    │   ├── save_capture_demo.png
    │   └── wifi.png
    └── demo.mp4

---

## 📈 Observations & Findings

- **FTP traffic is visible in plaintext**, proving why FTPS/SFTP is critical
- **ICMP traffic** allows simple device reachability checks (e.g., ping to Google)
- **DNS queries reveal browsing activity** and can expose user intent
- **TCP streams** help reconstruct full application-layer data flows
- **TLS handshakes** show encryption initiation and involved certificates
- **Protocol hierarchy** gives a bird’s-eye view of captured traffic types
- **Endpoints and conversations** identify the most active network devices

---

## 🎥 Sample Use Case Video

A full walkthrough of multiple analyses is available via demo videos in each task folder.

---

## 📝 Author

**Riya Bugalia**  
B.Tech CSE, MIT Manipal  
Course: *Google Cybersecurity – Networks & Network Security*  
Certificate Link: _[Insert your certificate link here]_

---

## 📎 License

This project is open-source and available under the **MIT License**.
