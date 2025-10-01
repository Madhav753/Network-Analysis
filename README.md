# Network-Analysis
This project involved performing a hands-on network traffic analysis using Wireshark, a widely used packet capture and network protocol analyzer. The objective was to capture live network traffic, identify different protocols in use, and summarize the packet-level communication observed during a browsing session.

Project Overview

This project demonstrates basic network traffic analysis using Wireshark, a popular packet capture and protocol analysis tool. The objective was to capture live network traffic, apply protocol filters, and analyze the behavior of different network protocols in action.

 Objectives

Install and configure Wireshark.
Capture traffic on the active network interface.
Apply filters to analyze different protocols.
Identify and summarize at least 3 protocols in the capture.
Export the capture as a .pcap file for record-keeping.

 Protocols Identified

DNS (Domain Name System): Showed queries and responses for domain resolution.
UDP (User Datagram Protocol): Observed in connectionless communication, primarily used by DNS.
TCP (Transmission Control Protocol): Captured packets included SYN, SYN-ACK, and ACK handshakes, showing reliable connection setup.

Note: No plain HTTP packets were observed, as most modern websites use HTTPS (encrypted traffic), which appears as TLS packets in Wireshark.
