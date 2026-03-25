# Wireshark-network-anaysis-lab
This project demonstrates packet capture and network traffic analysis using Wireshark. 
The goal was to analyze communciation between a client device and the first website hosted at info.cern.ch. 


# Objectives 🎯
- Identify local device IP and MAC address
- Perform DNS lookup to resolve domain to IP
- Capture live network traffic using Wireshark
- Analyze HTTP request (GET) and response (200k)
- Examine packet data across:
  - Ethernet layer (MAC addresses)
  - IP layer (IP addresses)
  - TCP layer (ports)
  - Application Layer (HTTP)
 
# Tools Used 🛠️ 
- Wireshark
- Web browser (Safari)
- DNS lookup tools (nslookup)

# Key Concepts Demonstrated 🔍
- Private vs Public IP addressing
- DNS resolution process
- TCP/IP protocol stack
- Packet structure


# Packet Analysis Summary 📊
- Captured HTTP GET request and 200 OK response
- Identified:
  - Source and destination IP addresses
  - MAC addresses at the data link layer
  - TCP port communication (port 80 and ephemeral ports)
- Followed TCP stream to analyze full communcation between client and server


# What I learned 👩🏽‍💻
This project helped me strenghten my understanding of how data travels across networks and how to analyze 
packet-level communication. I gained hands-on experience using Wireshark to inspect HTTP traffic and understand
how devices communicate across different layers of the network stack. 

