\# Network Security Audit \& Traffic Analysis



A comprehensive network security assessment project demonstrating network reconnaissance, active scanning, and packet-level traffic analysis using industry-standard tools.



\## Executive Summary

This project showcases the methodology of auditing a network infrastructure to identify active hosts, open ports, running services, and potential security vulnerabilities, followed by deep packet inspection to analyze network behavior.



\## Phase 1: Reconnaissance \& Scanning (Nmap)

Using \*\*Nmap\*\*, the network was scanned to map the attack surface and gather critical intelligence:

\- \*\*Host Discovery:\*\* Identified active hosts within the subnet.

\- \*\*Port Scanning:\*\* Audited open TCP/UDP ports to find unauthorized entry points.

\- \*\*Service \& OS Detection:\*\* Determined exact service versions and operating systems running to match against known CVEs (Common Vulnerabilities and Exposures).



\## Phase 2: Traffic Analysis \& Deep Packet Inspection (Wireshark)

Using \*\*Wireshark\*\*, network traffic was captured and analyzed to:

\- Monitor protocols and detect anomalies in real-time traffic.

\- Filter and analyze specific packets (e.g., TCP handshakes, DNS queries, and HTTP requests) to inspect plaintext transmissions.

\- Identify potential security risks such as weak encryption protocols or unusual high-volume traffic.



\## Tools \& Technologies

\- \*\*Reconnaissance:\*\* Nmap

\- \*\*Packet Analyzer:\*\* Wireshark

\- \*\*Environment:\*\* Lab / Virtual Network Environments

!\[Wireshark Traffic Analysis](wireshark\_analysis.png)

