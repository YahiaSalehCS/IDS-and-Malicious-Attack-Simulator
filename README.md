📌 IDS and Malicious Attack Simulator – Graduation Project
This project is a comprehensive cybersecurity solution that combines a custom-built Intrusion Detection System (IDS) with a realistic Malicious Attack Simulator, forming a self-validating environment for testing network security.

🔐 Intrusion Detection System (IDS)
The IDS component is designed to go beyond traditional signature-based detection by implementing intelligent traffic analysis techniques. It monitors live network packets using Python and Scapy, tracking TCP connection states, inspecting high-volume UDP traffic, and analyzing payload data to detect a wide range of threats.
It is capable of identifying:

Port scanning activity (e.g., Nmap)

Brute-force login attempts (SSH, FTP)

Web-based attacks such as SQL Injection and Cross-Site Scripting (XSS)

The IDS includes a modular structure for parsing and classifying packets in real time, aiming for low false positives and high accuracy. The goal is to provide proactive threat detection in a lightweight and transparent way.

💣 Malicious Attack Simulator
To evaluate the IDS, a custom Attack Simulator is built into the environment. It launches controlled cyberattacks that mimic real-world scenarios, such as:

Brute-force login attempts

SQLi and XSS against web applications

Packet floods and reconnaissance scans

These simulations are conducted within an isolated virtual lab, ensuring safe testing without affecting external networks. The simulator allows continuous feedback testing of the IDS, creating a closed-loop validation system.

📊 Features
Real-time packet inspection and alerting

Self-testing capability using attack generation

Traffic logging and analysis

Modular Python codebase (readable and extensible)

Dashboard-ready structure (Flask-compatible)

🧠 Purpose
The main goal of this project is to bridge the gap between detection and validation. Many IDS systems lack testing environments to prove their reliability. This simulator fixes that by acting as both an attacker and a tester, helping security researchers and teams evaluate IDS performance under realistic threat conditions.

Built using: Python, Scapy, Flask, Wireshark, CICFlowMeter, DVWA, Metasploit
Status: ✅ Completed | 📁 Fully Documented | 🔬 Academic Final Year Project





