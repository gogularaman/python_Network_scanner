# Network Scanner using Scapy

## Overview
This Python script utilizes the Scapy library to perform a simple network scan to discover devices in a specified IP range. The script sends ARP (Address Resolution Protocol) requests to the target IP or IP range and collects responses to identify active devices along with their corresponding MAC addresses.

## Features
- **Target Specification**: Users can specify the target IP or IP range using the command-line arguments.
- **ARP Requests**: The script sends ARP requests to the specified IP range using Scapy.
- **MAC Address Retrieval**: Captures the MAC addresses of the active devices responding to the ARP requests.
- **Output Formatting**: Displays the results in a clear tabular format showing IP addresses and corresponding MAC addresses.

## Usage
1. Install Scapy: Make sure to install the Scapy library before running the script. You can install it using `pip install scapy`.

2. Run the Script: Execute the script from the command line, providing the target IP or IP range as a command-line argument.
    ```bash
    python network_scanner.py -t 192.168.1.1/24
    ```

## Example
```bash
IP              MAC Address
--------------------------------------
192.168.1.1     00:1a:2b:3c:4d:5e
192.168.1.2     01:2a:3b:4c:5d:6e
...
```

## Dependencies
- Python 3.x
- Scapy library 

## Acknowledgments
- Scapy: [https://scapy.net/](https://scapy.net/)

Feel free to contribute or report issues. Happy scanning!
