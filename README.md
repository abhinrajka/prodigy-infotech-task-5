# Packet Sniffer Tool

## Description
This Python-based packet sniffer captures and analyzes network packets. It displays relevant information such as source and destination IP addresses, protocols, and payload data. The tool is designed for educational purposes and should be used ethically and with proper permissions.

## Features
- Capture and display IP packets
- Analyze and display TCP and UDP packets
- Show source and destination IP addresses
- Show source and destination ports for TCP/UDP packets
- Display payload data

## Prerequisites
- Python 3.x
- `scapy` library

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/abhinrajka/packet-sniffer.git
    ```
2. Navigate to the project directory:
    ```bash
    cd packet-sniffer
    ```
3. Install the required libraries:
    ```bash
    pip install scapy
    ```

## Usage
1. Open a terminal.
2. Run the script with administrative privileges:
    ```bash
    sudo python packet_sniffer.py
    ```
3. The script will start capturing and displaying packet information.

### Example Output

IP Packet: 192.168.1.2 -> 192.168.1.1
TCP Packet: 12345 -> 80
Payload: b'GET / HTTP/1.1\r\nHost: example.com\r\n\r\n'

IP Packet: 192.168.1.1 -> 192.168.1.2
UDP Packet: 53 -> 12345
Payload: b'\x12\x34\x56\x78'


## Important Considerations
- **Ethical Use**: Ensure you have explicit permission to sniff network traffic on any network you are monitoring. Unauthorized packet sniffing can be illegal and unethical.
- **Security**: Handle captured data securely, especially if it contains sensitive information.
- **Legal Compliance**: Be aware of and comply with local laws and regulations regarding network monitoring and packet sniffing.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request with your changes.

## License
This project is licensed under the MIT License 

