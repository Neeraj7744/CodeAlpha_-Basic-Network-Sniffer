Basic Network Sniffer Using Python



📌 Project Overview
This project involves building a simple network sniffer using Python and the scapy library. A network sniffer is a tool used to monitor, capture, and analyze packets of data flowing through a network. This helps in understanding how data is structured during transmission and how various network protocols interact.


🎯 Objectives
Capture real-time network traffic.

Analyze packet structures (IP, TCP, UDP, ICMP).

Understand protocol behavior and data flow on a network.

Display meaningful insights like:

Source & destination IP addresses

Protocol types

Source & destination ports

Payload data



🧰 Technologies Used
Python: General-purpose programming language.

Scapy: A powerful packet manipulation tool used for capturing and analyzing network packets.

Administrator/Root Privileges: Required to access low-level network interfaces.



🧪 How It Works
Packet Capture: The script uses scapy.sniff() to capture packets from the network interface.

Protocol Detection: It checks each packet for IP, TCP, UDP, and ICMP layers.

Data Extraction:

For each packet, it extracts:

IP source and destination

Protocol number

TCP/UDP port numbers

Packet payload (raw data)

Display: The extracted data is printed in a readable format for the user.



💻 Sample Output
yaml
Copy
Edit

[IP] 192.168.1.2 → 8.8.8.8
Protocol: 17
[UDP] Src Port: 55344 → Dst Port: 53
Payload: b'\xab\xcd...'



⚙️ Execution Requirements
Python 3.x

scapy library (pip install scapy)

Admin/root permissions to capture packets

(On Windows) WinPcap or Npcap must be installed

🔒 Disclaimer
Packet sniffing should only be performed on networks you own or have explicit permission to monitor. Unauthorized sniffing may be illegal and unethical.
