# CodeAlpha_Project_BasicNetworkSniffer
# Network Sniffer

## Description
This project is a simple network sniffer built in Python using the Scapy library. It captures and analyzes network traffic in real-time, allowing users to see the flow of data packets across the network. The sniffer can identify various types of packets, including TCP, UDP, and ICMP, and displays relevant information such as source and destination IP addresses and port numbers.

## Features
- Captures and analyzes network packets in real-time.
- Displays source and destination IP addresses.
- Identifies and displays TCP, UDP, and ICMP packets.
- Simple and easy-to-use command-line interface.

## Installation Instructions

### Prerequisites
- Python 3.x installed on your machine.
- Scapy library for Python. You can install it using pip.
- Npcap (for Windows) to enable packet capturing. And also install Wireshark.

### Steps to Install
1. **Install Python**:
   - Download and install Python from the official website.

2. **Install Scapy**:
   - Open your command prompt or terminal and run the following command:
     ```
     pip install scapy
     ```

3. **Install Npcap** (Windows only):
   - Download and install Npcap. During installation, ensure you check the option for "WinPcap API-compatible mode."

## Instructions

1. **Run the Sniffer**:
   - Open a command prompt or terminal with administrative privileges.
   - Navigate to the directory where the `network_sniffer.py` script is located.
   - Run the script using the following command:
     ```
     python network_sniffer.py
     ```

2. **View Captured Packets**:
   - The sniffer will start capturing packets and display information about each packet in real-time, including:
     - Source IP address
     - Destination IP address
     - Protocol type (TCP, UDP, ICMP)
     - Source and destination ports (for TCP and UDP packets)

3. **Stop the Sniffer**:
   - To stop the sniffer, you can interrupt the process by pressing `Ctrl + C` in the command prompt or terminal.

## Usage Instructions

1. **Clone the Repository**:
   - Use the following command to clone the repository:
     ```bash
     git clone 
     ```
   - Replace `USERNAME` with your GitHub username.

2. **Navigate to the Project Directory**:
   ```bash
   cd network-sniffer
