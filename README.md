# Basic Network Scanners

This repository contains two simple network scanning tools that can identify devices connected to your network, displaying their local IP and MAC addresses.

## Tools

### 1. Sniff_Tool.py

This tool uses `argparse` and `scapy` to create a basic network scanner.

#### Installation

Ensure you have `argparse` and `scapy` installed. They can be installed via pip:

    ```bash
    pip install argparse
    pip install scapy
    ```

#### Usage
Run the script with root or administrative privileges.

##### Syntax:

    ```bash
    python Sniff_Tool.py -ip <ip_address>/<subnet>
    ```

##### Example Output

    ```
    {'ip': '192.168.1.1', 'mac': '7c:a9:6b:07:6e:14'}
    {'ip': '192.168.1.3', 'mac': '88:11:96:ff:79:a0'}
    ...
    ```

### 2. Sniff_Tool2.py

This version uses `sys` and `scapy` for network scanning.

#### Installation
Install `scapy` if you haven't already:

    ```bash
    pip install scapy
    ```

#### Usage
Call this script from the command line using root/admin privileges.

##### Syntax:

    ```bash
    python Sniff_Tool2.py <ip_address>/<subnet>
    ```

#### Note
For best results, use the IP address of your default gateway (router) to get all client IP addresses.

## Additional Information
- It's crucial to use these tools responsibly and within the bounds of applicable laws and regulations.
- These tools are intended for educational purposes and to assist in network administration.
