Network Recon & Packet Analysis

Overview
In this project, we will document a workflow for performing local network reconnaissance and packet analysis using **Nmap** and **Wireshark**. The objective was to identify open ports, analyze traffic behavior, and evaluate any possible vulnerabilities for the local subnet of `192.168.1.0/24`.

Files
- `nmapscan.txt`: Output of the TCP SYN scan (`nmap -sS`) across the subnet.
- `wireshark.txt`: Packet capture analysis of SYN traffic and service responses.

Nmap Scan Highlights
- A TCP SYN scan was performed against all hosts in the local subnet.
- Open ports and active IPs were identified.
- Services were fingerprinted and saved in readable format.

Wireshark Analysis
- Live traffic was captured during and after the scan.
- Capture was filtered to show SYN packets and associated handshake responses.
- Packet behavior was confirmed with Nmap results.

Outcome
- We successfully mapped open ports to known services.
- Potential vulnerabilities were identified.
- We created a reproducible workflow for performing future scans.
