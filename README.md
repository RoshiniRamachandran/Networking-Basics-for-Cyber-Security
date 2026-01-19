# Networking-Basics-for-Cyber-Security

 Networking Basics for Cyber Security using Wireshark

This repository documents a hands on practical project focused on understanding fundamental networking concepts and analyzing live network traffic from a cyber security perspective. The primary objective of this work is to gain the ability to capture inspect and interpret packets using Wireshark and to understand how data moves securely and insecurely across a network.

The project begins with learning core networking concepts such as IP addresses MAC addresses DNS TCP and UDP. These concepts form the foundation of how devices communicate on local and global networks. Understanding these basics is essential for anyone interested in cyber security because most attacks exploit weaknesses in network communication.

Wireshark is used as the primary tool to capture live network traffic. After installing Wireshark an active network interface such as Wi Fi or Ethernet is selected and packet capture is started. While browsing websites different types of packets are generated and displayed in real time. This provides visibility into actual network behavior rather than theoretical examples.

Protocol based filters are applied to simplify analysis. Filters such as tcp dns http and udp are used to view specific packet types. Using these filters makes it easier to study individual protocols and understand their structure purpose and behavior during communication.

One important observation made during this task is the TCP three way handshake. The handshake consists of SYN SYN ACK and ACK packets and is used to establish a reliable connection between a client and a server. Observing this process in Wireshark helps in understanding how TCP ensures reliable data transfer.

Another key analysis involves identifying plain text versus encrypted traffic. HTTP traffic is observed to be readable in plain text which shows why it is insecure. HTTPS traffic uses encryption and the packet content appears unreadable which demonstrates how encryption protects sensitive information.

DNS traffic is also captured and analyzed. DNS query packets reveal the domain names requested by the system and DNS response packets return the corresponding IP addresses. This analysis explains how domain name resolution works in real world network communication.

All captured packets are saved in a pcapng file format for offline analysis and documentation. Observations are written in simple language to clearly explain what was captured and what was learned during the process.

Overall this project builds a strong foundation in network traffic analysis. It develops practical skills that are essential for cyber security roles such as security analyst network engineer and penetration tester. By completing this task the ability to analyze network traffic understand protocol behavior and recognize security risks is achieved.

This task is intended for beginners students and aspiring professionals who want practical exposure to networking in cyber security. The structured steps clear observations and saved packet captures make the project suitable for academic evaluation self learning and interview preparation while demonstrating hands on skills through real network analysis. It also encourages ethical use awareness and responsible analysis aligned with fundamental cyber security principles and basic professional documentation standards globally.


![image alt]()
![image alt]()
![image alt]()
![image alt]()
